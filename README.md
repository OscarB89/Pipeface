# Pipeface

A Facebook clone project using Ruby on Rails.

#### Homepage

Welcome page with sign up/sing in options

![Screenshot 2021-04-14 at 16 51 19](https://user-images.githubusercontent.com/71934417/114740863-25a67380-9d42-11eb-9691-1f440f93b4ac.png)

#### Post Feed Page

Page displays a feed from all users. We implemented a like as well as comment features.

![Screenshot 2021-04-14 at 16 50 01](https://user-images.githubusercontent.com/71934417/114740887-2dfeae80-9d42-11eb-8cd7-3ab004c758c8.png)

Once a comment has been liked, it can be unliked by the same user

![Screenshot 2021-04-14 at 16 50 45](https://user-images.githubusercontent.com/71934417/114740882-2c34eb00-9d42-11eb-8bce-595d0dd59110.png)

## Quickstart

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```

## Troubleshooting

If you don't have Node.js installed yet, you might run into this error when running rspec:
```
ExecJS::RuntimeUnavailable:
  Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes.
 ```
That is because Rails will use a Javascript runtime (such as Node) under the hood. The easiest way is to install Node by running `brew install node` -
and then run `bundle exec rspec` again

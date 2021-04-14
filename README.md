# AceBook - Pipeface

Welcome page with sign up/sing in options
![Screenshot 2021-04-14 at 16 51 19](https://user-images.githubusercontent.com/71934417/114740863-25a67380-9d42-11eb-9691-1f440f93b4ac.png)

Like/comment features
![Screenshot 2021-04-14 at 16 50 01](https://user-images.githubusercontent.com/71934417/114740887-2dfeae80-9d42-11eb-8cd7-3ab004c758c8.png)

Unlike feature
![Screenshot 2021-04-14 at 16 50 45](https://user-images.githubusercontent.com/71934417/114740882-2c34eb00-9d42-11eb-8bce-595d0dd59110.png)


REQUIRED INSTRUCTIONS:

1. Fork this repository to `acebook-teamname` and customize
the below**

[You can find the engineering project outline here.](https://github.com/makersacademy/course/tree/master/engineering_projects/rails)

2. The card wall is here: <please update>

## How to contribute to this project
See [CONTRIBUTING.md](CONTRIBUTING.md)

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

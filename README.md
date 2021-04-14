# Pipeface

<p align="center">
<img width="250" alt="Screenshot 2021-04-14 at 18 01 55" src="https://user-images.githubusercontent.com/71934417/114750211-a6b63880-9d4b-11eb-9a75-14c1abd2bf1d.png">
 </p>

This project is part of weeks 8 and 9 of Makers Academy. The focus of the project was to practice AGILE methodologies, such as standups and sprint planning sessions, as well as learning Ruby on Rails along the way.

Project requirements were specified by Makers coaches who acted as the client. We were given a set of requirements at the start of the first week and again in the second week.

## User Stories

```
As a user,
So that I can make posts securely,
I would like to be able to sign up with a unique username, email and password
```

```
As an signed up user,
So that I can sign in,
I would like a login page where I enter my email address and password.
```

```
As a user,
When signing in, if I enter incorrect details,
I would like to recieve a prompt to enter my details again
```

```
As a user,
So I can give updates about my life,
I would like to make posts on my wall
```

```
As a user,
If I want to change a post,
I can either update or delete a post
```

```
As a user, 
So I can understand other people's posts better,
I would like to be able to see who made the post and at what time
```

```
As a user,
I want my friends to be able to see my news,
I would like my newest posts to appear first
```

```
As a user,
So that I can see what eveeryone has been doing
I would like to be able to see all posts in one page
```

```
As a user, 
So when I login I see my posts, 
I would like to be redirected to my wall
```

```
As a user, 
So that strangers cant see my posts as a security feature,  
I would like only logged in users to see posts
```

```
As a user, 
So that I have full control over my posts, 
As the owner of posts, only I, can update or delete them 
```

## Further Requirements
- The project should be hosted online so that everyone can visit the website.
- The project should have CI/CD.
- The project should have a test coverage over 90%

## Homepage

Welcome page with sign up/sign in options.

![Screenshot 2021-04-14 at 16 51 19](https://user-images.githubusercontent.com/71934417/114740863-25a67380-9d42-11eb-9691-1f440f93b4ac.png)

## Post Feed Page

Page displays a feed from all users. We implemented a like as well as comment features.

![Screenshot 2021-04-14 at 16 50 01](https://user-images.githubusercontent.com/71934417/114740887-2dfeae80-9d42-11eb-8cd7-3ab004c758c8.png)

Once a comment is liked, it can be unliked by the same user.

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

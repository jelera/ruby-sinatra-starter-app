# Ruby On Sinatra Starter Project
A starter project for Ruby On Sinatra for beginner developers

## Purpose
The purpose of this is to simplify development environment for developers and programmers to make web applications with Ruby on Sinatra.
It is also a good learning tool for developers and programmers who want to learn or switch to Ruby on Sinatra.
---
## Gems Used
- [Sinatra](https://sinatrarb.com/)
- [Sintara-Contrib](https://github.com/sinatra/sinatra/tree/master/sinatra-contrib)
---
## Prerequisites
Before you download there are prerequisites you need to make this project work.
- A Ruby environment such as RVM or RBenv
- Install Ruby with either RBenv or RVM
- The Bundler Gem, after you install Ruby, use `gem install bundler` to install the gem
---
## Installation/Download
Clone the repo, or Download it, place it whereever you like, open any terminal you use, travel to the directory you placed your project and run the command:
```bundle install```
---
### Included
The `app.rb` is the main ruby file used, this will contain the routes you will be making, go into the directory where the `app.rb` is located and run `ruby <main ruby file>`, in this case `<main ruby file>` is the `app.rb` file, afterwards open your browser with `localhost:port` where `port` is the number that shows in the terminal on startup.
---
A `views` folder that contains 5 `.erb` files which include HTML that renders into the web application.
- layout.erb    -> The Default template the app will render
- home.erb      -> The Home template that will render on the layout.erb
- about.erb     -> The About template
- contact.erb   -> The Contact template
- not_found.erb -> The Not Found Template
---
The `Gemfile` and `Gemfile.lock` which are generated after you run the command `bundle init`. You will need the Gemfile if you wish to deploy your web application.
---
### Versioning
#### Version 1.0.0
First Release
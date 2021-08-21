# Redcarpet Gem Example
Demonstrates the use of redcarpet gem for markdown support in text with the help of coderay gem for syntax highlighting.

## Description
The project have been implemented to demonstrate how we can use [redcarpet](https://github.com/vmg/redcarpet) gem to make pages supporting markdown in ruby on rails framework. The [coderay](https://github.com/rubychan/coderay) gem is used to highlight the syntax of code snippet if present in the content. To add media(images, videos and gifs), [Active Storage](https://guides.rubyonrails.org/active_storage_overview.html) is to be used in addition to these gems.

## Install
To setup project locally, follow below instructions.

### Project Configuration
Have ruby version ruby-2.7.2 installed as mentioned in Gemfile.

Install necessary dependencies.
```bash
# install dependencies mentioned in Gemfile
$ bundle install

# verification of already installed files in node_modules
$ yarn install --check-files
```

### Database Setup
Create and Initialize database.
```bash
# migration of database
$ rails db:migrate
```

### Starting the server
To start the server on localhost run the command below. The server will start on default port 3000.
```bash
$ rails s
```


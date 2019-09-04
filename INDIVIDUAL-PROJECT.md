# Individual Project Guidelines

## High Level Steps

## Mentor Actionable Items

1. create Github repository and project

   Note: The student must provide the mentor with the project name.

2. create a Rails Project

   ```text
   rails new project-name -T -d postgresql
   ```

3. add `rails-rspec` with the version information to the `development and test` section of `Gemfile`
   a. bundle and configure

4. add `capybara` with the version information to the `development abd test` section of `Gemfile`
   a. bundle and configure

5. add a controller called `HomesController` with a single action called `index`

6. add an `index.html.erb` view for your `HomesController`

7. add a root route called `home#index` to your `routes.rb` file

## Student Actionable Items

8. enter all user stories within Github project

   a) convert each Github note to a Github issue
   
   b) add a task-list for each Github issue

   Note: https://www.mountaingoatsoftware.com/agile/user-stories

9. for each user-story in user-stories
   a) move the user-story into 'in progress' on Github Project
   
   b) create a feature branch for the user story
   
   c) move the user-story into 'in progess' on Github Project
   
   d) implement the user-story
   
   e) submit a pull-request (PR) with issue(s) implemented for review
   
   f) if PR is approved, mentor will merge into `master` branch and update Github project. The student will deploy to Heroku and go to (9a). Otherwise, go back to step (9c)

   Note: FYI, if the user story is `As a user, I can create a widget`, then the branch name should be something like _user-creates-widget_ and the feature spec should be _user_creates_widget_spec.rb_.

10. create a project video and it should contain the following:

    a) full name
    
    b) project overview
    
    c) demonstration

## Have Questions

If you have any question(s), please do send me a message via Slack.
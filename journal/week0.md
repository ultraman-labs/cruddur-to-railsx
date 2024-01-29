# Setting up .gitpod.yml so that the Gitpod environment is ready to run Rails for each new  workspace instantiantion.
The .gitpod.yml file, so far, contains:

    gem install rails
    gem update --system 3.5.5


 ## Creating the Rails Project
    At the CLI, ran 

```bash 
$ rails new Cruddur
```

## Adding PostgreSQL Gem to Gemfile
Open Gemfile in the root of your Rails project and add the pg gem (PostgreSQL adapter).
After adding it, run 'bundle install' to install the gem:
```ruby
gem 'pg'
```

```bash
bundle install
```
## Install PostgreSQL
```bash
brew install postgresql
```


## Start the Rails serveer with:
```bash
$ rails server
```
    
 ### NOTE: Model-View-Controller (MVC) pattern: 
 Rails uses the MVC pattern to structure your application. This separates the data (model), the presentation (view), and the logic (controller) of your application, making it easier to maintain and understand.   

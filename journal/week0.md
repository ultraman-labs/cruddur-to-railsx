# Setting up .gitpod.yml so that the Gitpod environment is ready to run Rails for each new workspace instantiantion.
The .gitpod.yml file, so far, contains:

    gem install rails
    gem update --system 3.5.5


 ## Creating the Rails Project
    At the CLI, ran 

```bash 
$ rails new Cruddur
```

## Start the Rails server with:
```bash
$ rails server
```
    
 ### NOTE: Model-View-Controller (MVC) pattern: 
 Rails uses the MVC pattern to structure your application. This separates the data (model), the presentation (view), and the logic (controller) of your application, making it easier to maintain and understand.   

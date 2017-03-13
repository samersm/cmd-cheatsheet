# cmd-cheatsheet


## Github

```
* git branch    // To view the list of your branches

* git checkout -b new_branch

* git status

* git add .

* git commit -m "your commit"

* git push

* git reset --hard HEAD         // To revert to a previous commit, ignoring any changes

* git clean -f -d       // to get rid of untracked files and directories in your working copy

* git commit --amend -m "New commit message"     //To edit your latest commit

* git push -f

* git clone <project path>

* rm -rf .git

* heroku domains        //To view all your domains

* heroku rake db:migrate

* git push -f heroku master

* git remote add origin <link>

* git pull / git fetch / git clone

* mkdir <foldername>

* touch <filename>.md

* pwd   // print working directory - shows what directory you are in

* ls    // list the files in this directory

* git log  	//show all commits

* git log —stat 	//Show more details on commits

```


## Rails

```
* rails -h      // to show all command lines)
    
* gem install rails

* rails new name

* bundle install

* bundle check

* gem list

* gem uninstall <gem name>

* rails routes

* cd rails-projects/saasapp/

* rails s -b $IP -p $PORT

* rails c -h    // for show all command lines)

* rails c       -       rails c -s
        Hirb.enable     // related to hirb gem
        Contact.all
        Contact.create(name: "test", description: "test")

* rails g migrate UserProfiles

* rails g controller Users show

* rails g scaffold User title:string decription:string

* rails g paperclip profile avatar

* rails g model Play title:string description:text director:string

* rails g controller Plays -s    // -s means that skip the existing files

* RAILS_ENV=production rake db:migrate 	//To run rails in production mode

* rails server -e production
```


## NodeJS

```
* npm init

* npm install -g

* npm install -s

* npm start

* npm list

* npm list -g --depth=0

* npm cache clean

* npm uninstall <package>

* npm uninstall -g <package>

* nvm install 6  	//To update nodejs to the latest version

* nvm install node

* nvm use 7.4.0

* nvm alias default v7.4.0

* npm install -g npm    // Update npm

* ng serve --host 0.0.0.0 --port $IP  	//to run angular 2 app
```

## python

```
* python —version
* python	 //to go to the python console
        >>> help('modules')  	// to see a list of your installed packages

* python <filename>.py

* sudo easy_install markdown 	//to install new package
```


## django

```
* mysql-ctl start

* python -m django --version

* django-admin startproject <project name>

* python manage.py startapp <page name>

* python manage.py migrate

* python manage.py runserver $IP:$PORT
```
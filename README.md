How Do You Say?
====

##How to run this cool app:

1) Make sure you have npm and git on your command line
```
    $ npm --version and git --version
```
2) Install grunt, bower, yeoman and angular yo generator:
```
    $ npm install -g grunt-cli

    $ npm install -g bower

    $ npm install -g yeoman

    $ npm install -g generator-angular-fullstack
```
3) Install mongoDB (refer to mongodb manuals)

4) Clone repository directly from [here](https://github.com/gsalisi/hdys.git). (you need to be added as collaborator)

5) On the command line, run: (ensure mongoDB connection is working) 
```
	$ mongod 
```
6) Open another command line tab/window, navigate to the root directory of the app using command line, then run:
```
    $ npm install

    $ bower install

    $ grunt serve
```
7) The app should happily run on localhost:9000

===
To optimize your workflow, use yeoman angular-fullstack generator commands.
It can be found [here](https://github.com/DaftMonk/generator-angular-fullstack). 


## Configuration

Start by cloning the repository:

```
$ git clone https://github.com/antblessing/bloc-jams-angular
```

The app uses Grunt to run tasks in development. 

Install the app dependencies by running:

```
$ npm install
```

## Run the Application

Run the application using the Gruntfile's `default` task:

```
$ grunt
```

The default task runs a simple server on port 3000. To view it in a any browser, go to [http://localhost:3000](http://localhost:3000).


## Grunt plugins

A list of the Grunt plugins in this application.

#### Watch

[Grunt watch](https://github.com/gruntjs/grunt-contrib-watch) watches for changes to file content and then executes Grunt tasks when a change is detected.

#### Copy

[Grunt copy](https://github.com/gruntjs/grunt-contrib-copy) copies files from our development folders and puts them in the folder that will be served with the frontend of your application.

#### Clean

[Grunt clean](https://github.com/gruntjs/grunt-contrib-clean) "cleans" or removes all files in your distribution folder (`dist`) so that logic in your stylesheets, templates, or scripts isn't accidentally overridden by previous code in the directory.

#### Hapi

[Grunt Hapi](https://github.com/athieriot/grunt-hapi) runs a server using [`HapiJS`](http://hapijs.com/). Happy is a Node web application framework with robust configuration options.

![image1](http://i392.photobucket.com/albums/pp9/gmb89/Screen%20Shot%202016-05-11%20at%2011.02.21%20PM_zpsu7bdmq6l.png)
![image2](http://i392.photobucket.com/albums/pp9/gmb89/Screen%20Shot%202016-05-11%20at%2010.59.04%20PM_zpsozio1fjt.png)

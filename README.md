## HTML starter template using HTML 5 boilerplate, jade-lang, and gulp

This starter template was intended to help me creating a static html template. it was build using HTML 5 boilerplate as the starter template, gulpjs as the task runner, and jade-lang as the html template engine language

### Structure folder

```
.
+-- .tmp
+-- app
|   +-- assets
|       +-- css
|           +-- style.css
|           +-- normalize.css
|       +-- images
|       +-- js
|           +-- main.js
|           +-- plugins.js
|       +-- vendors
|   +-- base
|       +-- includes
|           +-- head.jade
|           +-- footer.jade
|       +-- index.jade
+-- dist
```

### How to install

 - Install nodejs, documentation on how to install could be found [here](https://nodejs.org/)
 - Do a ```git clone``` from https://github.com/ekarudianto/html-starter-template.git
 - Inside project directory, run ```npm install```
 - Inside project directory, run ```bower install```
 - run ```gulp server```
 - go to ```localhost:9010``` for development mode

### Run in distribution package

Run ```gulp server:dist``` in project directory and go to ```localhost:9050``` for running the web app in distribution package.

### Build the web app

Run ```gulp build``` in project directory and the built will be accessible on ```dist``` folder
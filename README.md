### Install
```
git clone https://github.com/jeffAquinn/jeffAquinn.github.io.git
cd jeffAquinn.github.io.git
```
# Make your own Repo on github!...(username.github.io)"Host it to the web!"

```
cd (username.github.io)
cp -a jeffAquinn.github.io.git (your-username).github.io 
npm i
resume init
resume export index.html
```

# Adding to github
```
git add -A
git commit -m "json resume"
git push
```

# Elegant Theme [![npm version](https://badge.fury.io/js/jsonresume-theme-elegant.svg)](http://badge.fury.io/js/jsonresume-theme-elegant)

Responsive theme for [JsonResume](https://jsonresume.org/) inspired by card layouts.

[Theme Preview](http://themes.jsonresume.org/elegant)

### Contributing
```
$ git clone https://github.com/mudassir0909/jsonresume-theme-elegant.git
$ cd jsonresume-theme-elegant
$ npm install
$ grunt watch // watches for less file changes
$ grunt exec:run_server // Do this in a new terminal tab to run node server
```
Visit [http://localhost:8888](http://localhost:8888) to see the theme in action.


##### Testing JSON changes
You can test your changes by updating `resume.json` file inside `node_modules/resume-schema/` folder. You might want to rerun `grunt exec:run_server` whenever you make any changes to `resume.json`

##### Updating Styles
All the LESS files are organized under the folder `assets/less/`. Please go through the comments inside `theme.less` to find out which file to put your LESS changes. Grunt compiles `assets/less/theme.less` to `assets/css/theme.css` which is used eventually in the theme.

**_Please Do not make any changes inside `assets/css/theme.css`_**

##### Updating Javascript
All the javascript changes go into `index.js` which is responsible for rendering the theme.

##### Adding a new icon
Visit this [wiki page](https://github.com/mudassir0909/jsonresume-theme-elegant/wiki/Adding-a-new-icon)

### Roadmap

[https://github.com/mudassir0909/jsonresume-theme-elegant/labels/enhancement](https://github.com/mudassir0909/jsonresume-theme-elegant/labels/enhancement)

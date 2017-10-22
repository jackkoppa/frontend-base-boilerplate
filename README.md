# Frontend Base Boilerplate
Basic frontend boilerplate with npm, Grunt, responsive images, Sass, postcss, babel, watch, &amp; livereload server

For use in my personal projects, as a simple way to get started (includes a very basic custom css framework) 

## Usage
If `svn` is installed, can run the following from within the root folder of a brand new repository:

```shell
svn export https://github.com/jackkoppa/frontend-base-boilerplate/trunk . --force
```

This will overwrite the current readme, license, and .gitignore for the new repo. So if the new project has already been started, best to just download a zip of this boilerplate from https://github.com/jackkoppa/frontend-base-boilerplate, and extract it into your new project.

That's it - from there, get started on development, and delete everything above this line when updating the README:

___

# PROJECT NAME
## Background
PROJECT BACKGROUND

## Running Locally
### Install
* Node.js & npm ([link](https://nodejs.org/en/download/))
* Grunt.js (after installing Node & npm, run `npm install -g grunt-cli`. [More info](https://gruntjs.com/getting-started))
* ImageMagick (required, in order to use responsive images. [Download instructions](https://www.imagemagick.org/script/download.php))

### Run
```shell
git clone [PROJECT_URL]
cd [PROJECT_NAME]
npm install
grunt serveDev
```
Livereloading server now available at `http://localhost:8000`


Alternative grunt commands:
* `grunt` - compile & lint files, for both development (`dev/`) & production (`dist/`) builds
* `grunt serveProd` - compile, lint, & launch a persistent server for production build
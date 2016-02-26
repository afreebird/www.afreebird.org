# A Free Bird
## Main Website

[A Free Bird™][afreebird] main website built on Jekyllrb Generator with a focus on collaboration.


Project info
------------

- Official website: <http://afreebird.org/>
- Code repository: <https://github.com/afreebird/>
- License: [GNU Affero GPL 3][license]

Getting Started
---------------

- Generator-jekyllrb requires [Node.js](http://nodejs.org/) `>= 0.10`, [Ruby](http://www.ruby-lang.org/) `>= 1.9`
- Install Ruby dependencies: `gem install`
- Install Yeoman Jekyllrb generator: `npm install -g generator-jekyllrb`
- Install NodeJS dependencies: `npm install`


## Running

#### grunt serve

Compiles all files and opens the site in your default browser. A watch task watches for changes to files, recompiles if necessary, and injects the changes into the browser with LiveReload.

#### grunt check

Checks code quality with Jshint and CSS Lint, and Jekyll health with `jekyll doctor`.

#### grunt build

Builds an optimized site to the dist directory. [Usemin blocks](https://github.com/yeoman/grunt-usemin#the-useminprepare-task) are concatenated, [CSS](https://github.com/gruntjs/grunt-contrib-cssmin), [images](https://github.com/gruntjs/grunt-contrib-imagemin), and [HTML](https://github.com/gruntjs/grunt-contrib-htmlmin) are minified, [JavaScript is uglified](https://github.com/gruntjs/grunt-contrib-uglify), and assets are [revved](https://github.com/yeoman/grunt-filerev) for cache busting.

`grunt serve:dist` will run `grunt build` and open the result in your default browser

## Bower, components, and Usemin

[Bower](http://bower.io/) is a package manager for front-end components. Use it to download and manage CSS, JavaScript, and [preprocessor tools](https://github.com/Team-Sass) for your site. Everything in the _bower_components directory is available while running `grunt serve`.

To include components in the build, place them inside of a Usemin block or add them to the `copy:dist` task. This workflow will be streamlined with the release of Usemin 2.0.

## Links

[afreebird]: http://www.afreebird.org
[license]: http://www.gnu.org/licenses/agpl-3.0.html
[pixelmixer]: http://pixel-mixer.com/

Thanks to the many Ruby projects we're using and the [PixelMixer][pixelmixer] icon collection.

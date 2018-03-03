# Embedding SVG icons using a Twig Macro

Learn more about [twig macros](https://twig.symfony.com/doc/2.x/tags/macro.html).

## About this theme
This is a simple Drupal 8 theme which will allow you to test and view the code shared in my blog post.

### Working with the demo_theme theme
* Place this theme inside your drupal's `/themes/custom/` directory
* Enable and make the theme your default theme

### Compiling the theme
* In the command line, navigate to `/themes/custom/demo_theme`
* Run `nvm use`.  If NVM is not found, run `nvm install`
* Run `npm install`
* Run `npm run build`.  This will compile all your theme's code.

### Viewing the social icons
In order to compile this theme you need to have NVM, NPM and Node installed.

Go to `http://your-site/themes/custom/demo_theme/dist/style-guide/section-icons.html`

## Other information which may be useful
Autoprefixer & Babel is set to support:

* IE >= 9
* Last 3 versions of modern browsers.

These can be updated at any time within the `package.json`.

### Run the following commands from the theme directory
If you haven't yet, install nvm:
https://github.com/creationix/nvm

#### Use the right version of node with:
`nvm use`

_This command will look at your `.nvmrc` file and use the version node.js specified in it. This ensures all developers use the same version of node for consistency._

#### If that version of node isn't installed, install it with:
`nvm install`

#### Install npm dependencies with
`npm install`

_This command looks at `package.json` and installs all the npm dependencies specified in it.  Some of the dependencies include gulp, autoprefixer, gulp-sass and others._

#### Runs default task
`npm run build`

_This will run whatever the default task is._

#### Compiles Sass
`npm run compile`

_This will perform a one-time Sass compilation._

#### Runs the watch command
`npm run watch`

_This is ideal when you are doing a lot of Sass changes and you want to make sure every time a change is saved it automatically gets compiled to CSS_

#### Cleans complied directory
`npm run clean`

_This will perform a one-time deletion of all compiled files within the dist/ directory._

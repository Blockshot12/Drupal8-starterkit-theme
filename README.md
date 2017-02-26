# [Drupal 8](https://www.drupal.org/) Starterkit Theme
This is a Drupal 8 Starterkit theme.

* Homepage: [http://blockshot.org/)
* Source: [https://github.com/Blockshot12/Drupal8-starterkit-theme](https://github.com/Blockshot12/Drupal8-starterkit-theme)

## Drupal 8 Theming
Here are some usefull links to documentation/video's:
* [Theming Drupal 8](https://www.drupal.org/docs/8/theming)
* [Component-driven Drupal 8 theming](https://youtu.be/NV8sxz9mDYA)
* [Drupal 8 theme best practices](https://youtu.be/UmLkVV_R69Q)
## Installation
Clone the Starterkit to the themes folder in your drupal installation using the following command:
```
$ git clone https://github.com/Blockshot12/Drupal8-starterkit-theme
```
## Configuration
* Rename the Starterkit folder.
* Rename STARTERKIT.info.yml and STARTERKIT.libraries.yml.
* Find all the TODO's in the Starterkit and replace STARTERKIT with '*your-theme-name*. This includes the gulp *_conf.js* file.

## Dependencies
Install all dependencies with NPM and Bower.
For NPM:
```
$ npm install
```
For Bower:
```
$ bower install
```

## [Gulp](https://www.npmjs.com/package/gulp)

After installing all the dependencies, you can use Gulp with the following commands on the command line:
```
$ gulp build
```
This command will create the *dist* folder with all necessary files and folders.
```
$ gulp watch
```
This command will run the build command and then watching all source files for updates if saved.
```
$ gulp serve
```
This command will run the build command and then start a dev-server on *http://localhost:3000* with BrowserSync. BrowserSync is watching all source files including Drupal template files like *page.html.twig*.

## [BrowserSync with Gulp](https://www.browsersync.io/docs/gulp/)


## Sending Feedback

Here you can leave [your feedback](https://github.com/Blockshot12/Drupal8-starterkit-theme/issues).

## Folder Structure

```
starterkit/
|- bower_components/
|- dist/
|  |- img/
|  |- js/
|  |- css/
|- gulp/
|  |- help/
|- node_modules/
|- src/
|  |- icon/
|  |- img/
|  |- js/
|  |- scss/
|- templates/
|  |- block/
|  |- content/
|  |- content-edit/
|  |- dataset/
|  |- field/
|  |- form/
|  |- layout/
|  |- misc/
|  |- navigation/
|  |- user/
|  |- views/
```
## TODO's

* Favicon integration (is done manually now).

![alt tag](https://raw.github.com/danielauener/generator-wp-grunted-theme/master/header.png)

# wp-theme-generator

A WordPress theme [Yeoman](http://yeoman.io) generator, to kickstart WordPress
theme development with yo, sass and grunt.

**Note:** For now, this generator is an early development version, so expect many
changes and some bugs in both the generator and generated theme.

## What do you get
- A fully funtional WordPress theme with a working *grunt* development environment.
- The generated theme
  - is tested against the [Theme check](http://wordpress.org/plugins/theme-check/) and [Theme Forest check](http://wordpress.org/plugins/themeforest-check/) plugins and runs without errors, warnings or recommendations
  - is visually tested with [Testdata for the theme unit tests](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)
  - runs without errors or warnings in debug mode
  - follows the WordPress coding standards a 100%
- Well structured SCSS development files
- A pre-filled HTML documentation based on the [Themeforest documentation template](http://blog.themeforest.net/site-news/building-better-template-documentation/)
- grunt tasks for
  - compiling, merging and compressing all SCSS files to one *style.css* file
  - compiling, merging and compressing all JS files to one file
  - running jshint on all JS files
  - watching all changes and doing the hinting, compiling and merging automatically
  - generating a production ready distribution version of the theme
  - checking all PHP against WordPress coding standards automatically with PHP_Code_Sniffer


## Getting Started

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```

To install generator-wp-theme from npm, you have to install it from this
github repo, run:

```
$ npm install -g generator-wp-theme
```

Finally, initiate the generator. The most useful place to run this command is in
a working WordPress installations *themes* directory:

```
$ yo wp-theme
```

If you need more information on the provided grunt tasks and theme structure,
read through this article on my blog:
[Yeoman WordPress theme generator – kickstart a grunting SCSS theme](http://www.danielauener.com/yeoman-wordpress-theme-generator/)

### Getting To Know Yeoman

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

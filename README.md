# Angular Material Express Seed

A seed for Angular Material using Express.
This seed tries to follow some of the rules of John Papa's [angular-styleguide](https://github.com/johnpapa/angular-styleguide).

This awesome seed uses a bunch of great tools and technologies such as :

<ul>
    <li>Angular</li>
    <li>Angular Material</li>
    <li>Gulp</li>
    <li>Livereload</li>
    <li>Express</li>
    <li>SASS</li>
    <li>ES6 (ES6 branch)</li>
</ul>

## Dependencies

Gulp is required to build AMES :

    npm install -g gulp

## Install

    npm install

## Run

    npm start

## Build

    gulp

Gulp builds sass, js files and watch for changes in it and in .html files.

To use Livereload you need to install the Livereload extension for your browser.

## John Papa compliance

For references : [angular-styleguide](https://github.com/johnpapa/angular-styleguide)

Single Responsibility  :

    In the public/js/ folder, each file contains only one component.

IIFE :

    All angular components are wrapped in IIFE.

Modules :

    Respect Definitions / Getters / Setters / Named Functions rules

Controllers / Avoid using $scope :

    This seed uses the "controllerAs View" syntax in index.html and templates/objects.html
    and the "controllerAs with vm" syntax in boths controllers.

Bindable Members Up Top

Defer Controller Logic to Services

## References

<ul>
    <li>[Angular](https://angularjs.org/)</li>
    <li>[Angular Material](https://material.angularjs.org/latest/)</li>
    <li>[Gulp](http://gulpjs.com/)</li>
    <li>[Livereload](http://livereload.com/)</li>
    <li>[Express](http://expressjs.com/en/index.html)</li>
    <li>[SASS](http://sass-lang.com/)</li>
    <li>[ES6](http://es6-features.org/)</li>
    <li>[John Papa angular-styleguide](https://github.com/johnpapa/angular-styleguide)</li>
</ul>

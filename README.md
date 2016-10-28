# Skeleton
Compiles SASS into CSS and reloads your changes with Browser Sync
## Dependencies

* [Bourbon](http://bourbon.io) - SASS mixin library

## Developing

If you don't already have [Node](https://nodejs.org/download) installed, you're gonna want to make that happen.

You also might need to update/install npm or bower globally:

```shell
npm install npm -g
npm install bower -g
npm install gulp -g
```
This will install the node packages like gulp-sass and browser sync and pull in bourbon and chartist dependencies:

```shell
npm install
bower install
```

Gulp will start the browser-sync anc compile your CSS. You should be seeing a live updating version of the page now:

```shell
gulp
```

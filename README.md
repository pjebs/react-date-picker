React DatePicker
=================

![Screen shot of Date Picker](https://raw.github.com/pjebs/react-date-picker/master/screenshot.png)

Please read the [documentation](https://github.com/gpbl/react-day-picker) to use all the features of the Date Picker.

There is an example project included to show you how to use this Date Picker component on existing non-React projects.

Note: Although this project is listed on npm, don't use it. Just download the files from GitHub.


### Motivation For Fork
["Lots of people use React as the V in MVC. Since React makes no assumptions about the rest of your technology stack, it's easy to try it out on a small feature in an existing project."](https://facebook.github.io/react/)

I needed to use this awesome datepicker on a recent project. Unfortunately the project was a legacy project using jQuery.
The original date-picker uses node-style require() statements hence it was not possible to use it *easily* with other *little* React components also haphazardly being used.

I had 2 options - look for a different jQuery based date-picker or modify this React date-picker. After looking at the code, this date-picker was simply too good to **not use**.

### Improvements
* No need for Browserify or WebPack - just drop into your existing project and use.
* Use this DatePicker on **existing** projects including jQuery-based projects.
* Improved UI
* A few minor bug fixes
* Uses moment.js and react.js from global scope so other projects can use those libraries without 'doubling-up' and increasing the filesize of the javascript files.

### For Testing

You may have to run chrome in a different mode to run react files outside a local web server

In Terminal (Mac OS X)
open -a 'Google Chrome' --args -allow-file-access-from-files

### For Production

The sample code uses the JSX transformer. Make sure your production code uses a JSX->JS converter to increase execution speed and improve download time. (i.e. the JSX transformer is quite large)

Credits: 
--------
This React Component is a fork of [gpbl/react-day-picker](https://github.com/gpbl/react-day-picker).

Final Notes
------------

If you found this library useful, please **Star** it on github.
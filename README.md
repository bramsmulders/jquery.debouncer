#jquery.debouncer - v1.0.0

Debounce ALL the things

## Installation
* [Bower](http://bower.io/): `bower install --save jquery.debouncer`
* Download: [zip](https://github.com/bramsmulders/jquery.debouncer/zipball/master)
* Git: `git clone https://github.com/bramsmulders/jquery.debouncer`

## Usage
```Javascript
// Register function
debouncer(jQuery, 'smartresize', 'resize', 150);
$window.smartResize(function(){
    // handlers on debounced resize
});
```

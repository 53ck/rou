# rou

Simple fluid, Sass-based, responsive, mobile first grid system for modern browsers — IE8+, Firefox, Safari, Opera, Chrome.

## Installation

* Download: [zip](https://github.com/53ck/rou/zipball/master)
* [Bower](http://bower.io/): `bower install --save rou`
* Git: `git clone https://github.com/53ck/rou.git`

## Setup
```sass
$grid-type      : inline-block // or float
$grid-flex      : true
$grid-offset    : true
$grid-responsive: true
$grid-box-sizing: true
$gutter         : 20px // none for disable

$lap-start      : 481px
$desk-start     : 1024px
$desk-wide-start: 1200px

$mob-end        : $lap-start - 1px
$lap-end        : $desk-start - 1px

$mob-offset     : false
$por-offset     : false
$lap-offset     : false
```

## Browser support

* Google Chrome
* Firefox
* Safari
* Opera
* Internet Explorer 8+

## License

MIT License
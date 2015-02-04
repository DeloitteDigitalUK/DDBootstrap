Digital Bootstrap
===========

[Deloitte Digital](http://www.deloittedigital.com/eu) version of [Twitter Bootstrap](http://getbootstrap.com/) (on steroids)

###What is it?
DDBootstrap has been built on top of **bootstrap-sass** and features
* sass version with **no** dependencies on Ruby Sass gem
* rem sizing
* Deloitte colour palette

###Installation

Please see the appropriate guide for your environment of choice:


### a. Bower

dd-bootstrap Bower package is compatible with node-sass 1.2.3+. You can install it with:

```console
$ bower install dd-bootstrap --save
```

Sass, JS, and all other assets are located at [assets](/assets).

By default, `bower.json` main field list only the main `_bootstrap.scss` and all the static assets (fonts and JS).
This is compatible by default with asset managers such as [wiredep](https://github.com/taptapship/wiredep).

### b. Clone

```console
$ git clone https://github.com/DeloitteDigitalUK/DDBootstrap
```

###Features
**Deloitte Digital colour palette introduced**  
![](https://dl.dropboxusercontent.com/u/79955713/DD/Screen%20Shot%202015-02-04%20at%2010.22.30.png)   
primary green: `$dd-primary-green: #92D400`  
primary dark blue: `$dd-primary-dark-blue: #002776`  
primary bright blue: `$dd-primary-bright-blue: #00A1DE`  
secondary green: `$dd-secondary-green: #3C8A2E`  
secondary blue: `$dd-secondary-blue: #72C7E7`  
secondary lime: `$dd-secondary-lime: #C9DD03`

**Customised existing bootstrap colour classes**  
![](https://dl.dropboxusercontent.com/u/79955713/DD/Screen%20Shot%202015-02-04%20at%2010.57.19.png)  
gray base: `$gray-base: #8C8C8C`  
gray darker: `$gray-darker: #000`  
gray dark: `$gray-dark: #000`  
gray: `$gray: #8C8C8C`  
gray light: `$gray-light: #B4B4B4`  
gray lighter: `$gray-lighter: #DCDCDC`

![](https://dl.dropboxusercontent.com/u/79955713/DD/Screen%20Shot%202015-02-04%20at%2011.37.29.png)   
brand primary: `$brand-primary: $dd-primary-bright-blue`  
brand success: `$brand-success: $dd-secondary-green`  
brand info: `$brand-info: $dd-secondary-blue`  
brand warning: `$brand-warning: $dd-secondary-lime`  
brand danger: immutate

![](https://dl.dropboxusercontent.com/u/79955713/DD/Screen%20Shot%202015-02-04%20at%2011.38.10.png)   
state success background: `$state-success-bg: lighten($dd-secondary-green, 45%)`  
state info background: `$state-info-bg: lighten($dd-secondary-blue, 20%)`  
state warning background: `$state-warning-bg: lighten($dd-secondary-lime, 45%)`  
state danger background: immutate   

####Credits
[@vitkon](http://github.com/vitkon)  
[@mo-lon](http://github.com/mo-lon)  
[@mserino](http://github.com/mserino)

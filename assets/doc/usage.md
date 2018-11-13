Ready Made Starter HTML Template based on [HTML5 Boilerplate homepage](https://html5boilerplate.com/) | [Documentation
table of contents](TOC.md)

# Usage

Ready Made Starter HTML Template based on HTML5 Boilerplate is a very basic HTML template. Using this template developers can start their front-end developing instantly from scratch.

Though this is an HTML template, developers can use it as a base HTML template for any CMS like WordPress etc. In the `style.css` and `main.js`, there is some code which will be very helpful for WordPress theme development.



## Basic structure

The Ready Made Starter HTML Template folder includes the following files and folders:

```
├── assets
|     |--response.css 
├     |── css
│     | 	└── normalize.css
|     |── img
|     |--fonts
|     |--ico
|     |-- doc
|     |── js
│         ├── main.js
│         └── vendor
│              ├── jquery-3.3.1.min.js
│              └── modernizr-3.6.0.min.js
|              |-- html5shiv.min.js
|              |-- respond.min.js 
|     
├
├-- languages
├── style.css
├── humans.txt
├── index.html
├── robots.txt
```

What follows is a general overview of each major part and how to use them.

### assets

This directory contains almost all front-end files. It is intended that developers may find the root directory neat and clean to put their CMS specific files in it.

### css

This directory should contain all your project's CSS files. It includes some
initial CSS to help get you started from a solid foundation. [About the
CSS](css.md).

### fonts

In this directory you can put your embed font files, fontawesome files etc.

### ico

You can put your favicons in this directory.

We put HTML5 Boilerplate icons as example. You must replace them with your own.

If you want to use different Apple Touch Icons for different resolutions please
refer to the [according documentation](extend.md#apple-touch-icons).

### img

Put your all images in this directory.

### js

This directory should contain all your project's JS files. Libraries, plugins,
and custom code can all be included here. It includes some initial JS to help
get you started. [About the JavaScript](js.md).

### doc

This directory contains all the Ready Made Starter HTML Template documentation. You can use it
as the location and basis for your own project's documentation. Or, you can just delete it.

### responsive.css

This is the site's responsive style CSS file. In this file you can find some awesome customized reponsive break points. And of course you can edit as you needed.

### responsive-breakpoints.txt

In this text file you can find some breakpoints which you may use to create your customized responsive.css

### languages

In this directory you can put your .mo and .po file to make the site multi language compatible. We put some files just for placeholder. You must delete those and put yours.

### index.html

This is the default HTML skeleton that should form the basis of all pages on
your site. If you are using a server-side templating framework, then you will
need to integrate this starting HTML with your setup.

Make sure that you update the URLs for the referenced CSS and JavaScript if you
modify the directory structure at all.

Within <head> tag there are some files linked just for instance to guide developers exact where to link them. You must link up yours.

If you are using Google Universal Analytics, make sure that you edit the
corresponding snippet at the bottom to include your analytics ID.

### humans.txt

Edit this file to include the team that worked on your site/app, and the
technology powering it.

### robots.txt

Edit this file to include any pages you need hidden from search engines.
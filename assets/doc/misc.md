Ready Made Starter HTML Template based on [HTML5 Boilerplate homepage](https://html5boilerplate.com/) | [Documentation
table of contents](TOC.md)

# Miscellaneous

* [robots.txt](#robotstxt)
* [humans.txt](#humanstxt)
* [browserconfig.xml](#browserconfigxml)

--

## robots.txt

The `robots.txt` file is used to give instructions to web robots on what can
be crawled from the website.

By default, the file provided by this project includes the next two lines:

 * `User-agent: *` -  the following rules apply to all web robots
 * `Disallow:` - everything on the website is allowed to be crawled

If you want to disallow certain pages you will need to specify the path in a
`Disallow` directive (e.g.: `Disallow: /path`) or, if you want to disallow
crawling of all content, use `Disallow: /`.

The `/robots.txt` file is not intended for access control, so don't try to
use it as such. Think of it as a "No Entry" sign, rather than a locked door.
URLs disallowed by the `robots.txt` file might still be indexed without being
crawled, and the content from within the `robots.txt` file can be viewed by
anyone, potentially disclosing the location of your private content! So, if
you want to block access to private content, use proper authentication instead.

For more information about `robots.txt`, please see:

  * [robotstxt.org](http://www.robotstxt.org/)
  * [How Google handles the `robots.txt` file](https://developers.google.com/webmasters/control-crawl-index/docs/robots_txt)

## humans.txt

The `humans.txt` file is used to provide information about people involved with
the website.

By adding this file, you can prove your authorship (not your property) in an external, fast, easy and accessible way.

The provided file contains three sections: 

  * `TEAM` - this is intented to list the group of people responsible for the website
  * `THANKS` - this is intended to list the group of people that have contributed
  to the webste
  * `TECHNOLOGY COLOPHON` - the section lists technologies used to make the website
  
For more information about `humans.txt`, please see: http://humanstxt.org/

In this template we used a standard from http://humanstxt.org/humans.txt

But, of course, you are free to add any information you want.

If possible, you can also add an author tag to the <head> of the site:
<link type="text/plain" rel="author" href="http://domain/humans.txt" />

Look, there is not fight between meta author name and humans.txt link. They are individual.

Moreover, it's not mandatory to include this humans.txt file to your site. The only aim of this initiative is to know who the authors of the sites we visit are.



## browserconfig.xml

The `browserconfig.xml` file is used to customize the tile displayed when users
pin your site to the Windows 8.1 start screen. In there you can define custom
tile colors, custom images or even [live tiles](https://msdn.microsoft.com/library/dn455106.aspx#CreatingLiveTiles).

By default, the file points to 2 placeholder tile images:

* `tile.png` (558x558px): used for `Small`, `Medium` and `Large` tiles.
  This image resizes automatically when necessary.
* `tile-wide.png` (558x270px): user for `Wide` tiles.

Notice that IE11 uses the same images when adding a site to the `favorites`.

For more in-depth information about the `browserconfig.xml` file, please
see [MSDN](https://msdn.microsoft.com/library/dn320426.aspx).

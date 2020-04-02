# webframe-simple
Simple PHP/HTML template for small web sites

## Description

This is a template for small web sites with SEO friendly URLs, built with PHP.
It includes [Bootstrap 4](https://getbootstrap.com) but use whatever you like.

I like clean and simple whenever possible, so I use this when I want to very
quickly create a small site, with little to no dependencies.  My profile site
[mattjeffery.dev](https://mattjeffery.dev) is an example.

Help yourself if you think it could be useful.

## Usage

The `public` directory should be set as your site's document root. Within
`public` each directory (with the exception of `assets`) represents a menubar
item, and contains an `index.php`. This allows the url to simply reference the
directory.  This `index.php` file references a `content.php` file, which is
often sufficient, but you can make it as complex as you need.

There is not much here, so if you are familiar with how web sites are built in
PHP, it should all make sense.

To get started fork, clone or download this repo. Then, in the `public` directory:

* Rename/add/remove directories to suit your needs
* Modify `navbar.php` and match the menu items with your directories
* Modify `index.php` to include whichever directory you want as your site's default
* modify `assets/css/site.css` and `public/page-start.php` to adjust your site's template

Obviously, modify things however you like. For example, if you don't want a
menubar, modify `page_start.php` and do somethign else.

## License

[Free BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)


# html-attack - A test site intentionally vulernable to XSS attacks

## Getting Started/Prerequesites

This is a very simple HTML/PHP web site. You'll need:
* A web server: Nginx or Apache or rather popular, but there are lotsa of good choices.
* PHP, preferrably something current in the 7.x version tree.

There is no database backend or connectors to any other external services. Just place the contents of this repo in the web server's DOCROOT.

It's basically a self-referencing HTML form that skips input validation. You should be able to input most any reflected XSS attack you like against it and get results.

To learn more about XSS, see: [OWASP XSS Guide](https://owasp.org/www-community/attacks/xss/) and [OWASP XSS Filter Evasion Cheat Sheet](https://owasp.org/www-community/xss-filter-evasion-cheatsheet).

## Warnings

Being intentionally vulnerable, it would be unwise to allow this site to face the public Internet.

It would be equally unwise to place this site on anything other than an empty, non-production server in a non-production environment.

Consider yourself advised.

## Built With:

* [HTML Boilerplate](https://html5boilerplate.com/)
* [PHP](https://www.php.net)

## Author

**Rick Pelletier** - [Gannett Co., Inc. (USA Today Network)](https://www.usatoday.com/)

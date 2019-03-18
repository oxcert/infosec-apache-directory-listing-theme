INFOSEC-THEME: Apache Directory Listing Theme
=============================================

This theme turns the boring default file listing by autoindex mod in Apache into something slightly more presentable.

## Installation ##

### Apache configuration ###

1. Download and extract `simple` from `conf` directory.
2. Use `example.conf` to edit conf file for selected directory / virtual host . (E.g. edit `/etc/apache2/sites-available/000-default.conf` in Ubuntu to use theme everywhere.)
3. Reload Apache.

## Options ##

At `footer.html` there is `ignoreDirectories` variable, where you can set number of directories that should be hidden in breadcrumb navigation.

There is also `ignoreAsNoLink` variable that sets whether to ignore as 'do not display' or ignore as 'no links, but visible'.

## Troubleshooting ##

If you have trouble running `.htaccess` version, try to look at `AllowOverride` directive. 

## Licence ##

[MIT](https://opensource.org/licenses/MIT).

## Footnotes ##

Original theme by [Miroslav Pokorný](https://miroslavpokorny.com/simple-apache-directory-listing-theme).
Icons by [Yusuke Kamiyamane](http://p.yusukekamiyamane.com).

spring-reference-ebook
======================

Conversion of the official Spring Framework Reference to epub, mobi and azw3.

Suitable for reading using e-ink devices such as the Kindle or the Sony PRS product lines.


## Changes
### From 3.2.2.RELEASE to 3.2.3.RELEASE

#### 11.3.6 Spring MVC Test Framework

- Changed *example of a test requesting account information in JSON format*.

#### 14.2 Using the JDBC core classes to control basic JDBC processing and error handling

- Changed examples from `jdbcTemplate.queryForInt` to `jdbcTemplate.queryForObject`.
- Removed cast to `(String)` in the `jdbcTemplate.queryForObject` example.


## Older versions

You can download older versions of these docs on the [releases](https://github.com/regueiro/spring-reference-ebook/releases) page.


## Development
Created with [Sigil](http://code.google.com/p/sigil/) as epub, using the official documentation available at [SpringSource](http://static.springsource.org/spring/docs/).

Converted to azw3 and mobi using [Calibre](http://calibre-ebook.com/).



## Copyright
These files are free for use and modification by anyone, provided they comply with the terms of use of the documentation noted below. I do not claim any copyright on the contents of the files.

**Documentation copyright &copy; 2004-2013 - The SpringSource Team**

*Copies of this document may be made for your own use and for distribution to others, provided that you do not charge any fee for such copies and further provided that each copy contains this Copyright Notice, whether distributed in print or electronically.*
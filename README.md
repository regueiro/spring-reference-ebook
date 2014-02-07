spring-reference-ebook
======================

Conversion of the official Spring Framework Reference to epub, mobi and azw3.

Suitable for reading using e-ink devices such as the Kindle or the Sony PRS product lines.


## Changes

### From 4.0.0.RELEASE to 4.0.1.RELEASE

#### 4.4.2 Dependencies and configuration in detail

- Added note regarding the removal of the local attribute on the ref element.

#### 9.9.2 Using metadata-driven auto-proxying

- Updated the last example.

#### 10.3.5 Integration Testing

- Updated examples adding one more configuration.

#### Other

- Added section **20.2.5: Configuring the WebSocket Engine**.
- Corrected typos.

### From 3.2.5.RELEASE to 4.0.0.RELEASE

Too many changes to list here.


### From 3.2.5.RELEASE to 3.2.6.RELEASE

No changes.


### From 3.2.4.RELEASE to 3.2.5.RELEASE

#### 14.7.4 Handling complex types for stored procedure calls

- Corrected the examples.

#### 16.9.1 XStreamMarshaller

- Added some more text to the warning.

#### 17.11.3 Handling Standard Spring MVC Exceptions

- Corrected typo: Changed `ContentNeogitatingViewResolver` to `ContentNegotiatingViewResolver`.


### From 3.2.3.RELEASE to 3.2.4.RELEASE

#### 12.5.6 Using @Transactional

- Table 12.3. @Transactional properties:
	- Changed `rollbackForClassname` to `rollbackForClassName`.
	- Changed `noRollbackForClassname` to `noRollbackForClassName`.

#### 14.2.1 JdbcTemplate

- Updating (INSERT/UPDATE/DELETE) with jdbcTemplate: Changed `"update t_actor set = ? where id = ?",` to `"update t_actor set last_name = ? where id = ?",`.


### From 3.2.2.RELEASE to 3.2.3.RELEASE

#### 11.3.6 Spring MVC Test Framework

- Changed *example of a test requesting account information in JSON format*.

#### 14.2 Using the JDBC core classes to control basic JDBC processing and error handling

- Changed examples from `jdbcTemplate.queryForInt` to `jdbcTemplate.queryForObject`.
- Removed cast to `(String)` in the `jdbcTemplate.queryForObject` example.


## Older versions

You can download older versions of these docs at the [releases](https://github.com/regueiro/spring-reference-ebook/releases) page.


## Development
Created with [Sigil](http://code.google.com/p/sigil/) as epub, using the official documentation available at [SpringSource](http://static.springsource.org/spring/docs/).

Converted to azw3 and mobi using [Calibre](http://calibre-ebook.com/).



## Copyright
These files are free for use and modification by anyone, provided they comply with the terms of use of the documentation noted below. I do not claim any copyright on the contents of the files.

**Documentation copyright &copy; 2004-2013 - The SpringSource Team**

*Copies of this document may be made for your own use and for distribution to others, provided that you do not charge any fee for such copies and further provided that each copy contains this Copyright Notice, whether distributed in print or electronically.*

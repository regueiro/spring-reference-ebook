## Changelog for spring-reference-ebook

### From 4.0.1.RELEASE to 4.0.2.RELEASE

#### 16.3.2 Mapping Requests With @RequestMapping

- Removed tip: @RequestMapping On Interface Methods.
- New section @Controller's and AOP Proxying.

#### 16.3.3 Defining @RequestMapping handler methods

- Added org.springframework.http.HttpMethod for the HTTP request method. as a supported method argument type.
- Removed note: When using controller interfaces...

#### Other

- Some small changes in formatting and minor corrections.

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
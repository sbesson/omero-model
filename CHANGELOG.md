5.6.10 (March 2023)
-------------------

- Push to releases folder on artifactory ([#92](https://github.com/ome/omero-model/pull/92))
- Bump to Bio-Formats 6.12.0 ([#91](https://github.com/ome/omero-model/pull/91))

5.6.9 (November 2022)
---------------------

- Bump to TestNG 7.5 ([#88](https://github.com/ome/omero-model/pull/88))
- Bump to Bio-Formats 6.11.1 ([#87](https://github.com/ome/omero-model/pull/87))
- Fix link to PostgreSQL documentation ([#86](https://github.com/ome/omero-model/pull/86))

5.6.8 (September 2022)
----------------------

- Bump to Bio-Formats 6.10.1 ([#85](https://github.com/ome/omero-model/pull/85))

5.6.7 (June 2022)
-----------------

- Use release 5.5.4 of org.openmicroscopy.project plugin ([#84](https://github.com/ome/omero-model/pull/84))

5.6.6 (June 2022)
-----------------

- Bump to Bio-Formats 6.10.0 ([#82](https://github.com/ome/omero-model/pull/82))
- Add configuration to override floating-point pixel data behavior ([#81](https://github.com/ome/omero-model/pull/821))
- Add Gradle publication workflow ([#83](https://github.com/ome/omero-model/pull/83))

5.6.5 (April 2022)
------------------

- Bump to Bio-Formats 6.9.1 ([#79](https://github.com/ome/omero-model/pull/79))

5.6.4 (April 2022)
------------------

- Bump to Bio-Formats 6.9.0 ([#70](https://github.com/ome/omero-model/pull/70))
- Bump dsl plugin version 5.5.2 ([#69](https://github.com/ome/omero-model/pull/69))

5.6.3 (April 2021)
------------------

- Add support for Gradle 6 ([#66](https://github.com/ome/omero-model/pull/66))
- Use mavenCentral ([#67](https://github.com/ome/omero-model/pull/67))
- Link to external documentation about quartz-scheduler CronExpression.html ([#67](https://github.com/ome/omero-model/pull/64))


5.6.2 (September 2020)
----------------------

- New properties to configure JDBC ([#60](https://github.com/ome/omero-model/pull/60))

5.6.1 (July 2020)
-----------------

- Bump to Bio-Formats 6.5.1 ([#53](https://github.com/ome/omero-model/pull/53))
- Remove junit dependency ([#52](https://github.com/ome/omero-model/pull/52))

5.6.0 (April 2020)
------------------

- Provide SQL means of fetching users' pretty name and e-mail ([#51](https://github.com/ome/omero-model/pull/51))

5.5.5 (March 2020)
------------------

- Display unit test output instead of caching it
  ([#48](https://github.com/ome/omero-model/pull/48))
- Security vulnerability fixes for
  [2019-SV3](https://www.openmicroscopy.org/security/advisories/2019-SV3-user-privacy/) and
  [2019-SV5](https://www.openmicroscopy.org/security/advisories/2019-SV5-bypass-filters/)

5.5.4 (February 2020)
---------------------

- Add `omero.pixeldata.max_projection_bytes` to dependency stack ([#134](https://github.com/ome/omero-model/pull/47))

5.5.3 (December 2019)
---------------------

- Bump to Bio-Formats 6.3.1 ([#44](https://github.com/ome/omero-model/pull/44))
- Fix NPE issue with nulls in ordered collections ([#43](https://github.com/ome/omero-model/pull/43))

5.5.2 (July 2019)
-----------------

- Bump to Bio-Formats 6.1.1 ([#40](https://github.com/ome/omero-model/pull/40))
- Use offline Hibernate DTD ([#41](https://github.com/ome/omero-model/pull/41))

5.5.1 (June 2019)
-----------------

- Adjust combined_fields annotations for search.

5.5.0 (May 2019)
----------------

- Include Bio-Formats 6.1.0.
- Add omero.pixeldata.memoizer.dir to set BioFormatsCache.
- Note current deprecations in model mapping files.
- Add @Deprecation annotations to ome.model.* classes.
- Replace http by https when suitable.
- Reduce the number of declarations for Bio-Formats dependencies.
- Convert Unicode in properties file to non-literal.
- Use Java's CascadeType.DETACH instead of Hibernate's EVICT.
- Partially migrate Properties file from the openmicroscopy repository.
- Deprecate fields.
- Update Hibernate DTD URL to current recommendation.
- Add License file.
- Provide configurable indexer for text fields.
- Fix Enumeration generation.
- Improve SqlAction Exception handling.
- Run units test in Travis.
- Fix Javadoc warnings.
- Use new Gradle build system.
- Extract omero-model from the openmicroscopy repository.

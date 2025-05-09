# CHANGELOG - varnish

<!-- towncrier release notes start -->

## 4.0.0 / 2024-10-04 / Agent 7.59.0

***Removed***:

* Remove support for Python 2. ([#18580](https://github.com/DataDog/integrations-core/pull/18580))

***Fixed***:

* Bump the version of datadog-checks-base to 37.0.0 ([#18617](https://github.com/DataDog/integrations-core/pull/18617))

## 3.0.0 / 2024-10-01 / Agent 7.58.0

***Changed***:

* Bump minimum version of base check ([#18733](https://github.com/DataDog/integrations-core/pull/18733))

***Added***:

* Bump the python version from 3.11 to 3.12 ([#18212](https://github.com/DataDog/integrations-core/pull/18212))

## 2.1.0 / 2024-01-05 / Agent 7.51.0

***Added***:

* Bump the Python version from py3.9 to py3.11 ([#15997](https://github.com/DataDog/integrations-core/pull/15997))

## 2.0.0 / 2023-08-10 / Agent 7.48.0

***Changed***:

* Bump the minimum base check version ([#15427](https://github.com/DataDog/integrations-core/pull/15427))

***Added***:

* Update generated config models ([#15212](https://github.com/DataDog/integrations-core/pull/15212))

***Fixed***:

* Fix types for generated config models ([#15334](https://github.com/DataDog/integrations-core/pull/15334))

## 1.14.4 / 2023-07-10 / Agent 7.47.0

***Fixed***:

* Bump Python version from py3.8 to py3.9 ([#14701](https://github.com/DataDog/integrations-core/pull/14701))

## 1.14.3 / 2023-01-20 / Agent 7.43.0

***Fixed***:

* Fix UNKNOWN service check with backend:name ([#13706](https://github.com/DataDog/integrations-core/pull/13706))

## 1.14.2 / 2022-12-09 / Agent 7.42.0

***Fixed***:

* Stop using deprecated `distutils.version` classes ([#13408](https://github.com/DataDog/integrations-core/pull/13408))

## 1.14.1 / 2022-05-15 / Agent 7.37.0

***Fixed***:

* Refactor methods ([#11909](https://github.com/DataDog/integrations-core/pull/11909))
* Adapt to new check signature ([#11910](https://github.com/DataDog/integrations-core/pull/11910))
* Do not raise exceptions on empty output of varnishadm ([#11908](https://github.com/DataDog/integrations-core/pull/11908))

## 1.14.0 / 2022-04-05 / Agent 7.36.0

***Added***:

* Add metric_patterns options to filter all metric submission by a list of regexes ([#11695](https://github.com/DataDog/integrations-core/pull/11695))

## 1.13.0 / 2022-02-19 / Agent 7.35.0

***Added***:

* Add `pyproject.toml` file ([#11452](https://github.com/DataDog/integrations-core/pull/11452))

***Fixed***:

* Fix namespace packaging on Python 2 ([#11532](https://github.com/DataDog/integrations-core/pull/11532))

## 1.12.1 / 2022-01-08 / Agent 7.34.0

***Fixed***:

* Add comment to autogenerated model files ([#10945](https://github.com/DataDog/integrations-core/pull/10945))

## 1.12.0 / 2021-10-04 / Agent 7.32.0

***Added***:

* Disable generic tags ([#10027](https://github.com/DataDog/integrations-core/pull/10027))

## 1.11.0 / 2021-08-22 / Agent 7.31.0

***Added***:

* Use `display_default` as a fallback for `default` when validating config models ([#9739](https://github.com/DataDog/integrations-core/pull/9739))

## 1.10.0 / 2021-05-28 / Agent 7.29.0

***Added***:

* Add runtime configuration validation ([#9001](https://github.com/DataDog/integrations-core/pull/9001))

## 1.9.2 / 2021-03-07 / Agent 7.27.0

***Fixed***:

* Rename config spec example consumer option `default` to `display_default` ([#8593](https://github.com/DataDog/integrations-core/pull/8593))
* Bump minimum base package version ([#8443](https://github.com/DataDog/integrations-core/pull/8443))

## 1.9.1 / 2020-12-11 / Agent 7.25.0

***Fixed***:

* Skip metrics instead of throwing exceptions ([#8053](https://github.com/DataDog/integrations-core/pull/8053))

## 1.9.0 / 2020-10-31 / Agent 7.24.0

***Added***:

* [doc] Add encoding in log config sample ([#7708](https://github.com/DataDog/integrations-core/pull/7708))

***Fixed***:

* Fix parsing of varnishstat 6.5 JSON output ([#7731](https://github.com/DataDog/integrations-core/pull/7731)) Thanks [vcabbage](https://github.com/vcabbage).

## 1.8.0 / 2020-09-21 / Agent 7.23.0

***Added***:

* Add config spec for varnish ([#7538](https://github.com/DataDog/integrations-core/pull/7538))

***Fixed***:

* Fix style for the latest release of Black ([#7438](https://github.com/DataDog/integrations-core/pull/7438))

## 1.7.0 / 2020-05-17 / Agent 7.20.0

***Added***:

* Allow optional dependency installation for all checks ([#6589](https://github.com/DataDog/integrations-core/pull/6589))

## 1.6.1 / 2020-04-04 / Agent 7.19.0

***Fixed***:

* Update deprecated imports ([#6088](https://github.com/DataDog/integrations-core/pull/6088))
* Remove logs sourcecategory ([#6121](https://github.com/DataDog/integrations-core/pull/6121))

## 1.6.0 / 2020-01-13 / Agent 7.17.0

***Added***:

* Use lazy logging format ([#5377](https://github.com/DataDog/integrations-core/pull/5377))

## 1.5.0 / 2019-12-02 / Agent 7.16.0

***Added***:

* Add version metadata ([#4952](https://github.com/DataDog/integrations-core/pull/4952))

***Fixed***:

* Remove shlex ([#5065](https://github.com/DataDog/integrations-core/pull/5065))

## 1.4.0 / 2019-05-14 / Agent 6.12.0

***Added***:

* Adhere to code style ([#3579](https://github.com/DataDog/integrations-core/pull/3579))

## 1.3.1 / 2019-03-29 / Agent 6.11.0

***Fixed***:

* ensure_unicode with normalize for py3 compatibility ([#3218](https://github.com/DataDog/integrations-core/pull/3218))

## 1.3.0 / 2019-01-04 / Agent 6.9.0

***Added***:

* Support Python 3 ([#2810](https://github.com/DataDog/integrations-core/pull/2810))

## 1.2.1 / 2018-09-04 / Agent 6.5.0

***Fixed***:

* Make sure all checks' versions are exposed ([#1945](https://github.com/DataDog/integrations-core/pull/1945))
* Add data files to the wheel package ([#1727](https://github.com/DataDog/integrations-core/pull/1727))

## 1.2.0 / 2018-05-11

***Added***:

* Add custom tag support for service checks.

## 1.1.2 / 2018-03-23

***Added***:

* Add support for collecting varnishadm service checks for Varnish 5 ([#1130](https://github.com/DataDog/integrations-core/issues/1130))

## 1.1.1 / 2018-02-13

***Added***:

* Adding configuration for log collection in `conf.yaml`

## 1.1.0 / 2018-01-10

***Changed***:

* Use JSON with varnishstat starting varnish 5.0.0 ([#939](https://github.com/DataDog/integrations-core/pull/939))

## 1.0.6 / 2017-11-21

***Fixed***:

* Fixes pulling backend service check when its manually overriden ([#](https://github.com/DataDog/integrations-core/issues/805))

## 1.0.5 / 2017-10-10

***Fixed***:

* Fixes broken service check behavior ([#795](https://github.com/DataDog/integrations-core/issues/795))
* Fix `varnishadm backend.list -p` parsing for newer versions of Varnish ([#739](https://github.com/DataDog/integrations-core/issues/739)) (Thanks [@philipseidel](https://github.com/philipseidel))

## 1.0.4 / 2017-08-28

***Added***:

* Support for passing additional parameters to varnishstat and varnishadm in order to better support service discovery ([#498](https://github.com/DataDog/integrations-core/issues/498), thanks [@philipseidel](https://github)com/philipseidel)

## 1.0.3 / 2017-07-18

***Fixed***:

* Fixes an issue with retrieving the backend service checks. Special thanks to [@adongy](https://github.com/adongy) for finding this! [#582](https://github.com/DataDog/integrations-core/issues/582)

## 1.0.2 / 2017-07-18

***Added***:

* adds ability to filter metrics using the -f option of varnishstat ([#361](https://github)com/DataDog/integrations-core/issues/361)

## 1.0.1 / 2017-06-05

***Added***:

* Support varnish 4.1 for the service check using varnishadm ([#360](https://github)com/DataDog/integrations-core/issues/360)

## 1.0.0 / 2017-03-22

***Added***:

* adds varnish integration.

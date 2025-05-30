# CHANGELOG - ssh_check

<!-- towncrier release notes start -->

## 4.2.1 / 2025-04-17

***Fixed***:

* SSH service will report OK only if it is fully authenticated ([#20050](https://github.com/DataDog/integrations-core/pull/20050))

## 4.2.0 / 2025-02-20 / Agent 7.64.0

***Added***:

* Update dependencies ([#19576](https://github.com/DataDog/integrations-core/pull/19576))

## 4.1.0 / 2025-01-25 / Agent 7.63.0

***Added***:

* Update dependencies ([#19430](https://github.com/DataDog/integrations-core/pull/19430))

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

## 2.10.0 / 2024-09-05

***Added***:

* Update dependencies ([#18478](https://github.com/DataDog/integrations-core/pull/18478))

## 2.9.0 / 2024-08-09 / Agent 7.57.0

***Added***:

* Allow forcing SHA1 encryption for older SSH servers. Set `force_sha1: true` in conf.yaml. ([#18086](https://github.com/DataDog/integrations-core/pull/18086))

## 2.8.0 / 2024-01-05 / Agent 7.51.0

***Added***:

* Bump the Python version from py3.9 to py3.11 ([#15997](https://github.com/DataDog/integrations-core/pull/15997))
* Update dependencies ([#16502](https://github.com/DataDog/integrations-core/pull/16502))

## 2.7.0 / 2023-08-18 / Agent 7.48.0

***Added***:

* Update dependencies for Agent 7.48 ([#15585](https://github.com/DataDog/integrations-core/pull/15585))

***Fixed***:

* Update datadog-checks-base dependency version to 32.6.0 ([#15604](https://github.com/DataDog/integrations-core/pull/15604))

## 2.6.0 / 2023-08-10

***Added***:

* Update generated config models ([#15212](https://github.com/DataDog/integrations-core/pull/15212))

***Fixed***:

* Fix types for generated config models ([#15334](https://github.com/DataDog/integrations-core/pull/15334))

## 2.5.0 / 2023-07-10 / Agent 7.47.0

***Added***:

* Bump dependencies for Agent 7.47 ([#15145](https://github.com/DataDog/integrations-core/pull/15145))

***Fixed***:

* Bump Python version from py3.8 to py3.9 ([#14701](https://github.com/DataDog/integrations-core/pull/14701))

## 2.4.0 / 2023-04-14 / Agent 7.45.0

***Added***:

* Update dependencies ([#14357](https://github.com/DataDog/integrations-core/pull/14357))

## 2.3.3 / 2023-01-20 / Agent 7.43.0

***Fixed***:

* Update dependencies ([#13726](https://github.com/DataDog/integrations-core/pull/13726))

## 2.3.2 / 2022-08-05 / Agent 7.39.0

***Fixed***:

* Dependency updates ([#12653](https://github.com/DataDog/integrations-core/pull/12653))

## 2.3.1 / 2022-05-15 / Agent 7.37.0

***Fixed***:

* Upgrade dependencies ([#11958](https://github.com/DataDog/integrations-core/pull/11958))

## 2.3.0 / 2022-04-05 / Agent 7.36.0

***Added***:

* Upgrade dependencies ([#11726](https://github.com/DataDog/integrations-core/pull/11726))
* Add metric_patterns options to filter all metric submission by a list of regexes ([#11695](https://github.com/DataDog/integrations-core/pull/11695))

## 2.2.0 / 2022-02-19 / Agent 7.35.0

***Added***:

* Add `pyproject.toml` file ([#11439](https://github.com/DataDog/integrations-core/pull/11439))

***Fixed***:

* Fix namespace packaging on Python 2 ([#11532](https://github.com/DataDog/integrations-core/pull/11532))

## 2.1.1 / 2022-01-08 / Agent 7.34.0

***Fixed***:

* Add comment to autogenerated model files ([#10945](https://github.com/DataDog/integrations-core/pull/10945))

## 2.1.0 / 2021-10-04 / Agent 7.32.0

***Added***:

* Update dependencies ([#10258](https://github.com/DataDog/integrations-core/pull/10258))
* Disable generic tags ([#10027](https://github.com/DataDog/integrations-core/pull/10027))

## 2.0.0 / 2021-08-22 / Agent 7.31.0

***Changed***:

* Remove messages for integrations for OK service checks ([#9888](https://github.com/DataDog/integrations-core/pull/9888))

***Fixed***:

* Fix typos in log lines ([#9907](https://github.com/DataDog/integrations-core/pull/9907))

## 1.12.0 / 2021-07-12 / Agent 7.30.0

***Added***:

* Add runtime configuration validation ([#8989](https://github.com/DataDog/integrations-core/pull/8989))

## 1.11.4 / 2021-03-07 / Agent 7.27.0

***Fixed***:

* Bump minimum base package version ([#8443](https://github.com/DataDog/integrations-core/pull/8443))

## 1.11.3 / 2020-09-24 / Agent 7.23.0

***Fixed***:

* Add integration test for ssh keypair and make code more accurate ([#7655](https://github.com/DataDog/integrations-core/pull/7655))

## 1.11.2 / 2020-09-21

***Fixed***:

* pass the password to be used for pkey decryption ([#6862](https://github.com/DataDog/integrations-core/pull/6862))

## 1.11.1 / 2020-06-29 / Agent 7.21.0

***Fixed***:

* Add config specs ([#6923](https://github.com/DataDog/integrations-core/pull/6923))
* Agent6 style init ([#6924](https://github.com/DataDog/integrations-core/pull/6924))

## 1.11.0 / 2020-05-17 / Agent 7.20.0

***Added***:

* Allow optional dependency installation for all checks ([#6589](https://github.com/DataDog/integrations-core/pull/6589))

## 1.10.1 / 2020-04-04 / Agent 7.19.0

***Fixed***:

* Update deprecated imports ([#6088](https://github.com/DataDog/integrations-core/pull/6088))

## 1.10.0 / 2020-01-13 / Agent 7.17.0

***Added***:

* Use lazy logging format ([#5377](https://github.com/DataDog/integrations-core/pull/5377))
* Add version metadata ([#5016](https://github.com/DataDog/integrations-core/pull/5016))

## 1.9.0 / 2019-10-09 / Agent 6.15.0

***Added***:

* Upgrade Paramiko to version 2.6.0 ([#4685](https://github.com/DataDog/integrations-core/pull/4685)) Thanks [daniel-savo](https://github.com/daniel-savo).

## 1.8.0 / 2019-08-24 / Agent 6.14.0

***Added***:

* Upgrade pyasn1 ([#4289](https://github.com/DataDog/integrations-core/pull/4289))

***Fixed***:

* Remove unused dependencies ([#4405](https://github.com/DataDog/integrations-core/pull/4405))

## 1.7.0 / 2019-07-04 / Agent 6.13.0

***Added***:

* Update cryptography version ([#4000](https://github.com/DataDog/integrations-core/pull/4000))

## 1.6.0 / 2019-05-14 / Agent 6.12.0

***Added***:

* Adhere to code style ([#3569](https://github.com/DataDog/integrations-core/pull/3569))

## 1.5.0 / 2019-01-04 / Agent 6.9.0

***Added***:

* Support Python 3 ([#2836](https://github.com/DataDog/integrations-core/pull/2836))

## 1.4.0 / 2018-11-30 / Agent 6.8.0

***Added***:

* Upgrade cryptography ([#2659](https://github.com/DataDog/integrations-core/pull/2659))

## 1.3.1 / 2018-09-04 / Agent 6.5.0

***Fixed***:

* Update cryptography to 2.3 ([#1927](https://github.com/DataDog/integrations-core/pull/1927))
* Add data files to the wheel package ([#1727](https://github.com/DataDog/integrations-core/pull/1727))

## 1.3.0 / 2018-06-20 / Agent 6.4.0

***Changed***:

* Bump requests to 2.19.1 ([#1743](https://github.com/DataDog/integrations-core/pull/1743))

## 1.2.0 / 2018-03-23

***Added***:

* Add custom tag support.

## 1.1.3 / 2018-01-10

***Fixed***:

* Check that the private_key_file exists in the yaml configuration before attempting to access it ([#988](https://github)com/DataDog/integrations-core/issues/988)

## 1.1.2 / 2017-11-21

***Fixed***:

* If `ssh_check` passes and uses `None` as `exception_message`, downstream aggregator rejects it with a type error. Instead, specify a default message ([#852](https://github)com/DataDog/integrations-core/issues/852)

## 1.1.1 / 2017-08-28

***Added***:

* drop dependency on winrandom_ctypes for windows

## 1.1.0 / 2017-07-18

***Added***:

* Drop dependency on pycrypto ([#426](https://github.com/DataDog/integrations-core/issues/426) and [#454](https://github)com/DataDog/integrations-core/issues/454)

***Fixed***:

* Fix misplaced parentheses in config validation ([#416](https://github.com/DataDog/integrations-core/issues/416), thanks [@ilkka](https://github)com/ilkka)

## 1.0.0 / 2017-03-22

***Added***:

* adds ssh_check integration.

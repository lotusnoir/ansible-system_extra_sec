# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0](https://github.com/lotusnoir/ansible-system_extra_sec/compare/2.0.0...2.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`1304066`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/1304066fc9490e0c4137008d612e3b1d27dd2e74)
- update core and molecule [`c518bdd`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/c518bddc6dd0f2e881f9f911057201e75b239db4)
- add oraclelinux10 support + lint and core fixes [`99211cd`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/99211cd24afb3e15cda8b50e8eff9b747370b4d1)

## [2.0.0](https://github.com/lotusnoir/ansible-system_extra_sec/compare/1.1.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`3994729`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/3994729b541bfbc4f6611d2f9af61b957b2c44de)
- update core, molecule + gitlab-ci [`5644dd0`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/5644dd0fe98e7ad2b2300ccefd64bbd38b5e9d64)
- fix lint [`cc71547`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/cc71547065a86a4dbcbe08279e6b5d901438e2bc)
- fix molecule paralelism and little updates [`0789c13`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/0789c13d0cb47e4435d994048370f114dc805dee)

## [1.1.0](https://github.com/lotusnoir/ansible-system_extra_sec/compare/1.0.0...1.1.0) - 2025-01-17

### Commits

- add support for ubuntu24 [`e86bd60`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/e86bd60798c9f47416eba623365f202f375e69cb)
- fix rights for crontab [`4bb9619`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/4bb9619920c680b56adf285d954d530f3986f2e5)
- add version on molecule play image to maintain support on old release [`c0fb5eb`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/c0fb5ebc22e6833ddd6f8b0c906ee6459989f2d5)
- remove support for debian10 / ubuntu18 / redhat8 [`64e4c72`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/64e4c7273a7cdc79e5ab38fb00149999a7288f3c)
- update molecule [`b4173e5`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/b4173e50281a93e8855fb89edaefb62305c4019a)
- add redhat 9 to default supported distrib [`54dfef8`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/54dfef8982f7a346ca42ecc01a3b2ffd05dfdb2a)
- add redhat 8 to default supported distrib [`1b60556`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/1b60556bf9c0cc347fa50bdac5f1cf1f2a2d7da1)
- sort testing distrib to avoid random changes [`013260a`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/013260a846e7ff91308ed27c1610f3670cc1a896)
- update pre-commit and lint fix [`5a7332f`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/5a7332fdd843fdb2c63a27b8468ef7573eb05b58)
- add at.allow [`02d89fe`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/02d89fecd474d949d1335c37c76259e2fe54f509)

## [1.0.0](https://github.com/lotusnoir/ansible-system_extra_sec/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`3189e01`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/3189e01e73ed74045dc7013aa2c9f58e90380cd2)
- update readme + precommit + include vars [`e98f822`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/e98f8225b25540605b4bb4f155c7ab80f16d7aa1)
- change import tasks to include in order to support facts on name [`b309af5`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/b309af549c0e556e679b24a8721ec6dfb3254273)
- add umask change on /etc/init.d/rc [`ec19255`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/ec192552f287545103af21e2cc66b66b2c700865)
- Add conditions [`f9d5d19`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/f9d5d1964173d796c3fe54e283b2cfb3d5aa1a0d)
- fix issue and add feature [`22fa3b2`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/22fa3b2260e36715f91a1df28ec8dcae2709f74d)
- add log permission [`e918f9c`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/e918f9cde64ff51306ac9828c530662f673c92a6)

## [0.2.0](https://github.com/lotusnoir/ansible-system_extra_sec/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`6652377`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/665237756ccf166876ad1f16bd07eb589cc8b0b6)
- add galaxy id [`f65bdc2`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/f65bdc23bbe63f93dc64194bb76f76d3ee9c2411)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`2a0b18c`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/2a0b18c446fbf54e91689f5207bd212609d3fa57)
- add precommit for lint [`7d1a960`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/7d1a96058c468983e76cc916f12d1266680c78d7)
- fix checks [`0201b83`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/0201b83069361a6a72cdbe927456a8b7c9809bca)
- add new molecule all scenario [`614515c`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/614515caadcbe7f73e5fa865ab3d48380f7d2953)
- split distro for molecule tests on ci [`43b50a8`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/43b50a81265b3b4b18fedaed8c8287be95a17ae0)
- update checks and Readme [`7cf3d29`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/7cf3d29f7d9a9ab107835eaa83f6a2b94462b077)
- revert logrotate, manage by another module [`3a8227a`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/3a8227af8bbfd693aa44439e0e3a19fa1a3548c3)
- initial commit [`68839cd`](https://github.com/lotusnoir/ansible-system_extra_sec/commit/68839cddde00d4e7dea1292ee9e18ef27dd0866c)

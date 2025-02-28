# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0](https://github.com/lotusnoir/ansible-apps_salt_minion/compare/1.0.0...1.1.0) - 2024-11-14

### Commits

- fix missing folder [`80a0c92`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/80a0c92efdd9ee98db340bf4b2e20d969122239f)
- add version on molecule play image to maintain support on old release [`04c22f7`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/04c22f74fb04b124ab58938c8071e58789d499ce)
- remove support for debian10 / ubuntu18 / redhat8 [`8652f79`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/8652f793143e94c96eb2a2d98337066f4bf1e82d)
- update molecule [`01a205b`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/01a205b6b055c84a9d61bfdb43a4f421b8a7ca3c)
- add redhat 9 to default supported distrib [`0e70c02`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/0e70c0208faa2114da2c40cf874a9ce3afb7ecb2)
- add redhat 8 to default supported distrib [`c8c8a82`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/c8c8a822bf0338e83293d804a5c6eb91d19572cf)
- sort testing distrib to avoid random changes [`9c7e3f7`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/9c7e3f745047b393bce49fdee601504ae85be2cd)
- update pre-commit and lint fix [`18e0d68`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/18e0d688343b1ec957f125c5c19dfa901c5fc9f3)
- add variable for oner to support ubuntu18 [`8e4f647`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/8e4f647a879e77dccdc42ca213409dd68f22e242)
- remove support for rhel7 and docker dind on gitlab [`744dd0c`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/744dd0c4dced62736a9bb4cce55d55ab0cda006b)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_salt_minion/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`cf91615`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/cf916151df594f261454f2b6c592d0b948bf42c3)
- remove precommit gitlab [`ef9328d`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/ef9328d1691cb75da57fa0df327078e423a5c604)
- remove local file as its downloaded [`7bf3cfa`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/7bf3cfa0d5fca31bd9e739ef47d37a9f757464b6)
- change import tasks to include in order to support facts on name [`dda643b`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/dda643b1abe8d07fb078072c134510e5ba3de0f7)
- fix wrong mode for gpg key [`d2aa47f`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/d2aa47f433eb4a68ebea766e83786262c214062a)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_salt_minion/compare/0.1.0...0.2.0) - 2023-06-12

### Commits

- fix new distrib ora9 [`b268ecb`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/b268ecbcb95ae744a5df050bcd725ee611a5a527)
- add galaxy id [`4a98f49`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/4a98f49fb7e7317286f19815ea919ac8539ca500)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`9269adc`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/9269adc7ffaa4ba3618e9e4d6decf98e6f7e4515)
- add precommit for lint [`23c402d`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/23c402d98610d4c3d537ea5f7dab4e6ac3a78599)
- fix checks [`b4de9ce`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/b4de9cee40de17399ee22dfc0615936ed75b3b48)
- update default vars [`60056b5`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/60056b5f4bb349dba926958fb6977f4908a6fe97)
- split distro for molecule tests on ci [`d81760a`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/d81760a47296364343812af09b9d97a6b5a28103)
- remove verify [`54f12d3`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/54f12d3e71c5ceabc3963742df10c8d32ab32e1c)
- fix lint + update common files [`ae0def9`](https://github.com/lotusnoir/ansible-apps_salt_minion/commit/ae0def9954421e7a0e9861e8bd9dd7e905ecdcdc)

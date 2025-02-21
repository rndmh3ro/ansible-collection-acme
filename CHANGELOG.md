# Changelog

## [2.1.0](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/2.1.0) (2021-05-30)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/2.0.1...2.1.0)

**Breaking changes:**

- Rename collection | simplify provider selection | unify variables  [\#46](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/46) ([avalor1](https://github.com/avalor1))

**Implemented enhancements:**

- add hetzner dns tests [\#54](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/54) ([rndmh3ro](https://github.com/rndmh3ro))
- add possibility to keep and purge challenge record in Azure [\#52](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/52) ([michaelamattes](https://github.com/michaelamattes))

**Closed issues:**

- add possibility azure dns challenge purge entry [\#51](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/51)

## [2.0.1](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/2.0.1) (2021-05-18)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/2.0.0...2.0.1)

**Fixed bugs:**

- Lookup ZoneID and fix challenge record format. [\#53](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/53) ([smapjb](https://github.com/smapjb))

## [2.0.0](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/2.0.0) (2021-03-26)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/1.0.2...2.0.0)

**Breaking changes:**

- Unify variables [\#44](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/44)

**Closed issues:**

- Rename collection to avoid LE trademark [\#43](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/43)
- Simplify challenge provider selection [\#42](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/42)

**Merged pull requests:**

- Adjust collection name for galaxy [\#49](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/49) ([avalor1](https://github.com/avalor1))
- add possibility to define owner/group for local validation path and local challenge files [\#48](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/48) ([beechesII](https://github.com/beechesII))

## [1.0.2](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/1.0.2) (2021-03-17)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/1.0.1...1.0.2)

**Fixed bugs:**

- Improve Release Action [\#47](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/47) ([schurzi](https://github.com/schurzi))

## [1.0.1](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/1.0.1) (2021-02-05)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/1.0.0...1.0.1)

**Merged pull requests:**

- Add README.md link in role [\#41](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/41) ([avalor1](https://github.com/avalor1))

## [1.0.0](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/1.0.0) (2021-02-05)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.1.0...1.0.0)

**Implemented enhancements:**

- unify challenge provider logic [\#35](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/35) ([schurzi](https://github.com/schurzi))
- Account key content as variable [\#33](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/33) ([Nemental](https://github.com/Nemental))
- Add "local" provider for http-challenge [\#30](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/30) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- Documentation restructuring [\#32](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/32)

**Merged pull requests:**

- Release 1.0 [\#40](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/40) ([avalor1](https://github.com/avalor1))
- use more labels for version-generation [\#39](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/39) ([rndmh3ro](https://github.com/rndmh3ro))
- Documentation restructuring [\#37](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/37) ([avalor1](https://github.com/avalor1))
- use ternary to simplify tasks for directory usage, remove comments [\#36](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/36) ([rndmh3ro](https://github.com/rndmh3ro))
- use version for github action, short sha is no longer supported [\#34](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/34) ([schurzi](https://github.com/schurzi))

## [0.1.0](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.1.0) (2021-01-25)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.8...0.1.0)

**Implemented enhancements:**

- Feature / dns challenge otc openstack [\#31](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/31) ([Nemental](https://github.com/Nemental))

**Merged pull requests:**

- update documentation [\#28](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/28) ([avalor1](https://github.com/avalor1))

## [0.0.8](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.8) (2021-01-11)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.7...0.0.8)

**Closed issues:**

- Integration Tests for role [\#3](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/3)

**Merged pull requests:**

- fix galaxy-release action [\#29](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/29) ([rndmh3ro](https://github.com/rndmh3ro))
- adjust variable naming in example files and readme [\#27](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/27) ([avalor1](https://github.com/avalor1))
- Create runtime.yml [\#26](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/26) ([rndmh3ro](https://github.com/rndmh3ro))
- Create LICENSE [\#25](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/25) ([rndmh3ro](https://github.com/rndmh3ro))
- run tests on a schedule [\#24](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/24) ([rndmh3ro](https://github.com/rndmh3ro))
- build integration tests [\#23](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/23) ([rndmh3ro](https://github.com/rndmh3ro))

## [0.0.7](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.7) (2020-12-15)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.6...0.0.7)

**Fixed bugs:**

- fix broken AutoDNS wildcard creation \#20 [\#21](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/21) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- creation of wildcard certificates with autodns challenge not working with release 0.0.5 [\#20](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/20)

**Merged pull requests:**

- remove common\_name variable [\#18](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/18) ([avalor1](https://github.com/avalor1))

## [0.0.6](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.6) (2020-12-15)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.5...0.0.6)

**Implemented enhancements:**

- Add Hetzner DNS as letsencrypt\_dns\_provider [\#22](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/22) ([xobtoor](https://github.com/xobtoor))

## [0.0.5](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.5) (2020-12-09)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.4...0.0.5)

**Implemented enhancements:**

- Push to Galaxy Fails [\#13](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/13)
- add second checkout to solve race condition \(version gets updated but… [\#15](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/15) ([avalor1](https://github.com/avalor1))

**Closed issues:**

- subject\_alt\_name not optional [\#9](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/9)

**Merged pull requests:**

- fix ansible error if group is empty [\#19](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/19) ([avalor1](https://github.com/avalor1))
- remove letsencrypt\_create\_private\_keys variable from examples [\#17](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/17) ([avalor1](https://github.com/avalor1))
- remove variable letsencrypt\_create\_private\_keys [\#7](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/7) ([avalor1](https://github.com/avalor1))

## [0.0.4](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.4) (2020-11-12)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.3...0.0.4)

**Implemented enhancements:**

- add description of force\_renewal variable [\#12](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/12) ([avalor1](https://github.com/avalor1))

**Merged pull requests:**

- update checkout version for release workflow [\#11](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/11) ([avalor1](https://github.com/avalor1))
- update checkout version in galaxy push workflow [\#10](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/10) ([avalor1](https://github.com/avalor1))

## [0.0.3](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.3) (2020-11-12)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.2...0.0.3)

**Closed issues:**

- Remove unwanted files from release-tarball  [\#4](https://github.com/T-Systems-MMS/ansible-collection-acme/issues/4)

**Merged pull requests:**

- Add Azure dns provider challenge [\#8](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/8) ([michaelamattes](https://github.com/michaelamattes))

## [0.0.2](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.2) (2020-11-06)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/0.0.1...0.0.2)

**Merged pull requests:**

- add build\_ignore to filter unwanted files from release-tarball [\#6](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/6) ([avalor1](https://github.com/avalor1))

## [0.0.1](https://github.com/T-Systems-MMS/ansible-collection-acme/tree/0.0.1) (2020-11-04)

[Full Changelog](https://github.com/T-Systems-MMS/ansible-collection-acme/compare/6c0445f6769360d1b8ea12df58483ac4a8b602f3...0.0.1)

**Merged pull requests:**

- Workflows [\#2](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/2) ([avalor1](https://github.com/avalor1))
- add Workflows [\#1](https://github.com/T-Systems-MMS/ansible-collection-acme/pull/1) ([avalor1](https://github.com/avalor1))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*

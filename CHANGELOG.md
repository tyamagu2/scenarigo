# CHANGELOG

<a name="v0.3.3"></a>
## [v0.3.3] - 2020-06-17
### Bug Fixes
- **core:** add generated files to avoid the import error ([#41](https://github.com/zoncoen/scenarigo/issues/41))
- **deps:** update YAML library ( v1.7.12 => v1.7.15 ) ([#47](https://github.com/zoncoen/scenarigo/issues/47))
- **deps:** update YAML library ( v1.7.10 => v1.7.11 ) ([#42](https://github.com/zoncoen/scenarigo/issues/42))
- **deps:** update YAML library to fix a bug ( v1.7.9 => v1.7.10 ) ([#40](https://github.com/zoncoen/scenarigo/issues/40))
- **template:** fix processing for variadic arguments of function ([#48](https://github.com/zoncoen/scenarigo/issues/48))

<a name="v0.3.2"></a>
## [v0.3.2] - 2020-06-15
### Bug Fixes
- **deps:** update YAML library to fix a bug ( v1.7.8 => v1.7.9 ) ([#39](https://github.com/zoncoen/scenarigo/issues/39))

<a name="v0.3.1"></a>
## [v0.3.1] - 2020-06-12
### Bug Fixes
- **core:** fix ctx.Response() for http protocol ([#35](https://github.com/zoncoen/scenarigo/issues/35))
- **errors:** fix incorrect line number in YAML source ([#38](https://github.com/zoncoen/scenarigo/issues/38))

<a name="v0.3.0"></a>
## [v0.3.0] - 2020-06-11
### Features
- **core:** support to output error with YAML ([#33](https://github.com/zoncoen/scenarigo/issues/33))

<a name="v0.2.0"></a>
## [v0.2.0] - 2020-06-03
### Code Refactoring
- **core:** replace YAML libraries to goccy/go-yaml ([#31](https://github.com/zoncoen/scenarigo/issues/31))

### Features
- **core:** read YAML files only as scenarios ([#28](https://github.com/zoncoen/scenarigo/issues/28))
- **grpc:** enable to check header/trailer metadata of gRPC response ([#29](https://github.com/zoncoen/scenarigo/issues/29))
- **http:** enable to check HTTP response headers ([#30](https://github.com/zoncoen/scenarigo/issues/30))

### BREAKING CHANGE

change protocl.Protocol interface

<a name="v0.1.0"></a>
## v0.1.0 - 2020-05-17
- first release


[v0.3.3]: https://github.com/zoncoen/scenarigo/compare/v0.3.2...v0.3.3
[v0.3.2]: https://github.com/zoncoen/scenarigo/compare/v0.3.1...v0.3.2
[v0.3.1]: https://github.com/zoncoen/scenarigo/compare/v0.3.0...v0.3.1
[v0.3.0]: https://github.com/zoncoen/scenarigo/compare/v0.2.0...v0.3.0
[v0.2.0]: https://github.com/zoncoen/scenarigo/compare/v0.1.0...v0.2.0

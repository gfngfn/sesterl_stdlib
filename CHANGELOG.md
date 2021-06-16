# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- Fix `RawMap.map`.

### Added
- Add `RawMap.{from_list,merge_with,fold}`.

## [0.1.2]
- Add `Binary.from_int`.
- Add `List.foldl_effect`.
- Conforms to the new representation of `option<$a>`-typed values (by atoms `ok` and `error`).
- Change type `name` to `name<$a>`.
- Introduce `stop_reason` and `global` to `GenServer.Behaviour`.
- Rename `GenServer.init_fail` to `GenServer.init_stop`.
- Add type `GenServer.start_link_error`.
- Rename `GenServer.Make(Callback).where_is` to `GenServer.Make(Callback).where_is_local`.
- Add `GenServer.Make(Callback).where_is_global`.

## [0.1.1]


  [Unreleased]: https://github.com/gfngfn/sesterl_stdlib/compare/v0.1.2...HEAD
  [0.1.2]: https://github.com/gfngfn/sesterl_stdlib/compare/v0.1.1...v0.1.2
  [0.1.1]: https://github.com/gfngfn/sesterl_stdlib/compare/v0.1.0...v0.1.1

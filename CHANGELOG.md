# RobotlegsJS EventEmitter3 Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

<!--
Types of changes:

#### Added
- for new features.

#### Changed
- for changes in existing functionality.

#### Deprecated
- for soon-to-be removed features.

#### Removed
- for now removed features.

#### Fixed
- for any bug fixes.

#### Security
- in case of vulnerabilities.
-->

## Robotlegs-EventEmitter3 2.0.0

### [v2.0.0](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3/releases/tag/2.0.0) - 2020-03-03

#### Breaking Change

- Update [`@robotlegsjs/core`](https://github.com/RobotlegsJS/RobotlegsJS) to version `^2.0.0` (see #50).

  - Migrate array notation from `Array<SomeType>` to `SomeType[]`.

  - The rest of the `Public API` remains unchanged.

#### Added

- Add **Tidelift** as funding option (see #46).

- Add **Enterprise Support** information (see #47).

#### Changed

- Update `tslib` to version `1.11.1` (see #49).

- Update dev dependencies to latest version.

#### Security

- Migrate to [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) to solve security vulnerability (see #45).

## Robotlegs-EventEmitter3 1.0.0

### [v1.0.2](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3/releases/tag/1.0.2) - 2019-10-24

#### Changed

- Update `@robotlegsjs/core` to version `1.0.3` (see #37).

- Update `instanbul` settings (see #36).

- Migrate project to `travis-ci.com`.

- Update `codebeat` Project UUID.

- Update dev dependencies to latest version.

### [v1.0.1](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3/releases/tag/1.0.1) - 2019-03-21

#### Changed

- Update [`@robotlegsjs/core`](https://github.com/RobotlegsJS/RobotlegsJS) to version `1.0.1` (see #23).

- Improve `prettier` rules and `autoformat` script (see #22).

- Enable `"editor.formatOnSave"` rule for `VS Code` (see #22).

- Update dev dependencies to latest version.

### [v1.0.0](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3/releases/tag/1.0.0) - 2018-11-25

#### Changed

- Update `@robotlegsjs/core` to version `1.0.0` (see #14).

- Enable `greenkeeper` (see #2).

- Migrate to Headless Chrome and improve performance of `karma` (see #10).

- Prepare package for stable version (see #11).

- Update GitHub Templates (see #13).

- Update dev dependencies to latest version.

## Robotlegs-EventEmitter3 0.0.1

### [v0.0.1](https://github.com/RobotlegsJS/RobotlegsJS-EventEmitter3/releases/tag/0.0.1) - 2018-09-14

- Extends `IEventMap` to support `EventEmitter3` events (see #1).

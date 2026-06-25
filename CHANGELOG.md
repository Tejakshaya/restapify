# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### ✨ Added
- update faker's language locale

### 🐛 Fixed
- API reponds with an error message and status 500 if it's impossible to cast a variable 
- API is updated when a route file is deleted
- migrate from deprecated `faker` package to `@faker-js/faker` (#89)
- add timestamp to CLI "API updated" log message (#91)

## [2.3.0] - 2021-08-03
### ✨ Added
- support object notation in for-loop array sequence (thanks to [@flippingflapping](https://github.com/flippingflapping))

## [2.2.0] - 2021-07-30
### ✨ Added
- handle nested for-loop
- use dashboard v1.3.3

### 🐛 Fixed
- support windows OS

### 🔥 Removed
- possibility to define multiple states for the same route

## [2.1.5] - 2021-06-22
### 🐛 Fixed
- show error message in CLI when invalid fakerjs syntax is detected

## [2.1.0] - 2021-06-18
### ✨ Added
- handle javascript config file


## [1.0.2] - 2021-03-17
### 🐛 Fixed
- crash if presence of non json file in mocked API folder

## [1.0.1] - 2021-03-15
### 🐛 Fixed
- CLI crash on invalid configuration file path


[Unreleased]: ./compare/v2.3.0...HEAD
[2.3.0]: ./releases/tag/v2.3.0
[2.2.0]: ./releases/tag/v2.2.0
[2.1.5]: ./releases/tag/v2.1.5
[2.1.0]: ./releases/tag/v2.1.0
[1.0.2]: ./releases/tag/v1.0.2
[1.0.1]: ./releases/tag/v1.0.1

# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

## 2.1.0 (2024-10-15)

#### 🎁 Feature

* add prompts for os & arch (c47987b3)

#### 🚧 Chores

* **deps:** bump github.com/schollz/progressbar/v3 (#8) (e118eaac)
* update workflow step (e37f10f7)

#### 🔁 CI

* bump sigstore/cosign-installer in the github-actions group (#9) (27563541)
* bump codecov/codecov-action in the github-actions group (#7) (89618ab4)

## 2.0.3 (2024-10-01)

#### 🐞 Bug Fixes

* update import paths for the Go code (49eb11f0)

#### 🔁 CI

* update index pkg.go.dev step (4857baec)

## 2.0.2 (2024-10-01)

#### 🐞 Bug Fixes

* update downloader code to correctly compile the filename (becbc2dc)

#### 📄 Documentation

* update readme (1d918457)

#### 🔎 Tests

* debug extracted tags & cleanup (ce8526b7)
* err check (eee63198)

#### 🔀 Code Refactoring

* add service.go (311148ad)

#### 🚧 Chores

* **deps:** bump github.com/schollz/progressbar/v3 (#6) (e7cd015a)
* **deps:** bump github.com/stretchr/testify from 1.5.1 to 1.9.0 (#5) (f5b5f3b9)

#### 🔁 CI

* fix credentials usage (b7f4ecfd)
* Update docker.yml (986e999c)
* update metadata tags (535f013a)
* update docker metadata tags (6b256d12)

## What's Changed
* **Update module path to v2 and fix import statements for v2.0.2**

## 2.0.1 (2024-09-19)

#### 🐞 Bug Fixes

* correct the unit tests code (203b7b7d)

## What's Changed
* **Update module path to v2 and fix import statements for v2.0.1**

## 2.0.0 (2024-09-19)

#### 📣 Breaking Changes

* update code with interfaces (168bda7c)
```
test: add unittests for main.go
refactor: refactor all code as per interfaces implementation
ci: update package release
build: update go.mod
docs: update readme

BREAKING CHANGE: Interfaces Implementation and now prompt for download with path
```

#### 📄 Documentation

* add security policy & PR template (e60659b7)
* update changelog (2c4913d6)

#### 🔀 Code Refactoring

* fix lint issues for unittests (fd6183f6)

#### 🚧 Chores

* **deps:** bump github.com/schollz/progressbar/v3 (#4) (0dc10f57)

#### 🔁 CI

* bump golangci/golangci-lint-action in the github-actions group (#3) (e29d363f)
* add cosign image step (9de12705)
* update tags (54772870)
* fix workflows (efeb78b0)
* update docker.yml to use GH App token (910d9150)
* Add docker CI (4c81a0c2)
* update codeql for go (ad7cdb2b)
* Create codeql.yml (7682fcf1)

## What's Changed
* **Update module path to v2 and fix import statements for v2.0.0**
* ci: bump golangci/golangci-lint-action from 3 to 6 in the github-actions group by @dependabot in https://github.com/Nicconike/AutomatedGo/pull/3
* chore(deps): bump github.com/schollz/progressbar/v3 from 3.14.6 to 3.15.0 by @dependabot in https://github.com/Nicconike/AutomatedGo/pull/4


**Full Changelog**: https://github.com/Nicconike/AutomatedGo/compare/v1.2.0...v2.0.0


## 1.2.0 (2024-09-12)

#### 🎁 Feature

* Prompt user to download (556a1e58)

#### 📄 Documentation

* update issue templates (b195484e)
* update doc.go (9c3516f7)
* update readme (0cd6d5a9)
* update readme (8e7a9882)

#### 🔎 Tests

* 100% codecov (c8f457bf)
* Improve codecov for downloader.go (576916c9)
* 100% codecov for checksum.go (4b96091b)
* Improve codecov for checksum.go (f6578654)

#### 🚧 Chores

* Update name to AutomatedGo (a45ed383)
* **deps:** bump github.com/schollz/progressbar/v3 (#2) (e582dc62)
* update .goreleaser.yml (cb0a5e64)

#### 🔁 CI

* update release.yml (89bd3d4a)
* update incorrect path (90d938d0)
* update release workflow (a33cd70b)
* fix pkg.go.dev step (94880923)


## v1.1.0 (2024-07-16)

#### 🎁 Feature

* Add checksum verification (5884a154)

#### 🔁 CI

* run goreleaser only if new release (9485e929)
* use v2 for goreleaser action (7b8a72c3)
* use v6 for goreleaser (25591d36)
* update release workflow (88c916ab)
* update release workflow (4d6686b1)


## v1.0.6 (2024-07-08)

#### 🐞 Bug Fixes

* Use goreleaser for publishing (8fa9fc1c)

#### 📄 Documentation

* update readme (a0e882be)
* update readme (f0707053)

#### 🚧 Chores

* **deps:** bump codecov/codecov-action from 4.0.1 to 4.5.0 (#1) (4ec78448)


## v1.0.5 (2024-07-08)

#### 🐞 Bug Fixes

* Remove sem-rel config (ad86fbb0)

#### 🔁 CI

* update workflow (0bacbbeb)


## v1.0.4 (2024-07-08)

#### 🐞 Bug Fixes

* Min req set to go1.15 (6122c5d1)

#### 📄 Documentation

* Add issue templates (5ea945cb)

#### 🔎 Tests

* Add codecov for downloader.go (c86aa3b7)

#### 🔁 CI

* correct publish step (9ee10fd2)
* Improved codecov for pkg (f08e6459)


## v1.0.3 (2024-07-06)

#### Bug Fixes

* correct regex patterns in config.go (28235f5d)

#### CI

* fix codecov workflow (f3e43a26)
* update codecov workflow (5a1453a8)
* update codecov (c9325dcc)


## v1.0.2 (2024-07-06)

#### Bug Fixes

* update main script and pkg (ba5c3c8f)

#### Chores

* update sem-rel (d0b7a490)


## v1.0.1 (2024-07-05)

#### Bug Fixes

* sem release plugin (27280f95)


## v1.0.0 (2024-07-05)

#### Chores

* Add code for goautomate (da3146c3)

#### CI

* Update release workflow (5e897b15)

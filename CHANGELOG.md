# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.5...HEAD)

## [2.7.5](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.4...2.7.5) - 2021-03-24

### Changed

-   Collapse multiple check runs of same name. [d647f37](https://github.com/atomist-skills/github-notifications-skill/commit/d647f37ffe4ee0f42972cb3a095c4c04789e8599)
-   Make hide marker regular expression non-greedy. [23da846](https://github.com/atomist-skills/github-notifications-skill/commit/23da84601b2fa08b30135c7b4e36d28339eca50e)

## [2.7.4](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.3...2.7.4) - 2021-03-15

### Added

-   Allow for surpression of certain commits. [d4cedb9](https://github.com/atomist-skills/github-notifications-skill/commit/d4cedb9045f9434698fd4b2da92cfaf3fb9dcb2c)
-   Update lifecycle pack. [4d5c187](https://github.com/atomist-skills/github-notifications-skill/commit/4d5c187144f6185ca6d2b19d61ad5bfebb7c7e95)

## [2.7.3](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.2...2.7.3) - 2020-12-02

### Changed

-   Sort checks by state and name. [2434be2](https://github.com/atomist-skills/github-notifications-skill/commit/2434be2084c0d5704fcb4a70cdedaae3c63133f6)

## [2.7.2](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.1...2.7.2) - 2020-12-02

### Changed

-   Sort checks by creation time. [6d566ec](https://github.com/atomist-skills/github-notifications-skill/commit/6d566ec90172bf4290333c3904fc10d63f5bfdeb)

## [2.7.1](https://github.com/atomist-skills/github-notifications-skill/compare/2.7.0...2.7.1) - 2020-12-02

### Changed

-   Link to latest check instead of first from footer. [af24f3a](https://github.com/atomist-skills/github-notifications-skill/commit/af24f3a96f37a976d0ae406bbcb77203b251df2b)

## [2.7.0](https://github.com/atomist-skills/github-notifications-skill/compare/2.6.0...2.7.0) - 2020-12-02

### Added

-   Show compact check state in commit footer. [43c67d8](https://github.com/atomist-skills/github-notifications-skill/commit/43c67d85352b218fabdce85d42ac370b9013a197)
-   Add link to check footer. [8c4dcc7](https://github.com/atomist-skills/github-notifications-skill/commit/8c4dcc7910aa9345c0a37a12550863e2df014e0b)

## [2.6.0](https://github.com/atomist-skills/github-notifications-skill/compare/2.5.0...2.6.0) - 2020-11-24

### Added

-   Add repo filter to skill. [#75](https://github.com/atomist-skills/github-notifications-skill/issues/75)
-   Add default channel to skill configuration. [#76](https://github.com/atomist-skills/github-notifications-skill/issues/76)
-   Add config to filter out activity by certain GitHub users. [#77](https://github.com/atomist-skills/github-notifications-skill/issues/77)
-   Add icons for missing GitHub checks states. [#71](https://github.com/atomist-skills/github-notifications-skill/issues/71)
-   Auto-expand push lifecycle on failed check runs. [#72](https://github.com/atomist-skills/github-notifications-skill/issues/72)

### Removed

-   Remove maxConfigurations. [b191f76](https://github.com/atomist-skills/github-notifications-skill/commit/b191f764f5717d2ece96cedab7e889ad9b40054e)

## [2.5.0](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.11...2.5.0) - 2020-11-18

### Changed

-   Update skill icon. [b33fb46](https://github.com/atomist-skills/github-notifications-skill/commit/b33fb465802096244fe450cc287042233555b787)

## [2.4.11](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.10...2.4.11) - 2020-08-25

### Fixed

-   Remove reference to emoji examples in notifications configuration option for emoji. [#27](https://github.com/atomist-skills/github-notifications-skill/issues/27)

## [2.4.10](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.9...2.4.10) - 2020-07-28

### Changed

-   Update category. [#18](https://github.com/atomist-skills/github-notifications-skill/issues/18)

## [2.4.9](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.8...2.4.9) - 2020-07-16

### Added

-   Remove markdown comments in PR and issue bodies. [153f5c7](https://github.com/atomist-skills/github-notifications-skill/commit/153f5c7481b9c9dfc31e52f64ef5678168195a2a)

### Fixed

-   Better removal of details in markdown. [44be60f](https://github.com/atomist-skills/github-notifications-skill/commit/44be60f5c760a484de056b9e7f0590945a5c8262)

## [2.4.8](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.7...2.4.8) - 2020-07-15

### Fixed

-   Remove anchor links from markdown. [51d57dc](https://github.com/atomist-skills/github-notifications-skill/commit/51d57dc1412f328299f0d65aac9ae910128d5324)

## [2.4.7](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.6...2.4.7) - 2020-07-10

### Added

-   Render branch deletion with PR. [a2f399b](https://github.com/atomist-skills/github-notifications-skill/commit/a2f399b5b8cd146d93c8a1a849ae97d61cb0bed4)

## [2.4.6](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.5...2.4.6) - 2020-07-02

## [2.4.5](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.2...2.4.5) - 2020-07-02

### Changed

-   Should not be Slack-only. [#12](https://github.com/atomist-skills/github-notifications-skill/issues/12)
-   Edits to Chat wording. [#13](https://github.com/atomist-skills/github-notifications-skill/issues/13)
-   Update description. [084ac59](https://github.com/atomist-skills/github-notifications-skill/commit/084ac59313505f433a36aa9207854d8c4a57dd40)
-   Use new skill packaging. [70b80c2](https://github.com/atomist-skills/github-notifications-skill/commit/70b80c2110be69d89959fc171688bd59c9b23206)

## [2.4.2](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.1...2.4.2) - 2020-06-11

## [2.4.1](https://github.com/atomist-skills/github-notifications-skill/compare/2.4.0...2.4.1) - 2020-06-09

## [2.4.0](https://github.com/atomist-skills/github-notifications-skill/compare/2.3.4...2.4.0) - 2020-05-18

### Added

-   Add GitHub checks support to push and pull request notifications. [#10](https://github.com/atomist-skills/github-notifications-skill/issues/10)

## [2.3.4](https://github.com/atomist-skills/github-notifications-skill/compare/2.3.3...2.3.4) - 2020-05-13

## [2.3.3](https://github.com/atomist-skills/github-notifications-skill/compare/2.3.2...2.3.3) - 2020-05-06

## [2.3.2](https://github.com/atomist-skills/github-notifications-skill/compare/2.3.1...2.3.2) - 2020-05-06

### Changed

-   Update lifecycle packs. [1b7f128](https://github.com/atomist-skills/github-notifications-skill/commit/1b7f1286e6dce56d4e036a650e9a73d15a774a30)

## [2.3.1](https://github.com/atomist-skills/github-notifications-skill/compare/2.3.0...2.3.1) - 2020-05-01

## [2.3.0](https://github.com/atomist-skills/github-notifications-skill/compare/2.2.5...2.3.0) - 2020-05-01

### Fixed

-   Force only a single configuration of this skill. [#3](https://github.com/atomist-skills/github-notifications-skill/issues/3)

## [2.2.5](https://github.com/atomist-skills/github-notifications-skill/compare/2.2.4...2.2.5) - 2020-04-03

## [2.2.4](https://github.com/atomist-skills/github-notifications-skill/compare/2.2.3...2.2.4) - 2020-04-01

## [2.2.3](https://github.com/atomist-skills/github-notifications-skill/tree/2.2.3) - 2020-03-30

### Fixed

-   Fix issue with GitHub auth redirect link. [a3164d8](https://github.com/atomist-skills/github-notifications-skill/commit/a3164d886b99da08a5f4836d8a775040b4c1a370)

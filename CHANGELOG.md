# Changelog


## [3.0.0] - 2022-12-13
### Added
- docker-compose for testing [#37](https://github.com/easyredmine/redmine-installer/pull/37)
- .github workflow for CI
- `env_check` for test server environment
### Fixed
- ruby 3.x support [#35](https://github.com/easyredmine/redmine-installer/pull/35)
- Psych aliases while parsing `database.yml`
### Changed
- required ruby version = 3.1.2 [#36](https://github.com/easyredmine/redmine-installer/pull/36)
- required redmine version = 5.0.4+ [#36](https://github.com/easyredmine/redmine-installer/pull/36)

## [2.4.0] - 2022-09-07
### Added
- allow the administrator to manually empty the root directory [#33](https://github.com/easyredmine/redmine-installer/pull/33)

## [2.3.0.beta] - 2019-06-10

### Added
- Gems are required via Bundler
- Easycheck for server requirenments
- Validation for the package for upgrading

### Changed
- Gemfile was renamed to gems.rb
- Installer is now asking if user wants to copy missing plugins
- Tests aren't using system redmine-installer

### Deprecated
- Ruby <= 2.3

### Removed

### Fixed

### Security


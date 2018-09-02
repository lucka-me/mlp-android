<div align=center><a href="https://github.com/lucka-me/MLP-android"><img src="./Resource/Banner.svg" alt="Banner"></a></div>

<h1 align=center>Changelog</h1>

```markdown
## [0.2] - 2018-09-02
- 0.1.4(115) -> 0.2(144)
- New data structure

### Added
- New attributes for MockTarget:
  - Title (UI and methods updated)
  - Inteval, accuracy and altitude (UI and methods not updated yet)
- Save / load data with the new DataKit and Gson

### Changed
- MockTarget is a data class now, the old data could NOT be migrated
```

```markdown
## [0.1.4] - 2018-09-02
- 0.1.2(62) -> 0.1.4(115)
- New feature: Preference, enable/disable providers

### Added
- Preference screen
- Enable and disable providers from receiving mock locations

### Changed
- App icon improved. Since the Assest Studio seems to not support some features
  of SVG, the icon is generated manually. Looking for a better way.
- Switch compileSdkVersion and targetSdkVersion to 27 temporarily for some
  unresolved issues
```

```markdown
## [0.1.2] - 2018-09-02
- 0.1.1(54) -> 0.1.2(62)
- New function: Detect Enable mock location option and alert

### Added
- Detect if the Enable mock location option turned on before starting service
- Alert if the option is off

### Changed
- Code documented
```

```markdown
## [0.1.1] - 2018-08-31
- 0.1(33) -> 0.1.1(54)
- Bug fixed

### Added
- Push notification when exception encountered
- Get service state by a better but not best way, with a method that deprecated
  but still working

### Changed
- All string resources are in English now

### Fixed
- Service won't update mock location if the last target is disabled
```

```markdown
## [0.1] - 2018-08-30
- 0.1(33)
- Initial version
```
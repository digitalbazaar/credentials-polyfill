# credentials-polyfill ChangeLog

## 1.1.6 - 2017-06-23

### Fixed
- Fix IdentityCredential prototype.

## 1.1.5 - 2017-05-31

### Changed
- Add package.json file.

## 1.1.4 - 2017-04-17

### Fixed
- Remove window focus channel abort feature.

## 1.1.3 - 2017-04-17

### Fixed
- Always attempt channel abort on context closing; MS Edge
  cannot read `context.handle.closed` which should be
  true when called regardless.

## 1.1.2 - 2017-04-14

### Fixed
- Catch errors if backdrop CSS is unsupported.

## 1.1.1 - 2017-04-10

### Fixed
- Fix for legacy `register` API.

## 1.1.0 - 2017-04-05

### Added
- Add `requestPermission` to API.
- Use `respondWith` for polyfill events; expose IdentityCredentialRegistration.

## 1.0.1 - 2017-02-26

### Fixed
- Fix dialog polyfilling, opening, and canceling bugs.

## 1.0.0 - 2017-02-22

### Changed
- Use iframe by default and simplify dialog.

## 0.10.1 - 2016-12-12

### Added
- Add `enableRegistration` flag.
- Allow error text to be passed through channel.

## 0.10.0 - 2016-07-21

### Added
- **BREAKING**: Add experimental support for IE11. This change requires
  dropping backwards compatibility support that was in version 0.8.x. IE11
  is supported via use of an iframe, as IE11 does not support using
  postMessage with cross-domain windows.

- See git history for changes.

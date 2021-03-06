# Changelog

## 1.0.2 - 2021-01-18
### Added
- Refactor the reports task to make it more testable
- Add Github issue templates
- Add the NONE and CRITICAL CVSSv3 filters
- Add Python 3.8 in setup.py classifiers
- Add favicon.ico in website root

### Fixed
- Redirect subscribe links to the login page for unauthenticated users
- Fix wrong links for CWE definitions
- Handle exception in case of bad SMTP configuration
- Fix user creation/edition in administration panel
- Make Cwe.cwe_id field not nullable
- Clean CVSSv2 and CVSSv3 fields for rejected CVEs

## 1.0.1 - 2021-01-03
### Added
- Add an admin link in the user menu
- Display the is_confirmed field in users list
- Use click prompt to ask the user password

### Fixed
- Add missing javascript files
- Display the resend confirmation link in flash message
- Add email validator in profile form
- Click on search button submits the request
- Display the excerpt list of vendors and products in CVEs listing

## 1.0.0 - 2020-12-28
### Added
- Initial release.

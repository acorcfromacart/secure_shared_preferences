## 0.0.1
Initial release.

## 0.0.1-beta.01
Documentation updated

## 0.0.2
Flow chart added for better understanding of flow.

## 0.0.3
clearAll() method added to remove all preferences.

## 0.0.4
***** Breaking change ***** :
isEncrypted parameter is made option, default value will false.
What you need to do :
make second parameter of all put/get method as isEncrypted = false OR isEncrypted = true.
You can opt out default will be false.

## 0.0.5
***** Compatibility Update ***** :
- Updated to support Flutter 3.0+ and Dart 3.0+
- Replaced deprecated `package_info` with `package_info_plus`
- Updated `flutter_secure_storage` to version 9.2.4
- Updated `flutter_lints` to version 6.0.0
- Updated `shared_preferences` to version 2.5.3
- Updated `cryptography` to version 2.7.0
- Fixed lint issues and warnings
- Fixed code formatting and style issues
- Removed unnecessary print statements (replaced with comments)
- Fixed test initialization issues
- Updated example project to be compatible with latest Flutter

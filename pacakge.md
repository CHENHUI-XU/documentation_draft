# How to Publish Package

1. determine if it is a plugin (uses native code) or a general package
2. call  `flutter create --template=package hello`
3. implement the package
4. go to the root of folder, add the example that uses the package. (change the pubspec.yml)
5. add readme.md, changelog.md, LICENSE
6. API documentation is automatically generated when publish, nothing needs to be done
7. test the package `flutter pub publish --dry-run`
8. publish the `package flutter pub publish`
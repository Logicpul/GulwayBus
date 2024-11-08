# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android test

```sh
[bundle exec] fastlane android test
```

Runs all the tests

### android deployAlpha

```sh
[bundle exec] fastlane android deployAlpha
```

Deploy app to play store alpha channel

### android deployInternalTest

```sh
[bundle exec] fastlane android deployInternalTest
```



### android buildApp

```sh
[bundle exec] fastlane android buildApp
```



### android buildAppApk

```sh
[bundle exec] fastlane android buildAppApk
```



### android promoteAppToProd

```sh
[bundle exec] fastlane android promoteAppToProd
```

Promote app from alpha to production in Play Store

### android screenshots

```sh
[bundle exec] fastlane android screenshots
```

Generate app screenshots that will be uploaded to play store

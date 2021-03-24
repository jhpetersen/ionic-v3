# Ionic

## Ionic v3 fork with patches

### iPad platform detection
Since iOS 13 there is a change in user agent of iPad devices (see https://github.com/ionic-team/cordova-plugin-ionic-webview/issues/556#issuecomment-708282656) which causes wrong cordova platform information (see bug report https://github.com/ionic-team/ionic-v3/issues/1104).
This bug was fixed in Ionic >=4 but not for v3, so user osben already ported the fix in two patches (see https://github.com/osben/ionic-v3/commits/patch-1 and https://github.com/osben/ionic-v3/commits/patch-2), which are integrated hereby based on Ionic v3.9.10.

## Original description

[Ionic](https://ionicframework.com/) is the open-source mobile app development framework that makes it easy to
build top quality native and progressive web apps with web technologies.

Ionic is based on [Angular](https://angular.io/) and comes with many significant performance, usability, and
feature improvements over the past versions.

See the [Building Apps with Ionic](https://adamdbradley.github.io/building-with-ionic2) slides for a quick
overview or watch our [Crash Course](https://youtu.be/O2WiI9QrS5s) video for a quick walkthrough on how to get
started using Ionic.

### Getting Started

Start a new project by following our quick [Getting Started guide](https://ionicframework.com/getting-started/).
We would love to hear from you! If you have any feedback or run into issues using our framework, please file
an [issue](https://github.com/ionic-team/ionic-v3/issues/new) on this repository.

### Contributing

Thanks for your interest in contributing! Read up on our guidelines for
[contributing](https://github.com/ionic-team/ionic-v3/blob/master/.github/CONTRIBUTING.md)
and then look through our issues with a [help wanted](https://github.com/ionic-team/ionic-v3/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)
label.

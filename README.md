# Cordova Plugin Push (fork)

This is a fork of `cordova-plugin-camera` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [apache/cordova-plugin-camera](https://github.com/apache/cordova-plugin-camera).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| [cordova-plugin-camera#814](https://github.com/apache/cordova-plugin-camera/pull/814) | Android 13 support |

You can see all the changes here: [6.0.0...moodlemobile:v6.0.0-moodle.1](https://github.com/apache/cordova-plugin-camera/compare/6.0.0...moodlemobile:v6.0.0-moodle.1)

## Installation

You can install this package using the [original installation instructions](https://github.com/apache/cordova-plugin-camera#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-camera@6.0.0-moodle.1
```

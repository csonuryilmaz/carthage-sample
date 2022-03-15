# carthage-sample
Sample iOS app which has its dependencies from Carthage dependency manager.

## Prerequisites
You must have [Carthage](https://github.com/Carthage/Carthage).

The simplest way to install it is `brew install carthage`. And make sure you're using `carthage` 0.38.0 or up.

## Running the app

* Clone this repo
* Run `carthage update --platform iOS --use-xcframeworks` in the "carthage-sample" folder
  * Use `--cache-builds` to avoid rebuilding a dependency if it can
* You should now be able to run the app or open in Xcode

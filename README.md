# vagrant-android

Vagrant Boxes using Android. 

* Most boxes in this repository use ISOs from [the Android-x86 project](http://www.android-x86.org).
* As of date only one box is available that uses Cyanogen 14.
* Distribution: OVA 2.0 format files.


## How to use

* Head over to the releases page and download an OVA file for the Android version you want.
* Import it into Virtualbox.

The eventual goal is to create boxes of various Android OS versions with [Packer](https://www.packer.io/docs/builders/virtualbox-ovf.html).

## Why would I need this?

This question is really two questions:

* Why would you need Android on your PC? 
* And why would you need Android in a Vagrant box format?

Possible uses:

1. You need a larger screen size on Android, or want to use a mouse and PC.
1. You need a disposable mobile environment on your PC; for example, for functional testing of Android apps, or to create a disposable test farm composed of various Android versions.


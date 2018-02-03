# vagrant-android

Vagrant Boxes using Android. 

* Most boxes in this repository use ISOs from [the Android-x86 project](http://www.android-x86.org).
* As of date only one box is available that uses Cyanogen 14.
* Distribution: OVA 2.0 format files.


## How to use

* Head over to the releases page and download an OVA file for the Android version you want.
* Import it into Virtualbox.

## What you get

Once you import and start the Virtual Machine, you should see a desktop looking like this:

![virtualbox_android-cm14_03_02_2018_08_20_27](https://user-images.githubusercontent.com/13379978/35762346-21e87046-08bb-11e8-8b67-d029f244f072.png)

This is a [Taskbar](https://play.google.com/store/apps/details?id=com.farmerbb.taskbar) desktop.

* The initial setup has been done
* Location Services and "Send Data to Google or Lineage" are disabled

## Troubleshooting

See [TROUBLESHOOTING.md](TROUBLESHOOTING.md).


The eventual goal is to create boxes of various Android OS versions with [Packer](https://www.packer.io/docs/builders/virtualbox-ovf.html).

## Why would I need this?

This question is really two questions:

* Why would you need Android on your PC? 
* And why would you need Android in a Vagrant box format?

Possible uses:

1. You need a larger screen size on Android, or want to use a mouse and PC.
1. You need a disposable mobile environment on your PC; for example, for functional testing of Android apps, or to create a disposable test farm composed of various Android versions.


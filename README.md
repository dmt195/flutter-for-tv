# Flutter TV List

## Introduction

This repository is designed to collate the state-of-the-art regarding Flutter and its applicability to the category of 'Connected TVs', including smart TVs, set-top boxes, and HDMI-type sticks.

The number of codebases required to maintain a footprint on Connected TVs is enormous without something like Flutter. Other approaches exist including wrapped web apps, but there are often limitations including:

* devices are resource (CPU, RAM, GPU) limited
* stores have restrictions around web or hybrid technologies

Flutter may not be the best solution but I am keen to track and assess developments. 

*Please create a pull-requests if you know of any additional resources.*

## General Resources

* [Talk by Aleksandr Denisov](https://mobius-piter.ru/en/2021/spb/talks/5enhvpgouw2kphfa6gxoii/) ([slides direct download](https://downloads.ctfassets.net/2grufn031spf/4nPNbHCr80hiXpZTxWeELi/66a85865b78b744d0e4e65b0190c560c/Aleksandr_Denisov_Flutter_for_TV_ili_Kak_zapilit_prilozheniye_dlya_televizora_2021_04_13_20_32_24.pdf))

## Android TV & Fire TV

Available on a wide range of TVs (Sony, Panasonic, etc). Fire TV apps also uses Android technologies although please check specific requirements for your app type when submitting. Easy to get started...

* Blog post - [How to cretae an Android TV app using Flutter](https://www.dltlabs.com/blog/how-to-create-an-android-tv-app-using-flutter-362536)
* Blog post - [Android TV Support with Flutter Framework](https://rrtutors.com/tutorials/Create-TV-App-with-Flutter)
* YouTube Video - [Flutter | Android TV App | Random Video - Breaking Code](https://www.youtube.com/watch?v=iDBxjGrezLE)


## tvOS (Apple TV)

While not the biggest market share, iOS users expect tvOS to be supported and are very animated about it if it's not! Not officially supported - some framework changes required...

* GitHub Repo - [LibertyGlobal](https://github.com/LibertyGlobal/flutter-tvos-demo)


## Samsung TV (Tizen)

One of the largest target markets. There seems to be a big effort here...
* GitHub Repo - [Swift-Kim](https://github.com/swift-kim/flutter-tizen)


## Roku TV (Brightscript)

Very popular in the US, and growing in popularity elsewhere. Possibly the trickiest to solve...

* [Flutter issue](https://github.com/flutter/flutter/issues/37159)


## LG TV (webOS)

Nothing found although, as webOS apps are build on web technologies I would have thought that Flutter could target the web and then get wrapped somehow to make this work. TBC.

## Arm based set top boxes

* Blog post - [How to port Flutter SDK to set-top boxes for Android TV apps running and development](https://promwad.com/company/news/how-port-flutter-sdk-set-top-boxes-android-tv-apps-running-and-development)
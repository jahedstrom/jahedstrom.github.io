---
published: true
title: Blocstagram
layout: post
---
![Blocstagram Screen Shots](https://jahedstrom.github.io/BlocstagramScreenShots.jpg "Blocstagram Screen Shots")

## Overview

Blocstagram is a full featured Instagram clone app developed for learning purposes.  It uses the instagram API to access all the features necessary such as getting new posts, uploading images and liking and commenting on posts in the feed.  The app also includes the ability to select photos from the device, crop and apply a number of custom filters to the image before uploading.

## Details

Blocstagram was written in Objective-C.  All views, view controllers and layout was done programmatically.  There are several view controllers in the project that stem from the root table view controller.  Also several custom view controls were developed for functions such as composing a comment and displaying a circle spinner while some action was being taken.  The Model-View-Controller (MVC) pattern was followed throughout the project.  Model objects were created and a shared datasource was used to facilitate access throughout the app.  Many design patterns and mechanisms were used in the app including: delegates and protocols, custom categories, key-value observing (KVO), MVC, grand central dispatch (GCD) and notifications.  There were two third-party libraries (AFNetworking and UICKeyChainStore) that were used and installed with CocoaPods.  My favorite part of developing this app was doing the image transformations and filters.
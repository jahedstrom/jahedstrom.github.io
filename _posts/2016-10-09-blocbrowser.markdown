---
published: true
title: BlocBrowser
layout: post
---
![BlocBrowser Screen Shots](https://jahedstrom.github.io/BlocBrowserScreenShots.png "BlocBrowser Screen Shots")

## Overview

This app is a simple web browser with a floating toolbar.  The toolbar can be moved around the screen and the navigation buttons will be automatically enabled/disabled based on which actions are possible.  The toolbar can also be resized using pinch zoom and a long press will change the background colors.  For privacy no sessions are cached and each time user shuts down the app or it resigns the active state the web session is cleared.

## Details

The app is written in Objective-C.  The UI code is created programmatically with a custom UI control for the floating toolbar.  The WkWebView class is used to implement the browser inside a custom view controller.  The floating toolbar is a custom UIView object with several gesture recognizers to handle pinch, pan, tap and long press gestures.  A custom protocol is defined in the toolbar object in order to pass the gesture events back to the main view controller.
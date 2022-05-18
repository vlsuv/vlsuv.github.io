---
title: "pomodoro"
date: 2020-09-15T11:30:03+00:00
tags: ["MVP", "UserNotifications", "UserDefaults", "UIKit"]
showToc: true
TocOpen: true
draft: false
hidemeta: true
comments: false
description: "Pomodoro timer app for ios."
disableHLJS: true 
disableShare: true
hideSummary: false
searchHidden: true
ShowPostNavLinks: true
cover:
    image: ""
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/vlsuv/vlsuv.github.io/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
## Features
- Set work interval, short break, long break, long break after, task goal
- When app unactive, show notification about time finishing
- Turn on/turn off notifications
- Start, Pause, Stop timer
- Show work steps
- Show current timer type
- Timer works and saves data when application is not active
- Support for light & dark mode. Dark mode using [Drakula Color Pallete](https://draculatheme.com/contribute)
- Circle progress view is filling while timer is on

## Used
- MVP + Router
- AssemblyBuilder for creating modules
- UserNotifications
- Observers for NotificationCenter
- Fully programmatically UI; AutoLayout;
- UserDefaults
- CABasicAnimation; CAShapeLayer
- UIVisualEffectView
- UIPresentationController
- UIKit

## Screenshots
| ![timer-stop-dark](Screenshots/timer_stop_dark.png)  | ![timer-dark](Screenshots/timer_dark.png) | ![settings-dark](Screenshots/settings_dark.png) | ![timer-light](Screenshots/timer_light.png)| 
|---|---|---|---|
| ![settings-light](Screenshots/settings_light.png) | ![time-pick_light.png](Screenshots/time_pick_light.png) | ![notification](Screenshots/notification.png) |  |

## Source code
The source code for this app can be found at [GitHub](https://github.com/vlsuv/pomodoro).






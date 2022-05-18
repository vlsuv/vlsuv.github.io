---
title: "Chat"
date: 2022-05-17T17:57:43+04:00
tags: ["MVVM", "Combine", "Firebase", "GoogleSignIn", "CoreLocation", "AVKit"]
showToc: true
TocOpen: true
draft: false
hidemeta: true
comments: false
description: "Messenger app using firebase services"
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
## Implemented features
- Register by email, google
- Change user's photo
- Search registered users
- Create new chat with any registered user
- Delete chat
- Send text/voice/photo/video/location message

## Used
- MVVM + Coordinator
- Combine
- FirebaseServices: Auth, Database, Storage.
- GoogleSignIn
- MessageKit
- CoreLocation
- MapKit
- UIImagePickerController
- AVKit
- Autolayout

## Source code
The source code for this app can be found at [GitHub](https://github.com/vlsuv/chat).
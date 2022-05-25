---
title: "Hacker News App"
date: 2022-05-18T17:38:32+04:00
tags: ["MVVM", "RxSwift", "RxCocoa", "Alamofire", "UserDefaults", "SafariServices", "UIKit", "CocoaPods"]
showToc: true
TocOpen: true
draft: false
hidemeta: true
comments: false
description: "A hacker news reader for iOS."
disableHLJS: true 
disableShare: true
hideSummary: false
searchHidden: true
ShowPostNavLinks: true
cover:
    image: "cover-image.png"
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
- Get top, new, show, asks, jobs stories
- Show how much time has passed and story's score
- Story's preview and show comments
- Share, add to reading list, read in safari
- Refresh all stories
- Infinite scroll and get next stories
- Light/dark theme
- Dynamically sized UITableViewCell

## Used
- Hacker News API
- MVVM + Coordinators
- AssemblyBuilder for creating modules
- RxSwift, RxCocoa
- Alamofire
- Without the use of storyboards
- AutoLayout; Xib
- UserDefaults
- SFSafariController
- UIKit
- CocoaPods

## User Interface
### Screenshots
|!["main-light"](screenshots/main_light.png)|!["detail-story-light"](screenshots/detail_story_light.png)|!["web-light"](screenshots/web_light.png)|
|---|---|---|
|!["detail-ask-light"](screenshots/detail_ask_light.png)|!["main-dark"](screenshots/main_dark.png)|!["detail-story-dark"](screenshots/detail_story_dark.png)|

### Video
{{< youtube IuCv7aw9vEQ >}}

## Source code
The source code for this app can be found at [GitHub](https://github.com/vlsuv/hn).
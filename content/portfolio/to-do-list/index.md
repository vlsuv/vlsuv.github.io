---
title: "To Do List"
date: 2022-05-18T17:06:09+04:00
tags: ["MVP", "Realm", "CocoaPods", "UIKit", "UserNotifications"]
showToc: true
TocOpen: true
draft: false
hidemeta: true
comments: false
description: "A to-do list app build for iPhone."
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
### Lists
- Create list for tasks
- Delete and rename list
- Change list's order by dragging

### Tasks
- Add task with title, description, reminder
- Edit task's title, description, reminder
- Delete tasks
- Change task's done status
- Delete all completed tasks
- Search any task by title
- Move task to any list
- Change task's order by dragging

### User-Interface
Visually look in the graph [Visual-User-Interface](#Visual-User-Interface)

Most of the icons by [Feather Icons](https://feathericons.com/)

- Some pages can be moved by touch and closed with a swipe down
- Start editing mode with long press
- Tasks columns can be expanded and hidden with animation
- The size of some pages depends on the content
- Animated resizing of some pages
- Dynamically size some cells

## Used
- MVP + Coordinators
- AssemblyBuilder for creating modules
- Realm & RealmSwift
- CocoaPods
- UIKit
- UserNotificationCenter
- AutoLayout
- Without the use of storyboards

## Screenshots
### Tasks
|!["tasks-page"](Screenshots/tasks-page.png)|!["new-task-page"](Screenshots/new-task-page.png)|!["edit-task-page-full"](Screenshots/edit-task-page-full.png)|
|---|---|---|

### Lists
|!["lists-page"](Screenshots/lists-page.png)|!["new-list-page"](Screenshots/new-list-page.png)|
|---|---|

### Other
|!["search-task-page"](Screenshots/search-task-page.png)|!["list-more-details-page"](Screenshots/list-more-details-page.png)|!["choose-list-page"](Screenshots/choose-list-page.png)|
|---|---|---|
|!["calendar-page"](Screenshots/calendar-page.png)|!["task-notification"](Screenshots/task-notification.png)| |

## Visual-User-Interface
|!["new-task-1"](Screenshots/gif/new-task1.gif)|!["new-task-2"](Screenshots/gif/new-task2.gif)|!["tasks-column"](Screenshots/gif/tasks-column.gif)|
|---|---|---|
|!["task-edit-mode"](Screenshots/gif/task-edit-mode.gif)|!["lists-edit-mode"](Screenshots/gif/lists-edit-mode.gif)| |

## Source code
The source code for this app can be found at [GitHub](https://github.com/vlsuv/to-do-list).

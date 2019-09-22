# NotificationCenterMap

[IT'S STILL WORK IN PROGRESS, IT DOESN'T WORK YET :)]

It's easy to lose track of Notifications from NotificationCenter because of its many-to-many nature. Notifications can be sent from anywhere to anywhere in your iOS project. NotificationCenterMap's goal is to show a map of objects posting notifications and their observers.

## Idea

This framework is going to scan your iOS project's codebase, look for post() and addObserver() calls and group them by notification's name. It will be a command line tool generating [PNG/JPG/maybe some other format] file.

# PWA Notifications and Intallable
기본 소스는 Mozilla 쪽에서 PWA 기본 기능이 구현된 소스를 가져왔어요.

```
This is an Enhanced version of my basic to-do app, which stores to-do items via IndexedDB, and then also aims to provide notifications when to-do item deadlines are up, via the Notification and Vibration APIs.

The IndexedDB and Notification API functionality all works on Firefox desktop, Firefox Android, Firefox OS, Chrome, and IE 10+.

The Vibration API stuff works on Firefox OS and Firefox for Android.

You can [try it out live](https://mdn.github.io/to-do-notifications/).
```


## notification
`function createNotification(title) { ... }` 이게 핵심.

## installable
기본적으로 Service Worker 가 있어야 하고,(깡통 `sw.js` 라도 있어야 함) 적절한 `manifest` 가 있어야 해요. 

[![Warning](http://img.youtube.com/vi/K5eGxwagx-w/0.jpg)](https://youtu.be/K5eGxwagx-w?t=0s)


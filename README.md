# Browser Lock (ex. Pattern Lock Extension)
Browse freely. Browser Lock locks your browser.</br>
Most requests for feature proposals on the [Whale Forum](http://forum.whale.naver.com/)

## What Is It All About
Browser Lock is an extension of the Chrome-based browser and is designed to lock the browser.</br>
In the first half of 2017, thanks to the launch of NAVER's Chrome-based Web Browser Whale , we considered ways to respond to requests to lock the browser for various reasons. This project was started by examining whether the corresponding function (browser lock) could be realized at the level of the extension rather than the browser.

## Lock
Locking the browser means to block access to the browsing history up to the point before the lock. When the authority (in this case, the password or pattern) is obtained, the previous browsing history can be accessed again, otherwise the record will be lost.

## How It Works
Browser Lock locks the browser in the following way.
- Save and close open tab serialization
- Save and delete all saved cookies
- Saving and Deleting Browsing History
- lock screen output

When the lock is activated, the user's login status is released, and the previous unique usage history cannot be accessed without unlocking it.</br>
Meanwhile, the user (or guest) can freely use the browser even on the lock screen.</br>
If the user succeeds in entering the Master Password on the lock screen, all saved data is restored and the browser (tabs, etc.) is set to the point before lock.

## Build
```
npm install
npm run build
```

## Install
You need to add an extension app for the Chrome-based browser. At this time, you need to add (or load) the lib folder created through Build.

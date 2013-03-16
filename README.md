This is a dirty proof of concept to demonstrate how to hide Apple's system Apps on iOS.
(At least until you reboot your iDevice or until Apple fixes this bug).

# Installation

Currently my personal URL is hardcoded in the index.html and the plist-files.
So prior to use this Webapp, do a search on these files and replace the URL with your own URL.
(If you are able to contribute a more sophisticated solution, don't hesitate to fork and improve it!)
Upload all files to your URL and open it with Mobile Safari.

# Usage

1. Tap on the app you want to hide and install the "Delete me!"-App. You'll notice that the install process will fail intentionally).
2. Tap and hold the "Delete me!"-App and (guess what) delete the app.
3. Success!

# Known Problems

* I noticed my Music Player (Ecoute.app) stopped working if the native Music.app was previously hidden.
* Hidden Apps appear in the Notification-Center with their Bundle Identifier (com.apple.foo) instead of their name.

# Demo

Open http://hide.pheraph.net on your iOS-device to try it out, but I really recommend to install it on your own host.
Who wants to install some shady plists from an unknown source?

Kudos to David Gölzhäuser for his HiddenApp (removed from the AppStore) and his Webapp available here: http://idoodler.de/hideapps.html

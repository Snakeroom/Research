# r/Imposter in Official Reddit Platforms

## Android APK

As of [version 2020.10.0](https://www.reddit.com/r/redditmobile/comments/fnrc3s/reddit_for_android_version_2020100_now_available/) of the Android APK], code exists to show two elements based on whether the event is active.

The event icon appears in the top of the home and communities tabs next to search bar with an icon of an eye mask. Clicking this button takes you to the [r/Imposter](https://www.reddit.com/r/imposter) subreddit.

The event embed appears in the top of r/Imposter, pointing to `https://gremlins-api.reddit.com/embed?platform=android`. When night mode is enabled, the query parameter `nightmode` is set to 1` as well. When the embed is tapped, a fullscreen version is launched, pointing to `https://gremlins-api.reddit.com/embed?platform=android&fullscreen=1` (along with the `nightmode` parameter if night mode is enabled).

## iOS Application

Similar to the Android APK, the iOS application contains code to show the event's button and embed as of [2020.10.0](https://www.reddit.com/r/redditmobile/comments/fnrdmr/reddit_for_ios_version_2020100_now_available/).

The following assets are used for the buttons in light mode and dark mode respectively:

![Dark imposter icon](https://i.imgur.com/ggiIpFS.png)
![Light imposter icon](https://i.imgur.com/p9FyC74.png)

They appear in the same place as the Android version:

![r/imposter icon](https://i.imgur.com/x4aQXiU.jpg)

In addition, the embed exists in the same place:

![r/imposter embed](https://i.imgur.com/Pmk8BZe.jpg)

Due to an issue, the button would always appear despite the event not being active. This issue was resolved in 2020.10.1.

## Desktop Redesign

Once more, the desktop redesign has code to show the button and embed for the event.

The embed leads to `https://gremlins-api.reddit.com/embed?platform=android` and cannot be clicked to become fullscreen.

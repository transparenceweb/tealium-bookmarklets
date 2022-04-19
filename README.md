# tealium-bookmarklets
Helper scripts for using Tealium. Quick options to turn on [debugger](https://github.com/transparenceweb/tealium-bookmarklets/blob/main/activate-debugger.js) for TIQ, check the [current environment and version](https://github.com/transparenceweb/tealium-bookmarklets/blob/main/current-environment-and-version-checker.js) to make sure you are viewing the latest change, and a more detailed script to [duplicate Eventstream Event Feeds based on GUID](https://github.com/transparenceweb/tealium-bookmarklets/blob/main/event-feed-duplicator.js).

## Debugger
Just click the bookmarklet to set the debug cookie for the site you want to test.

## Check environment and version
Will log a message to console, for example: `Tealium version is ut4.46.202202101428 and current environment is prod`.

## Duplicate Eventstream Event Feed
In Eventstream, there is no native function to allow the copying or duplication of event feeds as there are with other features such as connectors. This script allows that.
1. Select the Event Feed you want to duplicate and copy the GUID from the end of the URL.

![Copy GUID from Event Feed URL](https://user-images.githubusercontent.com/2863273/163970080-a82b30e5-a272-424c-a6bc-c986671c35ca.png)

2. Click the bookmarklet and paste the copied GUID into the pop up.

![Paste into pop up to create copy](https://user-images.githubusercontent.com/2863273/163969937-9515cc21-e8ff-41d9-9d07-81db521156a4.png)

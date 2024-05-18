# Lab8-Starter

Yuvanand Saravanan

Graceful degradation and service workers are related in that we start with our full application that may require higher network speeds and then add service workers as a kind of backup to store responses for requests we send so that pages can load quickly and network requests are handled separately, especially in cases where the user has a slow network speed or no internet at all at some point in time. After the first time such a user loads the webpage, data is cached so that the next time they load the page, they may not get the full experience that we meant for our users to have but at least they will have some degraded experience that is better than waiting forever for the page to load.

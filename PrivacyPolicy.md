# SwipeClock Privacy Policy

**Last updated: November 22, 2026**

SwipeClock is a Chrome extension by BlackPearl that calculates work time, breaks, progress, and estimated leaving time from attendance swipes in greytHR.

## Consent

SwipeClock does not read greytHR page content or attendance responses until the user selects **Allow & continue** in the extension popup. Users can stop syncing and clear the locally cached swipes from the popup.

## Information processed

SwipeClock processes today's swipe dates and times and IN/OUT directions. When reading the swipe table, it may temporarily inspect the text in a matching row to locate those values; other row text is discarded and door or location labels are not stored. It may use the current greytHR page origin and a same-origin API endpoint path to retrieve today's swipe records. It uses the user's existing greytHR session, including the browser's greytHR cookies and, when available, the greytHR XSRF token, to request data from that same greytHR site. SwipeClock does not capture or store Authorization headers.

## How information is used

Attendance data is used only to display work sessions and calculate work time, break time, progress toward the daily target, and estimated leaving time.

## Storage and retention

- Swipe dates, times, directions, and the current day's cache are stored in Chrome local storage.
- A greytHR API endpoint path may be stored in Chrome local storage to support later same-origin sync requests.
- Daily target preferences are stored with Chrome Sync when changed and may synchronize according to the user's Chrome settings.
- Text pasted manually into the popup is processed in the popup and is not saved by SwipeClock.
- Locally stored swipe data remains until replaced or cleared. Users can use **Stop syncing & clear cached swipes** in the popup to remove the consent setting, swipe cache, and saved endpoint path. This does not remove daily target preferences from Chrome Sync.

## Sharing

SwipeClock does not operate a server, sell attendance data, or share it with the developer or unrelated third parties. When retrieving swipe records, the browser sends the request and its existing greytHR session to the user's greytHR site. Daily target preferences use Chrome Sync and may be handled by Google according to Chrome's sync settings. SwipeClock does not use information for advertising or analytics.

## Limited Use

SwipeClock's use and transfer of information obtained from greytHR pages and requests is limited to providing the extension's attendance time-tracking features and complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Contact

For privacy questions, contact Developers through the support contact provided on the SwipeClock Chrome Web Store listing.

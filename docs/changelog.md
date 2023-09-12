# Change Logs

### Current Release
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/us/app/optimal-hrv/id1501292206)
[![Play Store](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.optimalhrv.app&hl=en_US&gl=US)

- #### v3.3.5 (Sep 11, 2023)
    **Features:**
    - Upgraded the bluetooth and device connection integration for all reading screens.

    **Bug Fixes:**
    - Couple of issues/bugs fixed.

### Previous Releases

- #### v3.3.4 (2023-07-18)
    **Features:**
    - Added a Reset Session Progress feature.
    - Added a Progress indicator to track the number of completed exercises in a session.
    - Implemented a backend service to reset session exercises, allowing users to start from scratch.
    - Users are now automatically navigated to the final results without having to click the "Show Final Results" button.
    - Improved the UI/UX of the biofeedback screen.
    - Added a Delete Readings feature on the readings history screen.
    - Added a notes input box before the tags for better organization.
    - Displayed the notes on the readings history screen.
    - Implemented a bottom sheet to show complete notes when users click on them.

    **Bug Fixes:**
    - Fixed the permission check
    - Fixed an issue where the Continue and Stop buttons were not functioning properly.
    - Resolved the problem with the permission check on certain screens.
    - Addressed the issue where the device would appear connected even after disconnection during a session, causing repeated error messages.
    - Fixed the Bluetooth connectivity issue.
    - Fixed the issues in biofeedback RMSSD API's.
    - Resolved the problem of RF results not being displayed on the biofeedback screen.
    - Fixed the issue where the Name field was not displayed on the home screen upon initial rendering.
    - Fixed the issue of missing spacing in the vertical and horizontal layout on the home screen.
    - Fixed the problem of the New Reading button not appearing when data was not loaded yet.
    - Fixed the issue with post-reading notes not displaying correctly.
    - Fixed the post-reading model and improved the overall UI/UX.

- #### v3.3.3 (2023-07-01)
    **Features:**
    - Improved RF Assessments with the ability to pause and start.
    - Ability to reset sessions and also handle Bluetooth and Network disconnections.

    **Bug Fixes:**
    - Fixed the permission check
    - Fixed Bluetooth disconnection issues.
    - Fixed other minor bugs.

- #### v3.3.2 (2023-06-21)
    **Bug Fixes:**
    - Removed a label and icon
    - Remember me at login - fixed
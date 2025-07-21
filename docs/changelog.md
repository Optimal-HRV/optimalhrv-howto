# Change Logs

### Current Release
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/us/app/optimal-hrv/id1501292206)
[![Play Store](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.optimalhrv.app&hl=en_US&gl=US)

- #### v5.3.9 (May 20, 2025)
    **Features:**
    - Added comprehensive device connectivity troubleshooting widget to help users resolve Bluetooth pairing issues
    - Enhanced device scanning instructions with improved user guidance
    - Improved low-quality data detection with enhanced dialogue checks

    **Bug Fixes:**
    - Fixed critical 3.5 BPM breathing rate calculation issues in biofeedback exercises
    - Resolved heart rate chart rendering and data display problems
    - Fixed custom tags functionality issues in reading settings
    - Resolved app crashes in profile and subscription detail screens
    - Fixed type errors in reading settings provider
    - Corrected Optimal Zone data manager issues
    - Fixed morning routine and subscription plan provider bugs
    - Improved overall app stability and performance

    **Technical Improvements:**
    - Enhanced Bluetooth device connectivity and error handling
    - Optimised biofeedback exercise accuracy and breathing rate algorithms
    - Improved UI/UX for exercise listing screens
    - Better error handling for device connection states
    - Enhanced data validation and quality checks

### Previous Releases

- #### v5.3.8 (May 2025)
    **Features:**
    - Added device connectivity troubleshooting tools

    **Bug Fixes:**
    - Fixed app break issues in various UI components
    - Improved low-quality data handling with dialogue checks

- #### v5.3.7 (May 2025)
    **Features:**
    - Enhanced device scanning instruction display

    **Bug Fixes:**
    - Improved Bluetooth device connectivity workflow

- #### v5.3.6 (May 2025)
    **Bug Fixes:**
    - Resolved custom tags issues in reading settings
    - Fixed UI components in exercise screens

- #### v5.3.5 (April 2025)
    **Bug Fixes:**
    - General UI fixes and improvements
    - Enhanced exercise screen functionality

- #### v5.3.4 (April 2025)
    **Bug Fixes:**
    - Critical 3.5 BPM fix for biofeedback exercises
    - Improved exercise provider and screen components

- #### v5.3.3 (April 2025)
    **Bug Fixes:**
    - Fixed heart rate chart issues
    - Environment configuration improvements

- #### v3.3.5 (Sep 11, 2023)
    **Features:**
    - Upgraded the bluetooth and device connection integration for all reading screens.

    **Bug Fixes:**
    - Couple of issues/bugs fixed.

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

# Privacy Policy - Battery Monitor

**Last Updated:** August 11, 2026

Battery Monitor is committed to respecting your privacy.

## Data Collection and Storage
- **Local Storage Only**: All battery health records, sample logs, charging session data, and temperature records are stored strictly on your local device inside an encrypted SQLite Room database.
- **No Cloud Synchronization**: Battery Monitor does not operate cloud servers, external backends, or analytics trackers.
- **No Account Required**: You can use the application without registering an account or providing personal details.

## Permissions Explained
- **Foreground Service (`FOREGROUND_SERVICE`)**: Required to monitor battery level changes, voltage, and temperature continuously in the background.
- **System Overlay (`SYSTEM_ALERT_WINDOW`)**: Required if you choose to enable the optional floating overlay window.
- **Usage Access (`PACKAGE_USAGE_STATS`)**: Required if you choose to inspect per-app screen usage stats.
- **Bluetooth (`BLUETOOTH_CONNECT`)**: Required to display connected Bluetooth earbud/accessory battery levels.

## Data Control
You can clear all battery logs at any time from **Settings > Clear All Battery History**.

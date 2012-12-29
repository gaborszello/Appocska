Pill Reminder
-------------

Version 0.6 - Cleaning up
- Lot of stuff deleted/modified
- Implemented Up navigation all around the app

Version 0.5 - Settings, settings, settings...
- Lot of new stuff in the settings
- Removed unnecessary lines of code
- Added new localizations

Version 0.4.1 - Iconic release
- New appropriate icon

Version 0.4 - Pill Reminder
- Added hungarian localizations
- Namechange from Appocska to Pill Reminder

Version 0.3 - Big leaps
- Added dummy settings menu and about toast

Version 0.2
- Knows something, but nothing fancy

Version 0.1
- Knows nothing

Backward compatibility
----------------------

Modify the following lines in:

AndroidManifest.xml
- android:minSdkVersion="11" to android:minSdkVersion="8"

DisplayMessageActivity.java
- getActionBar().setDisplayHomeAsUpEnabled(true); to //getActionBar().setDisplayHomeAsUpEnabled(true);
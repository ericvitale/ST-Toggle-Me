# Toggle-Me
## Summary
SmartThings SmartApp for turning on and off switches, lights, dimmers, ... (frequenty) on a schedule.

If you have several scenarios you would like to control, just install the app from "My Apps" multiple times.

## Preferences
*Switches* - Switches to toggle.
Dimmers - Dimmers to toggle.
Dimmer Level - Level to set dimmers to.
Color Temperature Lights - Color Temperature Lights to toggle.
Color Temperature  - Color temperature to set color temperature lights to.
Color Temperature Lights Level - Level to set color temperature lights to.
Turn on for N seconds? - Seconds to turn lights on for.
Turn off for N seconds? - Seconds to turn lights off for.
Follow sunset / sunrise? - Only turn on / off when sun is down?
Sunrise Offset - Offset for sunrise.
Sunset Offset - Offset for sunset.
Use Custom Time Range - Toggle for custom time range, only run during the following times.
Start Time - Start time.
End Time - End time.
Rules Active - Run this program?
Log Level - Logging Level.

## Installation via GitHub Integration
1. Open SmartThings IDE in your web browser and log into your account.
2. Click on the "My SmartApps" section in the navigation bar.
3. Click on "Settings".
4. Click "Add New Repository".
5. Enter "ericvitale" as the namespace.
6. Enter "ST-Toggle-Me" as the repository.
7. Hit "Save".
8. Select "Update from Repo" and select "ST-Toggle-Me".
9. Select "toggle-me.groovy".
10. Check "Publish" and hit "Execute".

## Manual Installation (if that is your thing)
1. Open SmartThings IDE in your web browser and log into your account.
2. Click on the "My SmartApps" section in the navigation bar.
3. Click the blue "+ New SmartApp" button at the bottom of the page.
4. Click "From Code".
5. Paste in the code from "toggle-me.groovy" and hit "Create". (https://github.com/ericvitale/ST-Trigger-My-Lights/blob/master/smartapps/ericvitale/trigger-my-lights.src/trigger-my-lights.groovy)
6. Click the "Publish" --> "For Me".
7. The app will appear on your app under "Marketplace" --> "My Apps"

# doordash-driver-app-bugs-part2
Driver location does not update accurately in the DoorDash Driver app, causing order offers to be based on an incorrect location.

# Bug Report
**Title:** Driver location does not update correctly in DoorDash Driver app while moving

## Description
While actively using the **DoorDash Driver (Dasher) app** and moving between locations, the app does not accurately update the driver’s real-time location. The location shown inside the app differs from the actual current location when compared with Google Maps. This results in the app displaying an outdated or incorrect position while the driver is in motion.

---

## Steps to Reproduce
1. Open the **DoorDash Driver (Dasher)** app.
2. Start looking for orders.
3. Ride or drive between multiple locations over a period of time.
4. Observe the location shown in the Dasher app.
5. Open **Google Maps** and compare the displayed location with the Dasher app.

---

## Expected Behavior
- The Dasher app should update the driver’s location in real time while moving.
- The in-app location should closely match the real-time GPS location shown in Google Maps or other navigation apps.

---

## Actual Behavior
- The driver’s location in the Dasher app updates slowly or inaccurately.
- The in-app location does not match the actual current location shown in Google Maps.
- The app continues to display an outdated position even while moving.

---

## Frequency
- 2/10

---

## Environment
- **Application:** DoorDash Driver (Dasher) app
- **Platform:** Android
- **App Version:** 8.62.1
- **Date Observed:** Jan 7, 2026
- **Network:** Mobile data

---

## Impact
- Creates confusion for drivers relying on accurate in-app location tracking.
- Reduces reliability of location-based features within the app.
- Negatively affects overall navigation and tracking experience.

---

## Additional Notes
- Google Maps and other navigation apps consistently show the correct real-time location.
- Restarting or Pause the app does not consistently resolve the issue.
- Location mismatch is noticeable while the app remains open and active.

---

## Attachments
- Screen recordings comparing Dasher app location with Google Maps

https://github.com/user-attachments/assets/1eeeeb70-b9ee-4418-bae9-fc5b3e60de65

.

---



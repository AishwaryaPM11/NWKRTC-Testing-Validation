# Test Plan — NWKRTC BusTrack

## 1. Objective
Plan validation of the passenger, driver and admin modules, including bus search, live tracking, authentication, trip management and database access.

## 2. Scope
Features visible in the supplied source:
- Passenger navigation and information pages
- FROM/TO bus search using sample route data
- Live bus location display and approximate ETA
- Driver login, assigned trips, trip status actions, GPS sharing and issue notifications
- Admin login and bus, driver, route, schedule, trip, report and notification screens
- Firebase Realtime Database access rules

## 3. Test environment to record
- Application URL/build:
- Browser and version:
- Device/OS:
- Firebase project/environment (never record credentials):
- Tester:
- Test date:

## 4. Entry criteria
- App build is available.
- Test Firebase environment is configured.
- Test accounts and sample records are prepared.
- Testers have permission to use the test environment.

## 5. Exit criteria
- All planned cases have an execution status.
- Failed cases have reproducible steps and evidence.
- Critical issues are reported to the project team.
- No result is marked Pass without actual execution evidence.

## 6. Safety
Use test accounts and a non-production Firebase project where possible. Never include passwords, API secrets, private keys or personal passenger data in screenshots or repository files.

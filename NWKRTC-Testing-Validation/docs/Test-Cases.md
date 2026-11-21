# Test Case Register — NWKRTC BusTrack

**Execution status for every case below: Not Run.** Update only after executing the test.

| ID | Area | Test scenario | Expected result | Status |
|---|---|---|---|---|
| TC-01 | Passenger | Open home page | Home page loads without an error | Not Run |
| TC-02 | Navigation | Open About, Routes and Contact | Correct page is displayed | Not Run |
| TC-03 | Search | Search Hubballi to Dharwad | Matching sample buses are listed in departure order | Not Run |
| TC-04 | Search validation | Submit without FROM or TO | Validation message asks for both locations | Not Run |
| TC-05 | Search validation | Select same FROM and TO | Validation message says locations cannot be the same | Not Run |
| TC-06 | Search | Search a route with no sample bus | No-buses-found state is displayed | Not Run |
| TC-07 | Live tracking | Open Live Map without selecting a bus | Prompt to select a bus is displayed | Not Run |
| TC-08 | Live tracking | Select a bus with no recent location | Not-running state is displayed | Not Run |
| TC-09 | Live tracking | Select a bus with a fresh live record | Map and approximate ETA information are displayed | Not Run |
| TC-10 | Driver access | Submit empty driver login form | Required-field validation is displayed | Not Run |
| TC-11 | Driver access | Sign in with valid driver test account | Driver dashboard/profile is displayed | Not Run |
| TC-12 | Driver trips | Start an eligible scheduled trip | Trip status changes to In Progress and GPS sharing starts if permission is granted | Not Run |
| TC-13 | Driver trips | Mark an in-progress trip delayed | Trip status changes to Delayed and a notification is created | Not Run |
| TC-14 | Driver trips | Report an issue with description | Issue notification is sent to the database | Not Run |
| TC-15 | Driver trips | Complete an active trip | Trip status changes to Completed and arrival time is recorded | Not Run |
| TC-16 | Admin access | Submit empty admin login form | Required-field validation is displayed | Not Run |
| TC-17 | Admin | Open admin management sections with valid admin account | Admin pages are accessible | Not Run |
| TC-18 | Admin | Add/edit a bus, route, driver or schedule in test data | Data is saved and displayed correctly | Not Run |
| TC-19 | Role access | Try to access a restricted database write as an unauthorised user | Firebase rules reject the write | Not Run |
| TC-20 | Session | Leave driver/admin area or switch to passenger area | Auth session is logged out according to app logic | Not Run |

## Execution record
For each test, record:
- Actual result
- Pass / Fail / Blocked
- Date and tester
- Screenshot or log filename
- Bug ID if failed

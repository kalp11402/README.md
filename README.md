# README.md
write the test case on apk



---

 Test Case 1: Verify App Launch

**Test Case ID:** TC_001

**Steps:**

1. Tap on the app icon

**Expected Result:**

* App should open successfully

**Actual Result:**

* App opened successfully without any crash

**Status:** Pass

---

 Test Case 2: Verify "Start Tracking Service" Button

**Test Case ID:** TC_002

**Steps:**

1. Launch the app
2. Check button visibility

**Expected Result:**

* "Start Tracking Service" button should be visible

**Actual Result:**

* Button is visible and enabled

**Status:** Pass

---

 Test Case 3: Verify Button Click

**Test Case ID:** TC_003

**Steps:**

1. Tap "Start Tracking Service"

**Expected Result:**

* Tracking should be start

**Actual Result:**

* Tracking stated 
**Status:** Pass

---

 

---

Test Case 4: Grant Permission

**Test Case ID:** TC_004

**Steps:**

1. Select "While using the app"
2. Allow permission

**Expected Result:**

* Permission granted

**Actual Result:**

* Permission granted successfully

**Status:** Pass

---

 Test Case 5: Verify Button Text Change

**Test Case ID:** TC_005

**Steps:**

1. Grant permission
2. Observe button text

**Expected Result:**

* Button text changes to "Stop Tracking Service"

**Actual Result:**

* Button text changed to "Stop Tracking Service"

**Status:** Pass

---

 Test Case 6: Verify Activity Logs Entry

**Test Case ID:** TC_006

**Steps:**

1. Start tracking
2. Open Activity Logs

**Expected Result:**

* Log entry with "Location Update"
* Contains "Lat:" and "Lng:"

**Actual Result:**

* Log entry displayed with "Location Update"
* Latitude and Longitude values are shown

**Status:** Pass

---

## Test Case 7: Verify Location Update Frequency

**Test Case ID:** TC_007

**Steps:**

1. Start tracking
2. Wait for some time
3. Observe logs

**Expected Result:**

* Location should update periodically

**Actual Result:**

* Location is updating approximately every 1 minute

**Status:** Pass

---
## Test Case8 : Verify Location Update Frequency## Test Case ID: TC_009

**Objective:** Verify location details display correctly in popup

**Steps:**

1. Start tracking service
2. Wait for location update
3. Observe popup/card

**Expected Result:**

* Location details should display correctly
* "Accuracy" should appear only once

**Actual Result:**

* "Accuracy" field appears twice

**Status:** Fail

# Kazam-EV-Charging
📌 Kazam EV Charging Application - Manual Testing README
📋 Project Overview
The Kazam EV Charging Application is a mobile app designed to simplify electric vehicle (EV) charging. It enables users to:
✅ Locate nearby charging stations
✅ Check real-time availability
✅ Book charging slots
✅ Navigate to the selected station
✅ Make hassle-free payments

This README provides manual testing guidelines to ensure a seamless and bug-free user experience.

📂 Table of Contents
Test Environment
Testing Scope
Test Scenarios
Defect Reporting
Test Execution & Reporting
🛠 Test Environment
🔹 Devices & OS
Android (Version 9.0 and above)
iOS (Version 13.0 and above)
🔹 Network Requirements
Stable Wi-Fi or 4G/5G connection
🔹 App Versions
Testing on latest build (e.g., Kazam v1.0.3 Beta)
🔹 Tools Used
Bug tracking: JIRA / Trello
Test case management: TestRail / Google Sheets
📌 Testing Scope
1️⃣ Functional Testing
App installation and launch
User registration & login/logout
Searching for charging stations
Booking & canceling a slot
Payment transactions
2️⃣ UI/UX Testing
Screen layout, button alignment, and responsiveness
Color contrast, font size, and accessibility features
3️⃣ Performance Testing
App response time under different network conditions
Load testing (multiple users searching/bookings at once)
4️⃣ Security Testing
User authentication & session management
Secure payment transactions
5️⃣ Compatibility Testing
Different screen sizes and resolutions
OS compatibility (Android & iOS)
📌 Test Scenarios
Test Case ID	Scenario	Expected Result	Status
TC_001	Launch the app	App should open without crashing	✅ Pass / ❌ Fail
TC_002	User registration with valid details	User should be successfully registered	✅ Pass / ❌ Fail
TC_003	User login with incorrect password	Error message should be displayed	✅ Pass / ❌ Fail
TC_004	Search for nearby charging stations	List of stations should appear based on location	✅ Pass / ❌ Fail
TC_005	Book a charging slot	Booking confirmation should be displayed	✅ Pass / ❌ Fail
TC_006	Cancel a booking	Slot should be canceled and available for others	✅ Pass / ❌ Fail
TC_007	Make a payment using a credit card	Payment should be successful	✅ Pass / ❌ Fail
TC_008	App functionality under poor network conditions	App should display a proper error message	✅ Pass / ❌ Fail
🐞 Defect Reporting
If a bug is found, report it with the following details:
🔹 Bug ID: Unique identifier (e.g., BUG_001)
🔹 Summary: Brief description of the issue
🔹 Steps to Reproduce: Clear steps to replicate the issue
🔹 Expected Result: What should happen
🔹 Actual Result: What actually happens
🔹 Severity: Critical / High / Medium / Low
🔹 Screenshot/Screen Recording: Attach evidence if needed

Example:

less
Copy
Edit
Bug ID: BUG_001  
Summary: App crashes when searching for charging stations  
Steps to Reproduce:
1. Launch the Kazam app  
2. Enter location and tap on "Find Charging Stations"  
3. App crashes immediately  
Expected Result: List of charging stations should be displayed  
Actual Result: App crashes and closes  
Severity: High  
📊 Test Execution & Reporting
Test execution schedule: Weekly sprint testing
Daily Test Report: Status updates on passed, failed, or blocked test cases
Final Test Report: Summary of defects, coverage, and suggestions for improvement
📌 Conclusion
Manual testing of the Kazam EV Charging Application ensures a smooth, user-friendly, and secure experience for EV owners. By following these structured test cases and reporting bugs effectively, we contribute to delivering a high-quality product.

📌 Tester Name: Shivendra Singh
📌 Testing Team: QA Team – Kazam

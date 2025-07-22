#📱 Eventify App – QA Testing Documentation
#📘 Overview
Eventify is a mobile application that allows users to explore, book, and manage events such as concerts, conferences, meetups, and more. The app provides a user-friendly interface for discovering events based on location, category, and date.

As a QA Intern, I was responsible for performing manual testing on Eventify to ensure a bug-free and smooth user experience.

#🔍 Scope of Testing
This documentation covers the testing performed on the following modules of the Eventify mobile app:

#🔎 Event Discovery
#📅 Event Booking
#👤 User Registration & Login
#💳 Payment Integration
#📄 Booking History
#⚙️ Profile & Settings

#🧪 Types of Testing Performed
Type of Testing	Description
Functional Testing	Verified core features work as expected (e.g. booking, search).
UI/UX Testing	Checked app design, layout, and usability on various screen sizes.
Regression Testing	Ensured new updates didn’t break existing functionality.
Negative Testing	Verified how the app behaves with invalid inputs or actions.
Validation & Field Checks	Tested forms like login, registration, and payment inputs.

#✅ Sample Test Scenarios
🧾 1. User Login
Test Case ID	Scenario	Input	Expected Output	Status
TC_Login_01	Valid login credentials	email + password	Redirected to Home page	✅ Pass
TC_Login_02	Invalid password	email + wrong password	Error message displayed	✅ Pass
TC_Login_03	Blank fields	empty email & password fields	Validation error shown	✅ Pass

#🎉 2. Event Booking
Test Case ID	Scenario	Steps	Expected Result	Status
TC_Book_01	Book a free event	Select event → Tap Book → Confirm	Booking success message shown	✅ Pass
TC_Book_02	Book a paid event	Select event → Proceed to payment → Enter card → Confirm	Payment processed, ticket shown	✅ Pass
TC_Book_03	Book without login	Try booking as guest	Redirected to login page	✅ Pass

#🔁 Bugs Reported
Bug ID	Title	Severity	Description	Status
BUG101	Payment button unresponsive	High	Button does not respond on first tap	Fixed
BUG102	Event image overlap in UI	Medium	UI breaks on small screen devices	In Progress
BUG103	Error message not shown	Low	No error when blank email submitted in login form	Fixed

#⚙️ Tools Used
#📱 Device: Android (Physical + Emulator)

#🧪 Testing Tools: Postman (for backend API checks), Google Sheets (for test case tracking)

#📸 Screenshots & Logs: Collected and shared in bug reports

🧾 Documentation: Test cases written manually in Excel/Google Sheets

#📌 Key Learnings
Learned the end-to-end flow of event booking systems

Understood real-user scenarios and importance of UI/UX

Gained experience in test case writing, executing, and reporting bugs

Communicated effectively with developers and team for issue resolution

#📎 Conclusion
This hands-on testing experience with the Eventify mobile app allowed me to apply manual testing practices in a real-world project. I tested core modules, discovered bugs, and ensured quality delivery for a better user experience.

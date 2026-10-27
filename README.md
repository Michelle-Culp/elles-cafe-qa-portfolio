# elles-cafe-qa-portfolio
QA Testing Portfolio: Functional, UI, and API testing for EllesCafe web application.

Project Overview
This repository contains the complete QA documentation for the EllesCafe web application, a .NET Core MVC project. Testing covered five main pages: Home, Menu, Cart, Admin Authentication (Login/Logout), and the Admin Dashboard.

Testing Scope & Tools Used

Manual Testing: 28 test cases executed covering UI, functional, and edge-case scenarios.

Bug Tracking: Jira (Kanban board used for logging and resolving 5 defects).

API Testing: Postman (Verified HTTP 200 server health and 200 OK/redirect security on unauthorized Admin routes).

Database Validation: SSMS (SQL Server Management Studio) to verify data persistence for cart orders and admin item creation/deletion.

Browser Tools: Chrome DevTools (Console error tracking, Network tab performance checks).

Key Defects Identified & Resolved:

Menu Images: Placeholder images displaying instead of real photos; duplicate image paths in the Ice Cream section.

Quantity Selector: loadCart() JavaScript crash preventing the +/− buttons from functioning.

Cart Badge: Event listener firing twice, causing the badge count to double.

Cart Removal Logic: Clicking "-" below a quantity of 1 deleted the item entirely instead of stopping at 1.

Admin Navigation: Footer Admin link routed to a blank page, and CSS hover hid the link text.

Portfolio Artifacts:

EllesCafe_Test_Matrix.xlsx: The master test case sheet containing preconditions, steps, expected/actual results, and Jira cross-references.

Screenshots: See the /screenshots folder for views of the Jira board, detailed bug reports, and Postman API checks.

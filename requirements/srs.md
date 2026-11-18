SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

JAOF FOODS – Small Shop Stock and Sales Tracker

1. Introduction

The proposed system is a web-based application designed to help JAOF FOODS manage its food production, fish farming, inventory and sales activities. It will reduce dependence on manual records and make it easier to monitor available stock, record transactions and generate reports.

2. Functional Requirements

Functional requirements describe what the system shall do.

ID| Requirement| Measurable Fit Criterion
FR-01| The system shall allow registered users to log in using their username or email and password.| A registered user can log in with valid credentials, while invalid credentials are rejected.
FR-02| The system shall allow the administrator to create, update and deactivate user accounts.| The administrator can successfully perform all three operations on a test account.
FR-03| The system shall allow authorized users to add, view, update and delete product records.| A test product can be added, displayed, updated and deleted successfully.
FR-04| The system shall allow users to record raw materials and their available quantities.| A user can enter a raw material and its quantity, and the saved record appears in the inventory.
FR-05| The system shall allow authorized users to update raw material quantities when materials are received or used.| The inventory quantity changes correctly after a receipt or usage transaction.
FR-06| The system shall allow production workers to record production activities, including the product, quantity produced and production date.| A production record can be saved and retrieved with all required information.
FR-07| The system shall update finished-product stock when a production record is completed.| The finished-product quantity increases by the quantity recorded in production.
FR-08| The system shall allow authorized users to record fish stocking activities in the pond.| A fish stocking record can be saved with the quantity and date.
FR-09| The system shall allow authorized users to record fish mortality and update the fish stock accordingly.| Recorded mortality reduces the available fish quantity by the exact number entered.
FR-10| The system shall allow users to record fish harvesting activities.| A harvest record can be saved with the harvest date and quantity.
FR-11| The system shall maintain separate inventory records for fresh fish and smoked fish.| Users can view the available quantities of fresh and smoked fish separately.
FR-12| The system shall allow authorized users to record sales, including the product, quantity, unit price and sale date.| A completed test sale is saved with all required details and a correctly calculated total.
FR-13| The system shall automatically update product inventory after a successful sale.| A sale of a given quantity reduces the corresponding stock by exactly that quantity. The system rejects a sale exceeding available stock.
FR-14| The system shall generate reports showing sales and available inventory for a selected period.| A user can select a date range and generate a report containing the matching records and totals.

3. Non-Functional Requirements

Non-functional requirements describe the quality and performance expected from the system.

ID| Requirement| Measurable Fit Criterion
NFR-01| The system shall display its main pages within 3 seconds under normal operating conditions.| Each main page loads within 3 seconds in at least 9 out of 10 test attempts on the agreed test environment.
NFR-02| The system shall require users to authenticate before accessing protected functions.| An unauthenticated user attempting to access a protected page is redirected to the login page.
NFR-03| The system shall restrict access to functions according to assigned user roles.| A user cannot access or perform an operation outside their assigned permissions in role-based access tests.
NFR-04| The system shall validate required form fields and reject invalid quantities and prices.| Empty required fields, negative quantities and negative prices are rejected with clear error messages.
NFR-05| The system shall provide a consistent and easy-to-understand interface.| At least 4 out of 5 representative test users can complete the basic tasks of recording a sale and viewing stock without assistance.
NFR-06| The system shall maintain accurate inventory records when production, harvesting, mortality and sales transactions are recorded.| In a set of 20 test transactions, all resulting stock quantities match the expected calculated quantities.
NFR-07| The system shall support backup and restoration of its database.| A database backup can be created and restored successfully, with all records from the backup available after restoration.

4. Requirement Priorities

The initial priorities are as follows:

- High: User authentication, product management, raw material management, production recording, fish inventory, sales recording and stock updates.
- Medium: Fish mortality records, reports, user account management and database backup.
- Low: Additional interface improvements and advanced reporting features.

5. Assumptions and Constraints

- The system will initially support one business location.
- Users will access the system through a web browser.
- The system will use PHP, MySQL, HTML, CSS and JavaScript.
- Stock quantities will be entered and updated by authorized users.
- Internet-based payments and online ordering are outside the initial project scope.

6. Conclusion

These requirements define the main functions and quality expectations of the proposed JAOF FOODS Stock and Sales Tracker. They will guide the system design, implementation and testing.
REQUIREMENTS TRACEABILITY MATRIX

JAOF FOODS – Small Shop Stock and Sales Tracker

1. Introduction

The Requirements Traceability Matrix (RTM) establishes a relationship between the functional requirements, user stories and use cases of the JAOF FOODS system. It helps ensure that all identified requirements are considered during system design, development and testing.

2. Traceability Matrix

Requirement ID| Requirement Description| User Story ID| Use Case ID| Priority
FR-01| User login| US-01| UC-01, UC-02| High
FR-02| Manage user accounts| US-02| UC-01, UC-02| High
FR-03| Manage products| US-03| UC-01, UC-02| High
FR-04| Record raw materials| US-04| UC-02| High
FR-05| Update raw material quantities| US-05| UC-02| High
FR-06| Record food production| US-06| UC-02| High
FR-07| Update finished-product stock after production| US-06, US-12| UC-02| High
FR-08| Record fish stocking| US-07| —| High
FR-09| Record fish mortality| US-08| —| High
FR-10| Record fish harvesting| US-09| —| High
FR-11| Separate fresh and smoked fish inventory| US-10| UC-01| High
FR-12| Record sales| US-11| UC-01| High
FR-13| Update inventory after sales and prevent overselling| US-11, US-12| UC-01| High
FR-14| Generate sales and inventory reports| US-13, US-14| —| Medium

3. Non-Functional Requirements Traceability

Requirement ID| Requirement Description| Verification Method
NFR-01| System pages should load within 3 seconds under normal conditions.| Performance testing
NFR-02| Protected functions must require authentication.| Security testing
NFR-03| Users should only access functions permitted for their roles.| Access-control testing
NFR-04| The system must validate required fields and reject invalid quantities and prices.| Input validation testing
NFR-05| The interface should be easy to understand and use.| Usability testing
NFR-06| Inventory quantities must remain accurate after transactions.| Inventory testing
NFR-07| The system should support database backup and restoration.| Backup and recovery testing

4. Traceability Summary

The matrix connects the functional requirements to the user stories and use cases. It also identifies how the non-functional requirements will be verified.

Some requirements, such as fish stocking, mortality and harvesting, are not fully represented by the two detailed use cases in this document. They will be covered during system design and testing.

5. Conclusion

The Requirements Traceability Matrix provides a clear link between the identified system requirements and the planned system functions. It will help guide implementation and ensure that the important requirements of JAOF FOODS are addressed.
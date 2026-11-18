USER STORIES AND ACCEPTANCE CRITERIA

JAOF FOODS – Small Shop Stock and Sales Tracker

US-01: User Login

User Story: As an authorized user, I want to log into the system so that I can access the functions permitted for my role.

Acceptance Criteria:

- The system accepts a valid username and password.
- Invalid login details are rejected.
- The user is redirected to the appropriate dashboard after successful login.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-02: Manage User Accounts

User Story: As an administrator, I want to create and manage user accounts so that only authorized people can use the system.

Acceptance Criteria:

- The administrator can create a user account.
- The administrator can update user details.
- The administrator can deactivate an account.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-03: Manage Products

User Story: As an administrator, I want to add and update products so that the system contains accurate product information.

Acceptance Criteria:

- The administrator can add a product name and description.
- The administrator can view and update product details.
- The system stores the product information.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-04: Record Raw Materials

User Story: As a production worker, I want to record raw materials so that the business can monitor the materials used in production.

Acceptance Criteria:

- The worker can enter a material name and quantity.
- The system saves the material record.
- The worker can view recorded materials.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-05: Update Raw Material Stock

User Story: As a production worker, I want to update raw material quantities when materials are received or used so that the available quantities remain accurate.

Acceptance Criteria:

- The system allows received quantities to be added.
- The system deducts quantities used in production.
- The system prevents negative stock quantities.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-06: Record Food Production

User Story: As a laboratory worker, I want to record food production so that the business can track the quantities manufactured.

Acceptance Criteria:

- The worker can select a product.
- The worker can enter the quantity produced and production date.
- The system saves the production record.
- Finished-product stock increases after production is recorded.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-07: Record Fish Stocking

User Story: As a fish pond worker, I want to record the number of fish introduced into the pond so that the business can monitor fish population.

Acceptance Criteria:

- The worker can enter the stocking date and number of fish.
- The system saves the stocking record.
- The pond stock increases by the recorded quantity.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-08: Record Fish Mortality

User Story: As a fish pond worker, I want to record fish deaths so that the system reflects the actual number of fish remaining in the pond.

Acceptance Criteria:

- The worker can enter the date and number of fish that died.
- The system saves the mortality record.
- The system reduces the pond population accordingly.
- The system does not allow mortality quantities greater than the recorded pond population.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-09: Record Fish Harvesting

User Story: As a fish pond worker, I want to record harvested fish so that the business can monitor fish removed from the pond.

Acceptance Criteria:

- The worker can enter the harvest date and quantity.
- The system saves the harvest record.
- The system reduces the pond population.
- The harvested quantity is recorded for inventory processing.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-10: Manage Fresh and Smoked Fish

User Story: As a fish sales recorder, I want to distinguish fresh fish from smoked fish so that I can monitor the stock of each type separately.

Acceptance Criteria:

- The system identifies fresh and smoked fish separately.
- The user can view the available quantity of each type.
- Changes to one type do not incorrectly change the other type's stock.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-11: Record Fish and Product Sales

User Story: As a sales recorder, I want to record sales so that the business can keep accurate records of products sold and money received.

Acceptance Criteria:

- The user can select a product and enter the quantity sold.
- The user can enter the unit selling price.
- The system calculates the total amount.
- The system saves the sale with its date.
- The system rejects sales that exceed available stock.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-12: Update Finished Product Inventory

User Story: As a shop attendant, I want finished-product stock to be updated after production and sales so that I can know the quantity available for sale.

Acceptance Criteria:

- Completed production increases finished-product stock.
- Recorded sales reduce finished-product stock.
- The system displays the updated quantity.

MoSCoW Priority: Must Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-13: View Inventory Reports

User Story: As the business owner, I want to view inventory reports so that I can monitor available raw materials, finished products and fish stock.

Acceptance Criteria:

- The owner can view current stock quantities.
- The owner can identify low or insufficient stock.
- The system displays inventory information clearly.

MoSCoW Priority: Should Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

US-14: View Sales Reports

User Story: As the business owner, I want to generate sales reports for a selected period so that I can monitor business performance.

Acceptance Criteria:

- The owner can select a reporting period.
- The system displays sales within that period.
- The system calculates the total sales amount.
- The report can be viewed on the system.

MoSCoW Priority: Should Have
INVEST Check: Independent: Yes | Negotiable: Yes | Valuable: Yes | Estimable: Yes | Small: Yes | Testable: Yes.

---

MoSCoW Priority Summary

- Must Have: Essential functions required for the system to operate.
- Should Have: Important functions that improve monitoring and decision-making.
- Could Have: Useful functions that can be added if time permits.
- Won't Have: Functions excluded from the current project version.

INVEST Summary

The user stories are designed to be independent where possible, negotiable, valuable to users, estimable, small enough to implement and testable through their acceptance criteria.
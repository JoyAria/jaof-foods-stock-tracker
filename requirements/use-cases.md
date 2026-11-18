USE CASE SPECIFICATIONS

JAOF FOODS – Small Shop Stock and Sales Tracker

Use Case 1: Record Fish Sale

Item| Description
Use Case ID| UC-01
Use Case Name| Record Fish Sale
Primary Actor| Fish Sales Recorder
Supporting Actor| Customer
Goal| To record the sale of fresh or smoked fish and update the available stock.
Priority| High

Preconditions

- The user must be logged into the system.
- The user must have permission to record sales.
- The selected fish product must exist in the inventory.
- There must be sufficient stock available.

Main Success Scenario

1. The fish sales recorder opens the sales section.
2. The system displays the available products.
3. The recorder selects either fresh fish or smoked fish.
4. The recorder enters the quantity sold.
5. The recorder enters or confirms the unit selling price.
6. The system checks whether sufficient stock is available.
7. The system calculates the total sale amount.
8. The recorder confirms the transaction.
9. The system saves the sale record.
10. The system deducts the quantity sold from the available stock.
11. The system displays a successful sale confirmation.

Alternative Flows

- A1: Insufficient stock: If the requested quantity exceeds available stock, the system displays an error and does not save the sale.
- A2: Invalid quantity: If the entered quantity is zero, negative or invalid, the system requests a valid quantity.
- A3: Missing information: If required information is missing, the system asks the user to complete the required fields.

Postconditions

- The sale is stored in the database.
- The available stock is updated.
- The sale can be included in sales reports.

---

Use Case 2: Record Food Production

Item| Description
Use Case ID| UC-02
Use Case Name| Record Food Production
Primary Actor| Production / Laboratory Worker
Supporting Actor| Business Owner / Manager
Goal| To record the production of food products and update raw material and finished product quantities.
Priority| High

Preconditions

- The production worker must be logged into the system.
- The worker must have permission to record production.
- The product must exist in the product records.
- The required raw materials must be registered in the inventory.
- Sufficient raw materials must be available.

Main Success Scenario

1. The production worker opens the production section.
2. The system displays the available food products.
3. The worker selects the product to be manufactured.
4. The worker enters the quantity to be produced.
5. The worker selects or enters the raw materials used.
6. The worker enters the quantity of each raw material consumed.
7. The system checks whether sufficient raw materials are available.
8. The worker confirms the production record.
9. The system saves the production details.
10. The system deducts the materials used from raw material inventory.
11. The system adds the quantity produced to finished-product inventory.
12. The system displays a production confirmation.

Alternative Flows

- A1: Insufficient raw materials: The system displays a warning and prevents the production record from being completed.
- A2: Invalid production quantity: The system rejects zero, negative or invalid quantities.
- A3: Missing production details: The system requests the missing information before saving.
- A4: Production cancelled: The worker can cancel the operation before confirming it, and no inventory changes are made.

Postconditions

- The production record is stored in the database.
- The quantities of raw materials used are deducted from inventory.
- Finished-product stock is increased.
- The production record is available for future reporting.

---

Summary

The two use cases describe important operations of the JAOF FOODS system. The first covers fish sales and stock updates, while the second covers food production and inventory updates.
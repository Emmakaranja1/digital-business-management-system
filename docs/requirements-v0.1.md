# Digital Business Management System

## Project Scope & Requirements

**Requirements Version:** v0.1

**Business Location:** Nairobi, Kenya.


**Prepared By:** Developer

---

# 1. Introduction

This document explains the proposed Digital Business Management System that will be developed to help transform the current manual business management process into a more organized, accurate, and reliable digital system.

The purpose of this document is to ensure that both the business owner and developer have a clear understanding of:

- The current business challenges.
- The problems the system will solve.
- The expected system features.
- How the system will operate.
- The information required before development begins.

This document is not a pricing agreement. The purpose is to confirm that the proposed solution correctly represents the needs of the business before discussing development costs and timelines.

---

# 2. Current Business Situation

The business currently operates using manual methods such as:

- Writing sales records in notebooks.
- Remembering stock levels from experience.
- Manually calculating profits.
- Tracking customer debts manually.
- Managing suppliers without a centralized record.
- Calculating daily performance manually.

While these methods may work for a small business, they become difficult as the business grows because information can easily be lost, forgotten, or incorrectly calculated.

The proposed system will help move the business from depending on memory and manual records to using organized digital information.

---

# 3. Problems Identified

## 3.1 Sales Management Challenges

Currently:

- Daily sales are not automatically recorded.
- It is difficult to know exact daily income.
- Cash, M-Pesa, and credit sales are difficult to separate.
- Manual calculations may cause mistakes.
- End-of-day sales summaries take time.

The system will provide a digital sales recording process where every transaction is stored.

---

## 3.2 Financial Management Challenges

Currently:

- Business money and personal money may mix.
- Profit is difficult to calculate accurately.
- Expenses are not always categorized.
- It is difficult to know where money is being spent.

The system will help separate:

- Business income.
- Business expenses.
- Personal withdrawals.
- Restocking money.
- Estimated profit.

---

## 3.3 Stock Management Challenges

Currently:

- Stock levels are estimated manually.
- Products may run out without warning.
- Some products may stay too long without selling.
- It is difficult to know which products perform best.

The system will provide accurate stock tracking.

---

## 3.4 Customer Credit Challenges

Currently:

- Customers who take goods on credit are recorded manually.
- Some debts may be forgotten.
- Payment history is difficult to follow.

The system will provide proper customer debt management.

---

## 3.5 Supplier Management Challenges

Currently:

- Supplier information is not centralized.
- Previous purchases are difficult to trace.
- It is difficult to know how much was bought from each supplier.

The system will maintain supplier records and purchase history.

---

# 4. Proposed Solution

A Digital Business Management System will be developed to act as a business assistant that helps the owner manage:

- Products.
- Sales.
- Stock.
- Suppliers.
- Customers.
- Expenses.
- Payments.
- Reports.

The system will be designed according to the actual operations of the shop.

---

# 5. User Roles and Access Control

The system will support different users with different permissions.

## 5.1 Business Owner / Administrator

The owner will be able to:

- View all business information.
- View reports.
- Manage products.
- Manage suppliers.
- Manage employees.
- View profits.
- Review sales.
- Monitor stock.
- Approve important changes.

---

## 5.2 Cashier / Shop Attendant

The cashier will have limited access.

The cashier will be able to:

- Record sales.
- Receive customer payments.
- Record customer credit sales where allowed.
- View available products.

The cashier will not access sensitive information such as:

- Business profit.
- Full financial reports.
- System settings.

---

## 5.3 Stock Receiver

A stock receiver can:

- Record delivered stock.
- Select supplier.
- Enter products received.
- Enter quantities.
- Record purchase information.

Example:

**Supplier:**

Brookside

**Delivery:**

- Milk - 50 packets
- Mala - 20 packets

The owner will immediately see the delivery record.

---

# 6. System Features

## A. Product Management

The system will allow the owner to create and manage products.

Each product will contain:

- Product name.
- Category.
- Supplier information.
- Buying price.
- Selling price.
- Current stock.
- Stock unit.
- Selling unit.

Examples:

### Milk

Purchased:

- 20 litres

Sold:

- KSh 20 portion.
- KSh 50 portion.
- KSh 100 portion.

### Cooking Oil

Purchased:

- 20 litre container

Sold:

- 100 ml.
- 250 ml.
- KSh 20 portion.
- KSh 50 portion.

The system will support different measurements depending on how the business sells products.

---

## B. Product Measurement and Portion Management

Because the business sells some products in small portions, the system will support measurement conversions.

During setup, the following information will be collected:

- How the product is purchased.
- How the product is measured.
- Selling portions used.
- Quantity contained in one purchase unit.
- Profit calculation method.

### Example: Cooking Oil

Purchase:

- 20 litres

Questions captured:

- How many ml are given for KSh 20?
- How many ml are given for KSh 50?

The system will calculate:

- Quantity sold.
- Remaining stock.
- Cost of goods sold.
- Profit.

### Example: Sugar

Purchase:

- 50 kg bag

The system will calculate:

- Weight sold.
- Cost per portion.
- Selling price.
- Profit.

### Example: Bar Soap

Purchase:

- Carton of 48 pieces.

The system will calculate:

- Cost per bar.
- Selling price.
- Profit per bar.

---

## C. Sales Management System

Every sale will be recorded digitally.

### Sales Process

1. Cashier selects product.
2. Cashier enters quantity.
3. System automatically displays price.
4. System calculates total bill.
5. Customer payment method is selected.

### Payment Options

- Cash.
- M-Pesa.
- Credit.

The system will automatically:

- Reduce stock.
- Record the sale.
- Calculate estimated profit.
- Update reports.

---

## D. Cash Payment and Change Calculation

For cash payments:

The system will calculate customer change.

### Example

**Bill:**

KSh 180

**Customer gives:**

KSh 1,000

**System displays:**

Change:

KSh 820

This reduces calculation mistakes.

---

## E. Sales Correction and Audit Records

Before completing a sale:

The cashier can:

- Remove items.
- Correct quantities.
- Cancel unfinished transactions.

After completing a sale:

Only authorized users can:

- Reverse transactions.
- Edit records.

The system will keep records of:

- Who made changes.
- What was changed.
- When it happened.

---

## F. Inventory Management

The system will automatically track:

- Available stock.
- Stock received.
- Stock sold.
- Low stock products.
- Out-of-stock products.
- Fast-moving products.
- Slow-moving products.

---

## G. Supplier Management

The system will store:

- Supplier name.
- Phone number.
- Products supplied.
- Purchase history.
- Payments made.
- Outstanding balances.

---

## H. Customer Credit Management

The system will record:

- Customer name.
- Phone number.
- Items taken.
- Amount owed.
- Payments made.
- Remaining balance.

---

## I. Expense Management

The owner will record business expenses such as:

- Stock purchases.
- Rent.
- Electricity.
- Water.
- Transport.
- Internet.
- Airtime.
- Repairs.
- Salaries.
- Personal withdrawals.

Each expense will contain:

- Category.
- Description.
- Amount.
- Date.

---

## J. M-Pesa Management

The system will record:

- M-Pesa customer payments.
- Agent deposits.
- Agent withdrawals.

This will help separate different M-Pesa activities.

---

## K. Reports and Dashboard

The owner dashboard will provide business information.

### Daily Reports

The system will show:

- Total sales.
- Cash sales.
- M-Pesa sales.
- Credit sales.
- Expenses.
- Products sold.
- Stock remaining.

### Monthly Reports

The system will show:

- Total sales.
- Total expenses.
- Estimated profit.
- Stock purchases.
- Customer debts.
- Credit payments.
- Best-selling products.
- Slow-moving products.

---

## L. Cash Drawer Reconciliation

At the end of the day, the system will help compare:

**Expected cash:**

Based on recorded transactions

Against:

**Actual cash counted.**

### Example

**Expected:**

KSh 8,350

**Actual:**

KSh 8,250

**Difference:**

KSh -100

This helps identify:

- Missing transactions.
- Calculation mistakes.
- Cash shortages.

---

# 7. Information Required From Business Owner

Before development begins, the owner will provide:

## Products

- Product names.
- Buying prices.
- Selling prices.
- Measurements used.
- Portion sizes.

## Suppliers

- Supplier names.
- Contacts.
- Products supplied.

## Customers

- Credit customers.
- Existing balances.

## Business Expenses

- Common expenses.
- Monthly costs.

## Business Rules

Information about how the business currently operates.

---

# 8. Expected Benefits

The system will help the business owner:

- Reduce dependence on memory.
- Keep safer records.
- Know actual business performance.
- Control stock better.
- Reduce losses.
- Track customer debts.
- Understand profits.
- Make better purchasing decisions.
- Prepare the business for future growth.

---

# 9. Scope Approval

By signing below, both parties confirm that:

- The business challenges have been correctly identified.
- The proposed system features represent the required solution.
- Additional features can be discussed separately.
- Development cost will be discussed after this scope approval.



# Purpose of the System

The purpose of this system is not only to digitize records but to provide the business owner with better control, accurate information, and tools to support business growth.

This system will transform business operations from relying on memory and manual records into using organized information for better decisions.
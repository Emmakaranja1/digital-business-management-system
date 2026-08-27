# Business Problem

**Project:** Digital Business Management System

**Version:** 0.1

**Reference Business:** Small Retail Business, Nairobi, Kenya.

---

# 1. Business Context

The reference business is a small retail business operating in Nairobi, Kenya.

The business currently relies heavily on manual processes and records to manage sales, stock, customers, suppliers, expenses and financial information.

The purpose of this project is to understand these real-world business operations and develop a digital system that reduces manual work, improves record keeping and gives the business owner better visibility into the business.

The reference business will be used to guide the initial product design.

The resulting system should not be hard-coded for one business. It should eventually be configurable and reusable for other small retail businesses with similar needs.

---

# 2. Problems Identified

## 2.1 Manual Sales Recording

Sales are currently recorded manually.

This creates problems such as:

- Difficulty determining exact daily sales.
- Risk of incorrect calculations.
- Difficulty separating different payment methods.
- Difficulty reviewing historical transactions.
- Time spent manually preparing summaries.

---

## 2.2 Cash, M-Pesa and Credit Are Not Easily Separated

The business receives money through different channels:

- Cash.
- M-Pesa.
- Credit.

The business needs to know how much was received through each method.

Without structured records, reconciliation becomes difficult.

---

## 2.3 Customer Credit / Debts

Some customers may take goods and pay later.

The business therefore needs to know:

- Who owes money.
- What the customer took.
- How much the customer owes.
- How much the customer has paid.
- What balance remains.
- When payments were made.

Customer credit must therefore be treated as a core business process rather than simply another payment option.

---

## 2.4 Manual Stock Tracking

Stock is currently difficult to monitor accurately.

The business needs to know:

- What products are currently available.
- How much stock was received.
- How much stock was sold.
- Which products are running low.
- Which products are out of stock.
- Which products sell quickly.
- Which products move slowly.

---

## 2.5 Products Sold in Different Units and Portions

Some products may be purchased in bulk and sold in smaller portions.

Examples include:

- Cooking oil.
- Sugar.
- Bar soap.

A product may therefore have:

- A purchasing unit.
- A base measurement.
- A selling unit.
- One or more selling portions.

The system must be designed to support these real business operations.

The exact conversion values must come from the business.

---

## 2.6 Supplier Management

The business needs to maintain information about suppliers.

The system should help answer:

- Who supplied a product?
- What products were purchased?
- When was stock received?
- How much was purchased?
- How much was paid?
- Is there an outstanding supplier balance?

---

## 2.7 Expense and Business Money Tracking

The business incurs operating expenses that need to be recorded and categorized.

Examples include:

- Rent.
- Electricity.
- Water.
- Transport.
- Internet.
- Airtime.
- Repairs.
- Salaries.
- Other legitimate business operating expenses.

The system should allow the owner to record business expenses with:

- Expense category.
- Description.
- Amount.
- Date.
- Payment method.

Business expenses must be distinguished from other movements of business money.

### Owner Withdrawals

The owner may withdraw money from the business for personal use.

The system may record an owner withdrawal as a business cash movement so that the business cash position and reconciliation remain accurate.

The system does not need to record what the owner spends the withdrawn money on.

Example:

Owner withdraws KSh 1,000 from the business.

The system records:

```text
Type: Owner Withdrawal
Amount: KSh 1,000
Date: [date]

## 2.8 Profit Visibility

The owner needs better visibility into business performance.

The system should help provide information about:

- Sales.
- Expenses.
- Cost of stock.
- Estimated profit.
- Best-selling products.
- Slow-moving products.

Profit figures must be based on clearly defined business rules rather than assumptions.

---

## 2.9 End-of-Day Reconciliation

At the end of the business day, the owner needs to compare recorded transactions against actual money available.

The system should support comparison between:

- Expected cash.
- Actual cash counted.
- Difference.

This can help identify:

- Missing transactions.
- Calculation errors.
- Cash shortages.

---

## 2.10 Lack of Centralized Business Information

Business information is spread across manual records and memory.

The system should provide one organized source of information for:

- Products.
- Inventory.
- Sales.
- Payments.
- Customers.
- Credit.
- Suppliers.
- Purchases.
- Expenses.
- Reports.

---

# 3. Desired Business Outcome

The goal is not simply to replace a notebook with a computer screen.

The system should help the business owner answer questions such as:

> How much did I sell today?

> How much was received in cash?

> How much was received through M-Pesa?

> How much was sold on credit?

> Which customers owe me money?

> How much does each customer owe?

> What stock do I currently have?

> What products are running low?

> What did I purchase from suppliers?

> How much did I spend?

> How much money should be in the cash drawer?

> Is the actual cash equal to the expected cash?

> Which products are selling well?

> What is my estimated business performance?

---

# 4. Proposed Solution

The proposed solution is a digital retail business management platform that centralizes the core business operations.

The initial system will cover:

- User management.
- Product management.
- Inventory management.
- Sales management.
- Payment management.
- Customer management.
- Customer credit management.
- Supplier management.
- Purchases.
- Expense management.
- M-Pesa records.
- Reporting.
- Cash reconciliation.
- Audit records.

---

# 5. Core Business Flow

The initial business flow can be represented as:

```text
SUPPLIER
   |
   v
PURCHASE / STOCK RECEIVING
   |
   v
INVENTORY
   |
   v
PRODUCT
   |
   v
SALE
   |
   +----------------+
   |                |
   v                v
PAYMENT          CUSTOMER CREDIT
   |                |
   |                v
   |          OUTSTANDING BALANCE
   |                |
   |                v
   |          CREDIT PAYMENT
   |
   v
REPORTING


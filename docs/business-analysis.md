# Business Analysis

**Project:** Digital Business Management System

**Analysis Version:** 0.1

**Source:** requirements-v0.1

**Status:** Initial analysis

---

# 1. Purpose

This document analyzes the business operations described in the approved requirements document.

The purpose is to understand how the business currently operates, identify the major business processes, identify the people involved, and establish the foundation for designing the software system.

This document is an analysis of the requirements. It does not replace the original requirements document.

---

# 2. Business Problem

The business currently depends heavily on manual processes.

The requirements identify the following challenges:

- Sales are recorded manually.
- Stock levels are estimated manually.
- Profits are calculated manually.
- Customer credit is tracked manually.
- Supplier information is not centralized.
- Business and personal money may mix.
- Expenses may not always be categorized.
- Daily business performance is difficult to determine.

The proposed system is intended to move the business from relying on memory and manual records toward organized digital information.

---

# 3. Business Actors

## 3.1 Business Owner / Administrator

The Business Owner is responsible for managing and overseeing the business.

The requirements indicate that the owner needs access to:

- Business information.
- Reports.
- Products.
- Suppliers.
- Employees.
- Profits.
- Sales.
- Stock.
- Important changes.

The owner also approves important changes.

---

## 3.2 Cashier / Shop Attendant

The Cashier interacts with customers and records sales.

The requirements indicate that the cashier can:

- Record sales.
- Receive customer payments.
- Record customer credit sales where allowed.
- View available products.

The cashier should not have access to:

- Business profit.
- Full financial reports.
- System settings.

---

## 3.3 Stock Receiver

The Stock Receiver handles delivered stock.

The requirements indicate that the stock receiver can:

- Record delivered stock.
- Select a supplier.
- Enter products received.
- Enter quantities.
- Record purchase information.

---

# 4. Core Business Processes

## 4.1 Product Setup

The business needs to maintain product information including:

- Product name.
- Category.
- Supplier information.
- Buying price.
- Selling price.
- Current stock.
- Stock unit.
- Selling unit.

Some products may be purchased in one measurement and sold using another measurement or portion.

---

## 4.2 Product Measurement and Portion Management

Some products are purchased in bulk and sold in smaller portions.

Examples identified in the requirements include:

- Cooking oil purchased in litres and sold in millilitres or monetary portions.
- Sugar purchased in kilograms and sold in portions.
- Bar soap purchased by carton and sold by individual piece.

The system therefore needs to represent the relationship between the purchase quantity and the selling quantity.

The exact conversion rules must come from the business.

---

## 4.3 Stock Receiving

When stock is delivered:

```text
Supplier
    ↓
Delivery
    ↓
Products received
    ↓
Quantities recorded
    ↓
Inventory updated
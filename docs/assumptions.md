# Assumptions

**Project:** Digital Business Management System

**Version:** 0.1

**Purpose:** Record information that has not yet been confirmed by the business owner.

---

# 1. Purpose of This Document

This document records assumptions made during analysis of the reference retail business.

An assumption is information that is currently unknown, incomplete, or not yet confirmed by the business owner but may affect the design of the system.

Assumptions must not automatically be treated as confirmed business requirements.

Before production deployment for a real client, important assumptions should be validated with the business owner.

---

# 2. Assumption Status

The following statuses are used:

- **To Be Validated** — The information has not yet been confirmed.
- **Confirmed** — The business owner has confirmed the information.
- **Rejected** — The assumption has been determined to be incorrect.
- **Converted to Requirement** — The assumption has been confirmed and formally added to the requirements.
- **Converted to Decision** — The assumption has resulted in a technical or product decision.

---

# 3. Business Assumptions

## ASSUMPTION-001 — Products May Be Sold in Portions

**Statement:**

The business may purchase products in bulk and sell them to customers in smaller portions.

**Status:** To Be Validated

**Reason:**

The original requirements indicate that the business sells some products in portions.

**Impact:**

The inventory and product models may need to support different purchasing and selling units.

---

## ASSUMPTION-002 — Product Measurements Are Important

**Statement:**

Some products may require measurements such as kilograms, grams, litres, millilitres, pieces, packets, or other units.

**Status:** To Be Validated

**Reason:**

The original project discussion indicated that measurements and product quantities would need to be collected from the business.

**Impact:**

Incorrect assumptions about measurements could result in incorrect inventory calculations.

---

## ASSUMPTION-003 — Product Conversion Rules Vary by Product

**Statement:**

Different products may have different relationships between their purchasing unit and selling unit.

**Status:** To Be Validated

**Reason:**

A product purchased in bulk may be sold in smaller portions.

**Impact:**

The inventory system should not assume one universal conversion rule for every product.

---

## ASSUMPTION-004 — Customers Can Purchase on Credit

**Statement:**

The business allows some customers to receive goods and pay at a later time.

**Status:** To Be Validated

**Reason:**

Customer credit was identified as one of the business requirements.

**Impact:**

The system needs to support credit sales and outstanding customer balances.

---

## ASSUMPTION-005 — Customers Can Make Partial Credit Payments

**Statement:**

A customer may pay part of an outstanding credit balance instead of paying the entire balance at once.

**Status:** To Be Validated

**Reason:**

The exact credit repayment process was not fully documented.

**Impact:**

The credit model may need to support multiple payments against a single outstanding balance.

---

## ASSUMPTION-006 — A Customer May Have Multiple Credit Transactions

**Statement:**

A customer may make more than one credit purchase over time.

**Status:** To Be Validated

**Reason:**

The business may allow customers to continue purchasing while they have existing balances.

**Impact:**

The system should potentially maintain a transaction history rather than storing only one credit amount.

---

## ASSUMPTION-007 — Cash, M-Pesa and Credit Are Separate Payment Methods

**Statement:**

Sales can be paid using cash, M-Pesa, or credit.

**Status:** To Be Validated

**Reason:**

These payment methods were identified during the original business analysis.

**Impact:**

Sales and reporting should distinguish between the different payment methods.

---

## ASSUMPTION-008 — A Sale May Potentially Use More Than One Payment Method

**Statement:**

A customer may potentially pay for one sale using a combination of payment methods.

Example:

```text
Total Sale: KSh 500

Cash: KSh 200
M-Pesa: KSh 300
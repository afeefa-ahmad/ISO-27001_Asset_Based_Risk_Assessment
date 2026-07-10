# Company Overview

## 1. About the company

Trailhead Supply Co. is a small online retailer that sells outdoor and camping
gear directly to consumers. Customers browse and buy through the company's own
website, and orders are picked, packed, and shipped from a single fulfillment
warehouse. The company has grown quickly into a business of around 50 people, but
it still runs lean, with small teams and a lot of shared responsibility.

This document is a plain introduction to the business. The formal context of the
organization, meaning its internal and external issues and its interested parties,
is covered in `organizational-context.md`. The boundary of the assessment is
defined in `scope-of-isms.md`.

 *** Note: Trailhead Supply Co. is a fictional company created for this project. All
     details are illustrative and exist to demonstrate ISO 27001 methodology. ***

## 2. What the business does

At its core, the business is straightforward. It buys outdoor gear from suppliers,
lists it on its website, sells it to customers, and ships it out. The money is
made online, so the website and the systems behind it are the heart of the
company. If the store goes down, sales stop, and if customer data is exposed,
trust is lost. That simple reality is what makes information security matter here.

The main activities are:

- Selling products through the online store
- Taking and processing customer orders
- Shipping orders from the warehouse
- Supporting customers with questions, returns, and refunds
- Marketing to customers through email and the website

## 3. How the company operates day to day

A customer visits the website, creates an account or checks out as a guest, places
an order, and pays. Payment is handled by an outside provider, so Trailhead never
stores full card details itself. The order then flows to the fulfillment team in
the warehouse, who pick, pack, and ship it. Customer support handles anything that
comes up along the way, from delivery questions to returns. Behind all of this, a
small software and IT team keeps the website and the company's systems running.

## 4. The technology behind it

For a company its size, Trailhead relies on a compact set of systems.

| System | What it is used for |
|---|---|
| The online store | The company's website, where customers browse and buy, holding their accounts and orders |
| Order and fulfillment tools | The tools that track an order from purchase through to packing and shipping |
| Customer and support tool | The tool used to keep customer records and handle support |
| HR and payroll tool | The tool that holds employee records, such as personal details, contracts, and pay information | 
| Email and office tools | The company's email, along with the file storage and documents where staff keep shared files such as reports, plans, and supplier details, and the internal messaging they use day to day |
| Staff login system | The system that manages staff logins, letting each person sign in once to reach the systems they need |

Most of the company's important data and processes live in or pass through these
systems, which is why they form the core of what the assessment looks at.

## 5. The information the company handles

Trailhead holds a modest but sensitive set of information. The most important is
customer personal data, since that is what customers trust the company with and
what would cause the most harm if exposed.

- Customer personal data, such as names, addresses, emails, and phone numbers
- Order and transaction history
- Employee records held for running the business
- Business information such as supplier details and internal reports

## 6. The people

Trailhead is small enough that people often cover more than one role, and in some
areas a single person handles both IT and security. Because who does what
determines who should own each asset and each control later in the assessment, the
team is described in its own dedicated file rather than here.

See `organization-and-roles.md` for the full breakdown of teams, what they do, and
the systems and data each one works with.

## 7. Why this company suits an ISO 27001 assessment

Trailhead is a useful subject for a risk assessment because it is small enough to
understand fully, yet it has all the ingredients that make information security
real: sensitive customer data, a revenue stream that depends entirely on an online
platform staying available, several connected systems and services, and a small
team stretched across many responsibilities. Those are exactly the conditions
where an ISO 27001 assessment adds value, which makes the company a realistic and
instructive example to work through.

---
Prepared by Afeefa Ahmad. GRC portfolio project, fictional scenario for
demonstration purposes.

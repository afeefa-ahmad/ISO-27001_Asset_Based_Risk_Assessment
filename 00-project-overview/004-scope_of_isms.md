# Scope of the ISMS

## 1. What this document covers

This document defines the boundary of the Information Security Management System
(ISMS) for Trailhead Supply Co. It states which systems, processes, information,
and locations fall inside the ISMS, and which sit outside it.

The boundary is the reference point for everything that follows in the assessment.
Under ISO/IEC 27001:2022 Clause 4.3, the organization determines the boundaries
and applicability of its ISMS to establish its scope. In doing so, the clause
requires three things to be considered: the internal and external issues from
Clause 4.1, the requirements of interested parties from Clause 4.2, and the
interfaces and dependencies between the activities the organization performs
itself and those performed by other organizations. Each of these is reflected
below.

The context this boundary is built on is in `organizational-context.md`. The plain
introduction to the company is in `company-overview.md`.

> Note: Trailhead Supply Co. is a fictional company created for this project. All
> details are illustrative and exist to demonstrate ISO 27001 methodology.

## 2. Scope statement

> The ISMS covers the systems and processes behind Trailhead Supply Co.'s online
> store: the website customers buy from, the systems that process and ship their
> orders, the customer and order data involved, and the supporting corporate IT
> that staff use to run the business, including identity and access, email, and
> work devices.

Everything assessed in this project sits inside that statement. The sections below
break it down into specific systems, processes, information, and locations, and
set out the interfaces and dependencies with other organizations.

## 3. Systems in scope

- The online store and the cloud infrastructure that runs it
- The order management and fulfilment tools
- The customer and support tool
- The HR and payroll tool
- Email and office tools, including file storage and internal messaging
- The staff login system that manages access to company systems
- Employee laptops and mobile devices enrolled in company management

## 4. Processes in scope

- Customer account registration and login
- Browsing the store and placing orders
- Sharing payment details securely with the payment provider at checkout
- Processing, fulfilling, and shipping orders, including sharing delivery details with the shipping provider
- Handling customer support, returns, and refunds
- Granting, changing, and removing staff access to systems
- Sharing customer contact details with the email marketing provider and managing that relationship

## 5. Information in scope

- Customer personal data, such as names, addresses, emails, and phone numbers
- Order and transaction history
- Employee records held for running the business
- Business information such as supplier details and internal reports

## 6. Locations in scope

Location is part of the scope because information security is not only about
systems and data, but also about the physical places where that data is handled.
Physical and environmental security is a real part of an ISMS, and several ISO
27001 controls apply to physical spaces, such as securing offices, controlling
entry, and protecting equipment. The same customer data also carries different
risks depending on where it sits, whether in the office, in the warehouse, or on a
remote worker's device. Naming the locations in scope is what makes those physical
risks and controls relevant later in the assessment.

- The head office, where most staff work
- The fulfilment warehouse, where orders are picked, packed, and shipped
- Remote workers connecting to company systems, about a third of staff

Physical security looks different across these locations. In the office and
warehouse, Trailhead controls the space directly. For remote workers, where the
company does not control the physical space, physical security is achieved
indirectly, through device protections such as encryption and screen locks, and
through expectations around keeping devices and screens secure when working
outside the office. How this is handled in practice is examined in the risk
assessment and controls.

## 7. Interfaces and dependencies (Clause 4.3 c)

Trailhead depends on a number of outside organizations to run its business. The
ISMS boundary stops at the point where Trailhead connects to each of them: the
company is responsible for how it connects to and shares data with these
providers, while the providers are responsible for the security of their own
internal systems. These interfaces are considered when setting the scope and are
managed through vendor agreements.

| Other organization | Interface and dependency |
|---|---|
| Cloud hosting provider | Hosts the online store and supporting systems. Responsible for the security of the underlying cloud and its physical facilities. Trailhead is responsible for what it configures and runs on top of it. |
| Email and office platform provider | Provides email, file storage, office tools, and the staff login and identity service. Responsible for the security of the underlying platform. |
| Payment provider | Handles customer payments so that Trailhead does not store full card details. Responsible for securing the payment process on its own systems. |
| Shipping and logistics provider | Receives the delivery details needed to ship orders. Responsible for securing its own systems and the data shared for delivery. |
| Email marketing provider | Sends marketing emails and holds customer contact details shared for that purpose. Responsible for securing its own platform. |
| Customers | Responsible for securing their own account credentials and the devices they use to access the store. |

## 8. Out of scope

The following sit outside the boundary and are not assessed directly.

- The internal systems of the outside providers listed in Section 7. Trailhead is
  responsible only for the interface with each of them, not for the systems they
  run themselves.
- The cloud provider's underlying infrastructure and physical facilities, which
  are the provider's responsibility.
- Physical warehouse equipment with no connection to information systems, such as
  shelving and packing benches.
- Personal devices that are not enrolled in company management.

## 9. Reasoning behind the boundary

The boundary follows directly from the organizational context. The business
depends entirely on its online store and on the trust customers place in it, so
the systems, data, and processes behind the store are the core of the ISMS.
Trailhead runs some of these systems itself, which places responsibility for
securing them directly on the company, so those are firmly in scope. The parts
that sit outside, mainly the internal systems of outside providers, are better
managed through contracts and vendor reviews than by assessing infrastructure the
company cannot see or change. Drawing the line this way keeps the assessment
focused on where Trailhead can genuinely reduce its own risk.

---
*This assessment is scoped to ISO/IEC 27001 only. Other standards that could apply
to an online retailer, such as payment card handling requirements, are addressed
separately.*

*Prepared by Afeefa Ahmad. GRC portfolio project, fictional scenario for
demonstration purposes.*

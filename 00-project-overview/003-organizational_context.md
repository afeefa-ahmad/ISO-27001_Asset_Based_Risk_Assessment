# Organizational Context

## 1. What this document covers

This document establishes the context of Trailhead Supply Co. for its Information
Security Management System (ISMS). It has two parts.

The first is the set of internal and external issues that could affect the ISMS,
meaning the conditions inside the company and in the world around it that shape how
information security has to work here. The second is the set of interested parties,
meaning the people and groups who have a stake in how Trailhead handles information,
along with what each of them requires.

Together these answer a single question: what is the situation this ISMS has to fit?
This satisfies Clauses 4.1 and 4.2 of ISO/IEC 27001:2022, which ask the organization
to determine exactly these things before going further.

The plain introduction to the company is in `company-overview.md`. The boundary of the ISMS, which is set using this context, is defined in `scope-of-isms.md`.

> Note: Trailhead Supply Co. is a fictional company created for this project. All
> details are illustrative and exist to demonstrate ISO 27001 methodology.

## 2. Why this context matters

Before listing any risks or controls, an assessment has to understand the
organization it is assessing. This is what makes the work specific to Trailhead
rather than a generic checklist that could belong to any company.

It matters for a few practical reasons.

It shows what is worth protecting, and how much. Understanding that Trailhead
depends entirely on its website and on customer trust is what later justifies
rating an outage or a data breach as serious. The scores given to risks trace back
to facts established here, so they are reasoned rather than arbitrary.

It keeps the assessment realistic. Knowing that Trailhead is a small company with a
lean team and limited budget means the controls recommended later can be ones the
company could actually put in place, rather than measures built for a large
organization with a dedicated security team.

It makes decisions defensible. When a risk is judged a certain way, the reasoning
points back to something concrete about the business, such as its size, the data it
holds, or its dependence on outside services. That traceability, from a later
decision back to a documented fact about the organization, is what separates a
considered assessment from a copied one.

It accounts for what sits beyond the company's control. Identifying customers,
regulators, and outside providers shows where Trailhead's responsibility begins and
ends, which matters when reasoning about risk at the edges of the business.

ISO/IEC 27001:2022 places this understanding first, in Clauses 4.1 and 4.2, for
exactly these reasons. The sections that follow record it for Trailhead: first the
internal and external issues, then the interested parties and their requirements.

## 3. Internal and external issues (Clause 4.1)

Clause 4.1 asks the organization to identify the issues, both outside and inside
the business, that could affect whether the ISMS achieves what it is meant to.
These issues are the backdrop against which every later risk is judged.

### 3.1 External issues

These are factors in the world around Trailhead that it does not fully control but
has to account for.

| External issue | Why it matters to the ISMS |
|---|---|
| Reliance on the online channel | The business earns its revenue entirely through its website, so keeping the store available and trusted is critical to survival |
| Threat landscape for online retail | Online retailers are frequent targets for attacks such as account takeover, fraud attempts, phishing, and attacks against the website itself |
| Dependence on outside services | Core functions such as payments, shipping, and email marketing are provided by other companies, so part of the risk sits beyond Trailhead's direct control |
| Customer expectations on privacy | Customers expect their personal data to be protected, and a breach would directly damage trust and sales |
| Legal and regulatory environment | Data protection law places obligations on how customer and employee personal data is collected, stored, and used |
| Cost pressure as a small retailer | Limited budget shapes how much can be spent on security, which affects which controls are realistic |

### 3.2 Internal issues

These are factors inside Trailhead that shape how the ISMS can work in practice.

| Internal issue | Why it matters to the ISMS |
|---|---|
| Small team with shared roles | With around 50 staff, people cover several responsibilities, and the same small group handles both IT and security, which stretches capacity |
| Limited in house security expertise | There is no dedicated security team, so specialist knowledge is thin and rests on a few individuals |
| Systems the company runs itself | Trailhead operates some of its own core systems, which means the responsibility for securing and maintaining them falls directly on the company |
| Sensitive information held | Customer personal data and employee records raise the stakes of any incident |
| Fast growth from a small base | The company grew quickly, so processes and controls may lag behind the size the business has reached |
| Remote and warehouse working | About a third of staff work remotely and others work in the warehouse, so security has to cover access and devices beyond a single office |

## 4. Interested parties and their requirements (Clause 4.2)

Clause 4.2 asks the organization to identify the parties with an interest in its
information security, to state what each of them requires, and to note which of
those requirements the ISMS will address. The table below does all three.

| Interested party | What they require | Addressed by the ISMS |
|---|---|---|
| Customers | Their personal data kept private and secure, and the store available to use | Yes, through controls over data protection, access, and availability |
| Employees | Their personal data handled lawfully and kept protected | Yes, through controls over access to and handling of employee records |
| Leadership and owners | The business protected from disruption and reputational harm | Yes, this is a core driver of the ISMS |
| Suppliers and service providers | Information shared between the parties handled responsibly, and agreed security terms met | Yes, through supplier management and access controls |
| Regulators | Compliance with applicable data protection obligations | Yes, through controls that support lawful handling of personal data |
| Outside service providers used by Trailhead | Connections to their services handled securely and used as agreed | Partly, at the point of connection, since the providers' own internal systems sit outside the ISMS |

## 5. How this context shapes the ISMS

Read together, the issues and interested parties point to a clear picture. The
things most worth protecting are customer personal data and the availability of the
online store, because both sit at the centre of the business and of the trust it
depends on. At the same time, the internal issues, a small team, limited security
expertise, and cost pressure, mean the ISMS has to stay practical and focused rather
than heavy. This shapes the boundary set in the scope document, and it will shape
which risks matter most and which controls are realistic later in the assessment.

---
Prepared by Afeefa Ahmad. GRC portfolio project, fictional scenario for
demonstration purposes.

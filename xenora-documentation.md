# Xenora AI Documentation

> Consolidated plain-text export of the Xenora documentation site. Extracted from the published `.mdx` sources with all Mintlify-specific components flattened into standard Markdown.

---

## Table of contents

**Get started**
1. [Introduction](#introduction)
2. [Features](#features)
3. [Domains Supported](#domains-supported)
4. [Concepts & Glossary](#concepts--glossary)
5. [Getting Started](#getting-started)

**Work in Xenora**
6. [Dashboard](#dashboard)
7. [Entities & Clients](#entities--clients)
8. [Your workspace](#your-workspace)
9. [Pending Review](#pending-review)
10. [Custom Workflow](#custom-workflow)

**Admin & settings**
11. [General Settings](#general-settings)
12. [Teams & Roles](#teams--roles)
13. [Billing & Renewals](#billing--renewals)

**Reference**
14. [Troubleshooting](#troubleshooting)
15. [FAQ](#faq)

---

## Introduction

*Intelligent document workflow platform for professional services.*

Xenora is an intelligent AI document workflow platform for professional services firms. It automates the full document lifecycle — collection through WhatsApp and web, AI-powered validation, approval workflows, and natural-language retrieval over collected documents. Xenora powers a suite of products, starting with DocFlow for client document intake and onboarding.

Get started in three steps — sign up, choose your domain, and create your first flow. From there, Xenora takes over — sending document requests, reminding clients, validating every upload, and preparing the final file for your review.
Every client, every case, every document — tracked in one place. You always know exactly where things stand.
Adding your team is just as simple. Onboard colleagues with one click and collaborate on cases without losing context or control.


### Key capabilities

**Multi-channel document collection**
Collect documents from clients through the WhatsApp Business API (primary) or a web portal (fallback). Automated reminders, status tracking, and per-client checklists eliminate manual follow-up.

**AI-powered document validation**
Every uploaded document is validated by Xenora's RAG-based AI layer — checking for completeness, correct document type, expiry dates, signature presence, and field-level accuracy before it reaches the reviewer's queue.

**Document review workflow**
Every upload moves through a clear lifecycle — Awaiting Upload → Uploaded → Approved / Rejected / Re-upload Requested. Reviewers approve, reject, or request a re-upload directly from the case page, with the reason captured and sent back to the client automatically.

**WhatsApp-first client experience**
Clients submit documents, receive reminders, and check status entirely within WhatsApp — no app installs, no logins, no friction. Desktop web access is available for clients who prefer it.

**Workflow templates**
Pre-built templates for common document flows — KYC onboarding, Power of Attorney, Sale Deed, loan documentation, employee onboarding — that firms can customize and reuse.

**Audit trail & compliance**
Every document event (submission, validation, approval, modification) is logged with timestamps and actor identity. Six-year retention by default, aligned with Indian regulatory requirements.

### Get started

- **Quickstart** — Sign in, choose a plan, and pick your domain in under five minutes.
- **Dashboard tour** — Learn how practice domains and flows are organized.

---

## Features

*How Xenora moves a case from collection to close.*

Xenora handles every stage of the document lifecycle — from the first WhatsApp message to a fully verified case file.

### Collect

Send your client a personalised document checklist via WhatsApp and email. They upload from their phone — no app, no login, no confusion. Multi-party cases handled automatically — every director, partner, or employee gets their own link.

### Validate

Every upload is checked instantly by AI — document type, legibility, name match, and recency. Conflicts caught before you open the file. Errors flagged before they become problems.

### Track

One dashboard. Every case. See exactly what has been submitted, what is pending, and what needs your attention — across all clients, all domains, all team members.

### Automate

Reminders sent automatically. Follow-ups handled without lifting a finger. Cases move forward on their own — you step in only to approve.

### Close

Approve the case, download a verified file set — tagged, classified, and AI-reviewed. Full audit trail attached. Every document accounted for. Case closed and archived in one click.

---

## Domains Supported

Xenora supports a growing set of practice domains, each with built-in flows tailored to that domain's standard document collection and workflow needs.

### Chartered Accountants & Auditors
- Client KYC onboarding
- Statutory audit document collection
- Tax filing (Income Tax, GST)
- ROC filings and compliance
- Internal audit

### Legal & Company Secretarial
- Power of Attorney
- Sale Deed / property documentation
- Company incorporation
- Shareholder agreements
- Director KYC

### HR & People Operations
- Employee onboarding
- Background verification
- Document renewals (visa, work permits)
- Exit documentation

### Financial Services
- Loan processing (personal, business, home)
- KYC for financial institutions
- Insurance claim documentation

### Cross-domain
- Custom flows (build your own)

---

## Concepts & Glossary

*A quick map of the words Xenora uses — and what each one actually means.*

| Term | What it means |
|---|---|
| **Domain** | A practice area your firm works in — Tax, Audit, HR, Legal, Loans, etc. Turning a domain on activates the flows built for it. |
| **Flow** | A pre-built template that defines the document checklist for a specific use case (e.g. "Statutory Audit", "Employee Onboarding"). You run a flow by creating a case from it. |
| **Custom Workflow** | A flow you build yourself for a requirement that isn't in the built-in set. Once saved, it's a reusable template your whole team can use — same as any standard flow. |
| **Case** | One instance of a flow, for one customer. A case is the unit of work — created, tracked, reviewed, closed. |
| **Party** | A participant in a case. Most cases have one party (the client). Multi-party cases — common in legal and loans — have several (e.g. borrower + co-applicant + guarantor), each with their own document checklist. |
| **Entity / Client** | The organisation a case is attached to (Private Limited, LLP, Partnership, Proprietorship, Trust, HUF) or an individual client. Entities are stored once and re-used across cases — clean records, no re-typing. |
| **Document** | A single file the client is expected to upload (e.g. PAN, GST certificate, bank statement). Documents have their own lifecycle: Awaiting Upload → Uploaded → Approved / Rejected. |
| **Assignee** | The team member responsible for moving a case forward. Cases can be reassigned at any time. |
| **Timeline** | The chronological audit trail of everything that happened on a case — created, document uploaded, validated, approved, reassigned, completed. |

---

## Getting Started

*Sign in, pick a plan, and start collecting documents.*

### Accessing the application

Navigate to [Xenora](https://xenora.ai) in your browser to get started.

![Xenora sign-in page](/doc-images/1.png)

> **Tip:** Have questions? Use the chat in the bottom-right corner anytime.

### Authentication & login

Xenora supports three sign-in methods:

- **Google** — Sign in with your Google account.
- **Microsoft** — Sign in with your Microsoft account.
- **Organization email** — Enter your work email and we'll send a one-time password (OTP) to verify.

### Organization selection

1. **Enter your organization name** — Provide the legal or display name your team will use inside Xenora.
2. **Accept the Terms of Service** — Review the ToS, then continue to plan selection.

![Organization selection screen](/doc-images/2.png)

### Select your plan

Choose a plan to continue. Pricing varies by country — see the [Pricing Page](https://xenora.ai/pricing) for details.

> **Trial and billing**
> - All paid plans include a 14-day free trial.
> - A Free plan is also available if you'd like to try Xenora without a trial period.
> - Cancel anytime during the trial — no charges will apply.

> **Domain selection**
> - **Free / Starter** — includes one domain.
> - **Pro** — includes one domain, with optional add-on domains available for an extra fee.
> - **Business** — includes access to all domains.

![Plan selection](/doc-images/3.png)
> Prices may vary by region. Billing is in INR for India and AED for the UAE; all other regions are billed in USD. See https://xenora.ai/pricing for details.

#### Quick plan comparison

| Feature | Free | Starter | Pro *(Most popular)* | Business | Pro Max |
|---|---|---|---|---|---|
| **Users** | 1 | 1 | 5 | 20 | Custom |
| **Storage** | 5 GB | 10 GB | 100 GB | 500 GB | Custom |
| **Domains** | 1 | 1 | 1 (+ add-ons) | All domains | All domains |
| **Per-file upload limit** | Plan-defined | Plan-defined | Plan-defined | Plan-defined | Highest |
| **WhatsApp notifications** | ✓ | ✓ | ✓ | ✓ | ✓ |
| **Desktop upload fallback** | ✓ | ✓ | ✓ | ✓ | ✓ |
| **AI validation** | ✓ | ✓ | ✓ | ✓ | ✓ |
| **Custom workflows** | — | — | — | ✓ | ✓ |
| **Team roles** | — | — | ✓ | ✓ | ✓ |
| **Support** | Standard | Standard | Priority | Priority | Priority + dedicated CSM |
| **Dedicated onboarding** | — | — | — | ✓ | ✓ |

> **Tip:** The per-file upload limit is set by your plan. You can always see your current limit in **Settings → Plan**, listed as *Max upload size*. The limit applies per file — total storage is governed separately by your plan's storage quota.

---

## Dashboard

*Your control center.*

When you log in, you land on the **Dashboard**. The Dashboard is where you turn on the **practice areas** (called *domains*) your team works in — for example, HR, Tax, Legal, Compliance, Loans, or Real Estate.

![Dashboard with practice domains](/doc-images/4.png)

### Accessing flows

There are two ways to access flows for your practice domain:

**From the home screen**
Select your practice domain to see all flows available for it.

**From the Flows page**
1. **Open Flows** — Click **Flows** in the left-side menu.
2. **Pick a domain** — Use the dropdown on the top-right to select your practice domain.
3. **Browse flows** — The page loads the predefined flows for that domain.

![Flows page with domain dropdown](/doc-images/5.png)

---

## Entities & Clients

*Clean, reusable records for every client you work with.*

The **Entities & Clients** page is where Xenora stores the people and organisations you collect documents from. Once a client or entity is added, every future case for them is just a couple of clicks — no re-typing names, contact details, or registration numbers.

### Two record types

Xenora keeps two distinct record types so your team uses the right one without thinking about it:

- **Client** — an individual person. Stored with first name, last name, email, mobile number, and optional internal notes. Used when the case is with a specific human (employee onboarding, individual ITR filer, applicant).
- **Entity** — an organisation. Stored with the registered name, entity type (Pvt Ltd, LLP, Partnership, Proprietorship, Trust, HUF), PAN, GSTIN, CIN, address, and associated directors/partners. Used when the case is with a company (statutory audit, GST filing, company incorporation).

### Why this matters

- **No duplicate work** — Add a client or entity once. Every case for them pre-fills the contact and identifier fields automatically.
- **Audit-ready records** — Each entity carries its PAN, GSTIN, CIN, and director/partner list in one place, so audit pulls are a search away.
- **Multi-case view** — Open a client or entity and you see every case ever run for them, with status, deadline, and assignee at a glance.

### Working with records

- **Add a client** — Click **Add Client**. Fill in name, email, mobile, and optional notes. Save.
- **Add an entity** — Click **Add Entity**. Pick the entity type, fill in registered name, PAN, GSTIN/CIN if applicable, then add directors/partners.
- **Search** — Search by client name, email, or mobile in the Clients tab; search by entity name, PAN, or GSTIN in the Entities tab.
- **Edit** — Open any record to update its details. Changes don't affect historical cases — past cases keep the data they had at the time.
- **Delete** — Records that aren't tied to any case can be deleted. Records with cases attached cannot — close or cancel the related cases first.

### Using entities in cases

When you create a case (see [Creating a case](#creating-a-case)), pick an existing entity from the **Entity / Company** dropdown. The case inherits the entity's contact details and identifiers. If the entity doesn't exist yet, click **Add new entity** right from the case form — it's saved to your entities list at the same time.

---

## Your workspace

*Managing your cases and tickets.*

A **case** is a single instance of document collection — one customer (or set of parties), one set of required documents, tracked from creation to completion. When you create a case, you're instantiating a flow for a specific customer. Once created, Xenora handles the rest: notifying the customer, collecting their documents, running AI validation, and queueing everything for your review and approval.

### Anatomy of a case

Every case has the following attributes:

- **Case ID** — unique identifier
- **Flow** — the template this case is based on
- **Parties** — the customers involved
- **Documents** — what's been requested and uploaded
- **Status** — current lifecycle state
- **Assignee** — team member responsible
- **Audit trail** — every event with timestamp

### Case lifecycle

A case moves through these states:

`Open → In Progress → Under Review → Completed / Cancelled → Archived`

- **Open** — sent to customer, awaiting first upload
- **In Progress** — at least one document uploaded, more pending
- **Under Review** — all documents uploaded, awaiting reviewer action
- **Completed** — all documents approved
- **Cancelled** — manually stopped
- **Archived** — moved out of active view

### Case views

Xenora provides multiple views to help you find and manage cases at different stages of work:

- **All Cases** — Every case in your organisation, including completed and archived cases.
- **Pending Review** — Cases awaiting action from you or your team (see [Pending Review](#pending-review)).
- **My Cases** — Cases currently assigned to you (filtered from All Cases by the assignee chip).
- **Filters and search** — Search by customer name, email, or mobile number to quickly locate a specific case.

### Creating a case

To create a case, choose a flow and fill in the customer details. Once created, the client is notified and can begin uploading the requested documents.

![New case creation form](/doc-images/6.png)

1. **Choose a flow** — From the **Flows** page, click the flow template you want to use, or click **New Case**.
2. **Fill in the case form**
   - **Client name** — the person you are collecting documents from
   - **Client email** and/or **mobile number** — where reminders will be sent
   - **Entity / Company** — the organization this case belongs to (optional)
   - **Deadline** — the date by which documents are expected
   - **Reminder days** — how many days before the deadline to nudge the client
   - **Custom fields** — any extra information specific to the chosen flow
   - **Internal notes** — private notes only your team can see
3. **Choose how the first notification is sent**
   - **Send WhatsApp + Start Case** *(recommended)* — creates the case and sends email and WhatsApp notifications.
   - **Create Case** — don't send yet. Create the case silently and send later, or upload documents on behalf of your user.
4. **Click Create & Send** — The client immediately receives a message with the document checklist, deadline, and a secure upload link.

> **Tip:** If your case is associated with an entity or organization, select an existing entity from the dropdown, or click **Add new entity** to create one.

### Notifications and file upload

Once you create a case, your customer receives an email and a WhatsApp notification with the list of requested documents. They can submit documents in two ways:

- **Reply on WhatsApp** — Upload documents directly in the WhatsApp conversation.
- **Use the secure email link** — Open the link in the email to upload documents through the web portal.

**WhatsApp message**

![WhatsApp message](/doc-images/7.png)

**Email (client view)**

![Email client view](/doc-images/8.png)

#### Notification triggers

| Event | WhatsApp | Email |
|---|---|---|
| Case created | ✓ | ✓ |
| Document rejected | ✓ | ✓ |
| Reminder sent | ✓ | ✓ |
| Case completed | ✓ | ✓ |
| Case cancelled | ✓ | ✓ |

#### Reminder cadence

Reminders are scheduled when you create the case, based on the **Reminder after** value you pick on the case form. You can choose **1, 2, 3, 5, or 7 days** before the deadline. A reminder fires on both WhatsApp and email — same channels as the original request. If the case is still open at the deadline, follow-up nudges continue until the case is marked complete or cancelled.

You can also send a reminder manually any time from the case page — **Send Notification** at the top of any open case.

#### One active case per mobile number (WhatsApp)

To avoid confusing clients with overlapping conversations, Xenora allows only **one active WhatsApp case per mobile number** at a time. If a number already has an Open, In Review, or Reopened case:

- New cases for that number are switched to **email-only** notifications automatically.
- The mobile field on the case page shows an amber warning icon indicating WhatsApp delivery is paused for this number.
- Once the existing case is **Completed** or **Cancelled**, WhatsApp resumes automatically for any new case on that number.

Email notifications are never gated by this rule — they always go out.

### Working with documents

When your customer uploads a document, you'll receive a notification. You can also check pending cases anytime from **My Cases**, **Pending Cases**, or **All Cases** (see [Case views](#case-views)).

Click **View** on any case to open it and see the documents the customer has submitted.

#### Supported formats

- PDF
- JPG, PNG, HEIC
- Excel, Word

The maximum size for any single uploaded file depends on your plan — see your current limit in **Settings → Plan** under *Max upload size*. Total storage across all uploads is governed by your plan's storage quota (see the [plan comparison](#quick-plan-comparison)).

#### AI validation

Each uploaded document is automatically validated by Xenora's AI. The system checks:

- Document type matches the request
- Required fields are present
- Image quality (blur, rotation, completeness)
- Expiry dates *(beta — not yet rolled out for public use)*
- Signatures on legal documents *(beta — not yet rolled out for public use)*

Each document is marked as one of:

- **Valid** — The document passed all checks.
- **Invalid** — The document failed validation (e.g., wrong document type, missing fields).
- **Unidentifiable** — The document couldn't be read automatically — usually a blurry image, a regional language, or an unrecognized format. You can still open it and review manually.

**Common reasons validation fails:**

- Document is blurry or low-resolution
- Document is in a regional language not yet supported
- Wrong document type uploaded (e.g., Aadhaar instead of PAN)
- Photo of a screen instead of a scan

#### Manual review

After AI validation, you can:

- **Approve** the document if it meets your requirements.
- **Reject** the document — the customer will be notified to upload it again.
- **Skip** the document if it's not required at this stage.

![Working with documents](/doc-images/9.png)

| Status | What it means |
|--------|---------------|
| Awaiting Upload | Client has not yet uploaded |
| Uploaded | Client has uploaded; needs your review |
| Approved | You have accepted the document |
| Rejected / Re-upload Requested | You asked the client to upload again |
| Skipped | Document was marked as not required |

### Case actions

Once you've opened a case, several actions are available from the top of the page:

**Send Notification**
If a customer hasn't responded in time, click **Send Notification** to remind them. The reminder is sent through both WhatsApp and email — the same channels used for the original request.

**Complete**
Once all documents are reviewed and approved, you can mark the case as complete to close it out.

**Cancel**
If a case is no longer needed — for example, the customer has withdrawn the request or the requirement has changed — click **Cancel** to stop the case. The customer is notified that the case has been cancelled, and no further uploads are accepted.

**Archive**
Completed or cancelled cases can be archived using the **Archive** button. Archived cases remain in the system for audit and reference, but are moved out of your active view to keep the dashboard focused on ongoing work.

**Download All**
Click **Download All** at the top of the case to download every document the customer has uploaded as a single bundle.

### Internal notes

Every case has an **Internal notes** field that's visible only to your team — clients never see it. Use it to capture context that doesn't belong in a document: a phone call summary, a flag for the partner, a deadline negotiated separately. Notes appear as a dedicated card on the case page when present.

### Case timeline (audit trail)

Each case carries a chronological **Timeline** on the right side of the case page. Every meaningful event is recorded with a timestamp and the actor (team member or client) who triggered it:

- Case created, assigned, reassigned
- Document requested, uploaded, validated, approved, rejected, re-upload requested, skipped
- Notification sent (manual or automatic reminder)
- Notes updated, fields updated, custom document added or removed
- Case completed, cancelled, reopened, archived

The timeline is the single source of truth for "what happened on this case." It's preserved for the case's full retention period, available for export with the case bundle, and used for internal reviews, client disputes, and audit responses.

---

## Pending Review

*Your team's daily queue — cases that need a human decision now.*

The **Pending Review** page shows every case in your organisation that's currently in an **Open**, **In Review**, or **Reopened** state — in other words, every case where the client has acted (or is expected to act) and your team needs to follow up.

This is the page most reviewers live in day to day. It's faster than scrolling through All Cases because completed, cancelled, and archived work is hidden by default.

### What you can do here

- **Search** — Filter by client name, email, or mobile to jump straight to a specific case.
- **Open** — Click any row to open the full case view (documents, timeline, actions).
- **Sort** — Most recently updated cases bubble to the top so the queue stays current.
- **Paginate** — 10 cases per page by default; use the controls at the bottom to move through the queue.

### When to use it vs All Cases

- Use **Pending Review** when you start your shift, or any time you want to know "what needs me right now."
- Use **All Cases** when you're looking for a specific historical case, building a report, or auditing past work — it includes completed, cancelled, and archived cases too.

---

## Custom Workflow

*Build your own workflow.*

### Custom workflows

Custom workflows are one of Xenora's most powerful and flexible features. They let you design your own document collection processes — tailored exactly to how your business operates.

- **Multiple parties** — Collect documents from multiple customers, vendors, or stakeholders in a single case.
- **Custom requirements** — Specify exactly which documents each party needs to submit.
- **Custom fields** — Capture structured data alongside the documents.

![Custom workflow builder](/doc-images/11.png)

Once created, a custom workflow becomes a reusable template for your team. Run it again for similar cases without rebuilding the process from scratch.

### Using a custom flow

Once created, your custom flow appears under the **Custom Flows** section on the **Flows** page. From there, it works exactly like any built-in flow:

1. **Open the flow** — Click the custom flow to open it.
2. **Create a new case** — Create a new case and select the parties involved.
3. **Notify the customer** — Customers receive WhatsApp and email notifications, just like with standard flows.
4. **Review uploads** — Documents are uploaded, validated, and reviewed through the usual process.

![Custom flow case view](/doc-images/12.png)

> **Note:** There's no separate workflow for cases created from custom flows — your team can use them seamlessly alongside Xenora's built-in flows.

### Sharing documents with customers

Xenora isn't just for collecting documents — you can also send documents to your customers, either for their reference or to request signed copies in return.

Document sharing uses a built-in flow called **"Share documents with Client"**, available in your practice domain.

**To share a document:**

1. From the **Flows** page, select **Share documents with Client** and create a new case.
2. Enter the customer's details (name, email, mobile).
3. Open the **Share Document** tab inside the case and upload the files.
4. Toggle **Response required** if you need the customer to send signed documents back.
5. Add any instructions in the **Remarks** field.

You can add multiple documents to a single share — they'll all be sent to the customer together.

The customer receives the documents via WhatsApp and email. Once the case is complete, click **Complete** to close it.

---

## General Settings

*Configure organization-wide settings, view plan details, and manage your account.*

### General settings

The **Settings** page provides an overview of your organization's account, including:

- **Tenant ID** — Your unique organization identifier.
- **Current plan** — The subscription plan you're on.
- **Plan limits & usage** — Users, storage, and domains used vs. available.

You can also update your organization name or add an address at any time.

![Organization settings page](/doc-images/10.png)

### Delete organization

> **⚠️ Warning:** Use this option carefully. Account deletion is permanent and cannot be undone once the cool-down period ends.

After you cancel your billing, you can request deletion of your organization. The process works as follows:

1. **Immediate archival** — Your account is archived as soon as you confirm deletion. You and your team will lose access to the dashboard, and no new cases or uploads can be created.
2. **Cool-down period** — Your data is retained for **1 to 6 months** to meet statutory and regulatory requirements (such as tax records and audit obligations under Indian law).
3. **Permanent deletion** — Once the cool-down period ends, all your documents and account data are permanently deleted from Xenora's systems and cannot be recovered.

> **Note:** If you change your mind during the archival period, contact support to restore your account before the cool-down completes.

---

## Teams & Roles

*Invite team members, assign roles, and manage user access.*

> **Note:** The **Teams** feature is available on the **Pro**, **Business**, and **Pro Max** plans.

Invite team members to your organisation and collaborate on cases together.

- **Create & assign cases** — Assign new cases to specific team members so ownership is clear from day one.
- **Reassign cases** — Move cases between team members as workloads shift.
- **View team workload** — See which cases each member is currently handling and rebalance as needed.

### Adding team members

To add a team member, go to **Settings → Team → Add User**. Enter their email address and pick a role. They'll receive an invitation to join your organisation; once they accept, they can sign in with Google, Microsoft, or email OTP — the same options available to you.

### Roles

Xenora has three roles. Pick the lowest one that lets the person do their job.

- **Admin** — Full control. Manages the organisation, billing, team, and settings. Every organisation must have at least one Admin.
- **Editor** — Day-to-day operator. Creates and works cases, manages clients and entities, but can't change billing, settings, or the team.
- **Read** — View-only. Can see cases, clients, and dashboards, but can't create, edit, or approve.

### Roles & permissions matrix

| Capability | Read | Editor | Admin |
|---|---|---|---|
| View dashboard | ✓ | ✓ | ✓ |
| View cases | ✓ | ✓ | ✓ |
| View clients & entities | ✓ | ✓ | ✓ |
| Create / edit cases | — | ✓ | ✓ |
| Approve / reject documents | — | ✓ | ✓ |
| Create / edit clients & entities | — | ✓ | ✓ |
| Build custom workflows | — | ✓ | ✓ |
| Be assigned to a case | ✓ | ✓ | ✓ |
| Access Settings (organisation, plan, team) | — | — | ✓ |
| Access Billing & Invoices | — | — | ✓ |
| Add / disable / delete team members | — | — | ✓ |
| Delete the organisation | — | — | ✓ |

> **Heads up:** Only **Admin** can access Billing, Invoices, and the Settings area. If an Editor or Read user tries to open those pages directly, they'll see an Access Denied screen — by design, not a bug.

### Changing someone's role

Open **Settings → Team**, click the user, and pick the new role. The change takes effect on their next page load — they don't need to sign out and back in.

---

## Billing & Renewals

*Manage your plan, invoices, payment methods, and renewals.*

> **Admin-only:** Billing, Invoices, Renewal, and Payment Methods are visible only to users with the **Admin** role.

### Billing

The **Billing** page shows your current plan and lets you manage your subscription. To access it, click **Billing** in the side menu.

- **Upgrade your plan** — Move to a higher tier for more users, storage, and domain limits.
- **Downgrade** — Switch to a lower tier. The change takes effect at the end of the current billing cycle so you don't lose access mid-period.
- **Buy additional domains** — Add more domains on the **Pro** plan as your practice grows.
- **Switch billing cycle** — Move between monthly and annual billing.

### Invoices

The **Invoices** page lists every invoice generated for your organisation — monthly subscriptions, annual plans, add-on domains, and one-off charges. You can download any invoice as a PDF for your records or accounting team.

### Payment methods

The **Payment Methods** page shows the card on file for your subscription and lets you replace it. To open it, go to **Billing → Payment Methods**.

You'll be asked to update your payment method when:

- **A charge fails** — Xenora couldn't collect your scheduled payment (expired card, insufficient funds, bank decline).
- **Your card is expiring soon** — We surface a banner before the card stops working.
- **You manually choose to replace it** — Any time, no reason needed.

Replacing the card keeps your existing subscription intact — same plan, same renewal date, no new trial. Only the card on file changes.

### Renewal

If a payment fails, Xenora gives you a grace period to fix it before your team loses access. The exact timing depends on your plan status:

| Status | What's happening | What you should do |
|---|---|---|
| **Payment past due** | A scheduled charge didn't go through. Your team still has full access. | Open **Billing → Renew** and complete the payment. Update the card if it's the cause. |
| **Suspended (post-grace)** | Payment didn't recover in time. Your team's access is paused, but your data is intact. | Renew to restore access immediately — nothing is lost. |
| **Archival pending** | Suspension has continued past the data-archival threshold. Your data will be archived shortly. | Renew now to keep your account live. Once data is archived, recovery requires support. |

The **Renew** page (**Billing → Renew**) walks you through any pending payment. It tells you the exact amount due, the consequences if you don't act by a given date, and the next steps after payment succeeds.

### Add-on domains

On the **Pro** plan, you start with one domain. Need another? Buy an add-on domain from the Billing page — it's pro-rated to the rest of your current billing period and renews with your subscription.

**Business** and **Pro Max** plans include access to all domains at no extra cost.

### Cancellation

You can cancel your subscription from the Billing page at any time. You'll keep full access until the end of the period you've already paid for; we don't pro-rate refunds on mid-period cancellations.

After cancellation, you can also request **deletion of your organisation** — see [Delete organization](#delete-organization) for the cool-down and permanent-deletion process.

### Billing support

If you have any issues with billing or need help with your account, reach out:

- **Billing queries:** [billing@xenora.ai](mailto:billing@xenora.ai)
- **Product support:** [support@xenora.ai](mailto:support@xenora.ai)

---

## Troubleshooting

*Quick fixes for the things users hit most often.*

### Sign-in & access

| Symptom | What's happening | What to do |
|---|---|---|
| "Session expired" after a fresh login | Your session genuinely expired, or a request to a backend service failed authentication. | Sign in again. If it repeats, contact support — your account may need a reset. |
| "Access Denied" on Settings / Billing / Team | Your role doesn't have access. Only **Admin** can open these. | Ask an Admin in your organisation to either grant you Admin or perform the action for you. |
| Stuck on "Loading..." after sign-in | The role lookup is still in progress, or there's a network blip. | Wait 5–10 seconds and refresh. If it persists, sign out and back in. |

### Documents & uploads

| Symptom | What's happening | What to do |
|---|---|---|
| "File too large" when client uploads | The file exceeds your plan's per-file limit. | Ask the client to compress, split, or rescan at lower resolution. Or upgrade your plan to raise the limit. |
| "File type not supported" | The file isn't in the supported set (PDF, JPG, PNG, HEIC, Excel, Word). | Convert to one of the supported formats and try again. |
| AI marks a clearly correct document as **Invalid** | AI flagged a type mismatch, missing field, or quality issue. | Open the document, review the AI reason in the case page, and either accept (Approve manually) or request a clean re-upload. |
| Document marked **Unidentifiable** | AI couldn't read the file — usually blurry, in a regional language, or a photo of a screen. | Open it and review manually. Approve if it's actually correct; ask the client for a clearer scan if not. |

### Notifications

| Symptom | What's happening | What to do |
|---|---|---|
| Client says they got the email but no WhatsApp | This number already has another active case — Xenora pauses WhatsApp to avoid two conversations. | Complete or cancel the other open case for that number, then re-send the notification. See [One active case per mobile number](#one-active-case-per-mobile-number-whatsapp). |
| Reminder didn't go out on time | Reminders fire based on the **Reminder after** value set on the case. If the deadline isn't set, reminders won't fire. | Open the case and confirm the deadline is set. Use **Send Notification** to send one manually. |

### Billing

| Symptom | What's happening | What to do |
|---|---|---|
| "Payment past due" banner | Your card was declined. Your team still has full access — it's a warning. | Open **Billing → Renew** and complete the payment. Replace the card if it's the cause. |
| Suspension after grace period | The grace window expired without payment. Access is paused, data is intact. | Renew immediately — access restores once the payment succeeds. |
| Need an invoice for accounting | All invoices are available as PDF downloads. | Go to **Billing → Invoices** and download the one you need. |

If you hit something that isn't here, email **[support@xenora.ai](mailto:support@xenora.ai)** — include your organisation name, the case ID (if relevant), and a screenshot.

---

## FAQ

*Frequently asked questions about Xenora.*

### Support

**How do I report an issue or contact Xenora support?**

If you encounter any problems while using **Xenora** — including errors such as **"Service not available"** — please report the issue to our support team at **[support@xenora.ai](mailto:support@xenora.ai)**.

*Issue resolution & priority*
- All reported issues are reviewed by our support team.
- Issues are prioritized based on severity and business impact.
- **Critical issues** are typically addressed within **1–3 business days**.

*Product questions & use cases*
For product-related questions, feature clarifications, or use-case discussions, email **[support@xenora.ai](mailto:support@xenora.ai)** and our team will be happy to assist.

**Who should I contact for support, sales, or consulting?**

- **Technical support** — for application issues, access problems, or technical questions, contact **[support@xenora.ai](mailto:support@xenora.ai)**.
- **Sales, consulting & partnerships** — for pricing and plans, Enterprise licensing, consulting and custom solutions, or partnerships and commercial inquiries, contact **[sales@xenora.ai](mailto:sales@xenora.ai)**.


### Security & compliance

**How does Xenora handle security?**

Security is a **core design principle** at Xenora. The platform is built with a security-first approach to protect your data, users, and integrations.

- **Secure by design** — Xenora is a SaaS-based platform, with a self-hosted option available for Enterprise customers. Security is treated as a first-class feature across the platform.
- **Tenant isolation & data protection** — each customer (tenant) is fully isolated using strong data separation. Data is never shared between tenants, multi-tenant database isolation enforces strict boundaries, and the platform prevents PII / PHI data from being logged.
- **Access control & authentication** — Xenora supports Role-Based Access Control (RBAC), per-tenant user and role management, and Multi-Factor Authentication (MFA). Authentication uses **JWT-based authentication**, **OAuth 2.0**, **OpenID Connect**, and **API token authentication** for secure system integrations.
- **Key & sensitive data security** — sensitive information, including **Bring Your Own Keys (BYOK)**, is securely encrypted using industry-standard practices.

**What compliance standards does Xenora meet?**

**Primary compliance standard:** **HIPAA**. Xenora is designed to support regulated workloads requiring strong privacy and data protection controls. For organizations with advanced security or compliance requirements, Xenora can be deployed within your own infrastructure (Enterprise plans only).

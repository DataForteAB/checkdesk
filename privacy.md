---
title: Privacy Policy — Checkdesk for Jira
---

# Privacy Policy

**DataForte AB** · Tant Gröns väg 54, 147 60 Uttran, Sweden
Contact: hello@dataforteab.com
Last updated: 17 August 2026

This policy describes how the Atlassian Marketplace app **Checkdesk for Jira** ("the app") handles
data. The app is built on Atlassian Forge and runs on Atlassian's infrastructure.

## The short version

Checkdesk never leaves your Atlassian site. It has **no external egress at all** — no third-party
service, no analytics, no telemetry — which is why it qualifies for Atlassian's *Runs on Atlassian*
programme. Everything it stores lives in Forge storage inside your own tenant.

## What the app does with your data

Checkdesk keeps a checklist on Jira issues, writes the progress into a Jira field, and can block a
workflow transition while required items are open. It processes:

- **Checklist items you type**: the text, whether an item is required, whether it is done and when.
- **Issue and project identifiers** needed to attach a checklist to an issue and to apply a project
  default template.
- **Configuration you enter**: templates, which projects they default to, the optional extra field
  id, and the "block until every item is done" switch.

The app collects no analytics, does not profile users, and does not sell or share data with anyone.
DataForte AB has no access to your Jira site.

## Where data is stored

All app data lives in the **Forge Key-Value Store**, inside Atlassian's cloud infrastructure, scoped
to your installation.

| Data | Purpose |
|---|---|
| `cl:<issue key>` — the checklist items | showing and updating the checklist on that issue |
| `tpl:<name>` — templates | applying a standard checklist, optionally per project |
| `cfg` — settings | the optional field id and the require-all switch |

The checklist progress ("3/5 (60%)") is also written to the app's own Jira field so it can be used
in JQL, filters, boards and automation. That value lives in Jira, like any other field value.

## Data sent outside Atlassian

**None.** There is no outbound call to any third party.

## Personal data

The app does not intentionally process personal data. Checklist text is written by your own users
and could contain personal data if they type it; it is stored in your tenant and deleted with the
app. If a template or rule references a Jira user, that user's Atlassian account id is stored.

DataForte AB acts as a data processor for whatever passes through the app; you remain the
controller. There are **no sub-processors**.

## Legal basis for processing

Where the GDPR or UK GDPR applies, we process data to **perform the contract** under which the app
is provided to you (Art. 6(1)(b)) and on the **legitimate interest** (Art. 6(1)(f)) in operating the
checklists you created. As processor we act on your documented instructions as controller.

## International transfers

None introduced by the app: data stays in your Atlassian Cloud tenant, in the region Atlassian
assigns to it.

## Retention and deletion

Data lives for as long as the app is installed. **Uninstalling the app deletes its Forge storage.**
Jira issues and field values remain in your site, because they are yours.

To request information or deletion at any other time, write to hello@dataforteab.com. We answer
within 30 days.

## Your rights

Under the GDPR you may request access to, correction of, or deletion of personal data, and you may
lodge a complaint with the Swedish data protection authority (Integritetsskyddsmyndigheten).

## Security and incident notification

The app holds no credentials — it needs none, because it never calls out. Because data lives only
inside your Atlassian tenant, a breach of that stored data would be an Atlassian platform event
handled under Atlassian's incident process; where we become aware of an incident affecting data the
app processes, we will notify you at the vendor contact on your installation without undue delay.

## Children

The app is a business tool for software teams. It is not directed to children, and we do not
knowingly process children's data.

## Changes

Material changes to this policy will be published on this page with a new "last updated" date.

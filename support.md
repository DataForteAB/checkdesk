---
title: Support — Checkdesk for Jira
---

# Support

**Checkdesk for Jira** is built and supported by **DataForte AB**.

- **Email:** hello@dataforteab.com
- **Language:** English
- **Hours:** Swedish business days, 09:00–17:00 CET
- **First response:** within two business days

## Before you write

Most problems fall into one of these:

**The checklist does not appear on an issue.** In the newer Jira issue view the checklist shows up
in the right-hand column under **Checklist** (sections there start collapsed) and as the
**Checklist** field. In the classic view it is an issue panel. If neither is visible, the app may
not be installed for that product or the subscription may have lapsed.

**Progress is not searchable in JQL.** The field is written when the checklist changes; tick or add
an item once and the value appears. Then search with `"Checklist" ~ "100%"` or group by the field on
a board.

**A transition is blocked and should not be.** The "Checklist is complete" validator blocks while
required items are open — or all items, if the admin switched that on. Remove the validator from the
transition, or untick the requirement on the item.

**A template did not apply.** Project defaults apply the first time someone opens an issue with an
empty checklist in that project. Check the project key is listed on the template.

When you write, include your Jira site URL, the issue key and roughly when it happened — that is
usually enough to find it in the logs.

## Links

- [Privacy Policy](privacy.html)
- [Terms of Service](terms.html)

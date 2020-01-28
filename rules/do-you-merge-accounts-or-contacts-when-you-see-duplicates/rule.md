---
type: rule
archivedreason: 
title: Do you merge Accounts or Contacts when you see duplicates?
guid: c56d042d-ab0b-489b-8311-f411016f7a92
uri: do-you-merge-accounts-or-contacts-when-you-see-duplicates
created: 2018-03-26T22:55:50.0000000Z
authors:
- id: 4
  title: Ulysses Maclaren
related: []

---

It’s easy for any CRM system to fill up with duplicate records since people often forget to check if something exists before adding it, or if you have a web form that connects directly, someone may sign up more than once if they forget that they already have

Luckily, it’s very easy in Dynamics 365 to merge duplicates. All you have to do is select the 2 records, and hit the merge button. You can then choose which fields to keep from each record and the subordinate record is deleted.

<!--endintro-->
<dl class="badImage">&lt;dt&gt;<img src="crm-duplicate-bad.jpg" alt="crm-duplicate-bad.jpg">&lt;/dt&gt;<dd>Figure: Bad Example – a developer would not know which record to use to track timesheets against</dd></dl><dl class="goodImage">&lt;dt&gt;<img src="crm-duplicate-good.jpg" alt="crm-duplicate-good.jpg">&lt;/dt&gt;<dd>Figure: Good Example – records merged to remove duplicates</dd></dl>
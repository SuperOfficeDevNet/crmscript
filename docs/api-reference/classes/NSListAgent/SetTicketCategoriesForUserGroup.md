---
uid: crmscript_ref_NSListAgent_SetTicketCategoriesForUserGroup
title: Void SetTicketCategoriesForUserGroup(Integer userGroupId, Integer[] categoryIds)
intellisense: NSListAgent.SetTicketCategoriesForUserGroup
keywords: NSListAgent, SetTicketCategoriesForUserGroup
so.topic: reference
---

# Void SetTicketCategoriesForUserGroup(Integer userGroupId, Integer[] categoryIds)

Set ticket categories for one user group

**Parameters:**
 - **userGroupId** The ids of the user groups we want tickets categories from
 - **categoryIds** The ids of the user groups we want tickets categories from

```crmscript
NSListAgent agent;
Integer userGroupId;
Integer[] categoryIds;
agent.SetTicketCategoriesForUserGroup(userGroupId, categoryIds);
```


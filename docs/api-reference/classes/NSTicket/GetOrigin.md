---
uid: crmscript_ref_NSTicket_GetOrigin
title: TicketOrigin GetOrigin()
intellisense: NSTicket.GetOrigin
keywords: NSTicket, GetOrigin
so.topic: reference
---

# TicketOrigin GetOrigin()

What is the origin of this ticket

**Returns:** TicketOrigin

     - Enum: 0 = Unknown 
     - Enum: 1 = Email 
     - Enum: 2 = SMS 
     - Enum: 3 = Fax 
     - Enum: 4 = Phone 
     - Enum: 5 = Facebook 
     - Enum: 6 = Twitter 
     - Enum: 7 = Internal 
     - Enum: 8 = CustomerCentre 
     - Enum: 9 = EMarketing 
     - Enum: 10 = AutoGenerated 
     - Enum: 11 = Chat 
     - Enum: 12 = Form 

```crmscript
NSTicket thing;
TicketOrigin origin  = thing.GetOrigin();
```


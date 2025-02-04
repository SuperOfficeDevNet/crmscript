---
uid: crmscript_ref_NSQuoteAgent_GetAllPriceLists
title: NSPriceList[] GetAllPriceLists(Integer quoteConnectionId, String currency)
intellisense: NSQuoteAgent.GetAllPriceLists
keywords: NSQuoteAgent, GetAllPriceLists
so.topic: reference
---

# NSPriceList[] GetAllPriceLists(Integer quoteConnectionId, String currency)

Gets the all PriceLists in all currencies, including those inactive. Will return empty array if there is no PriceList available.

**Parameters:**
 - **quoteConnectionId** Primary key of the connection
 - **currency** Iso currency like: USD or NOK. See http://www.currency-iso.org/dl_iso_table_a1.xls for details. Case insensitive. Will return empty array if there is no PriceList with the stated currency available.

**Returns:** NSPriceList[]

```crmscript
NSQuoteAgent agent;
Integer quoteConnectionId;
String currency;
NSPriceList[] res = agent.GetAllPriceLists(quoteConnectionId, currency);
```


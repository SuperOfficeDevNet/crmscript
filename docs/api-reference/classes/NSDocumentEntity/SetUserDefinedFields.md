---
uid: crmscript_ref_NSDocumentEntity_SetUserDefinedFields
title: SetUserDefinedFields(Map udefs)
intellisense: NSDocumentEntity.SetUserDefinedFields
keywords: NSDocumentEntity, SetUserDefinedFields
so.topic: reference
---

# SetUserDefinedFields(Map udefs)

Set the user-defined fields on the NSDocumentEntity as a map.

**Parameter:** 
 - **udefs** Map user defined field values encoded as strings.

```crmscript
NSDocumentEntity thing;
Map udefs;
udefs["SuperOffice:1"] = "[I:123]";
udefs["SuperOffice:1"] = "123"; // this will also work, but beware of decimal point variations in different languages
udefs["custom.progid"] = "foobar";
thing.SetUserDefinedFields(udefs);
```


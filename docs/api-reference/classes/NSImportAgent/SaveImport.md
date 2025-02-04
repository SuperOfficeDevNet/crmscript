---
uid: crmscript_ref_NSImportAgent_SaveImport
title: Integer[] SaveImport(NSImportLine[] importLines, String[] columnDefinition, Bool createSelection, String culture, String context)
intellisense: NSImportAgent.SaveImport
keywords: NSImportAgent, SaveImport
so.topic: reference
---

# Integer[] SaveImport(NSImportLine[] importLines, String[] columnDefinition, Bool createSelection, String culture, String context)

Do the actual import

**Parameters:**
 - **importLines** The rows that will be imported
 - **columnDefinition** An array of the columndefinitions, like firstname, lastname, ...
 - **createSelection** true if a selection of the imported entities shall be made
 - **culture** The current culture used in the import. Used to match language specific strings
 - **context** Optional context for the import.

**Returns:** Integer[]

```crmscript
NSImportAgent agent;
NSImportLine[] importLines;
String[] columnDefinition;
Bool createSelection;
String culture;
String context;
Integer[] res = agent.SaveImport(importLines, columnDefinition, createSelection, culture, context);
```


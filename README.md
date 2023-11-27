# Ludopus AL Code Snippets

This extension is mainly for employees of Ludopus GmbH. 
It provides a list of code snippets for extension development written in AL for Microsoft Business Dynamics.

## Features

The following list shows all snippets that are available in this extension:

| Name | Type | Description |
| --- | --- | --- |
| LUDCreateSetupTable | Table Body | Creates a table body for the setup table for an extension. |
| LUDCreateSetupCardPage | Page Body | Creates a page body for the setup card page for an extension. The base for this page is the code snippet LUDCreateSetupTable. |
| LUDSetupEventSubscriber | EventSubscriber | Creates an EventSubscriber which is triggert after company initialisation. It starts the setup process of an app. |
| LUDSourceCodeSetupTableExtension | Tabel Extension | Creates the table extension for the source code setup table |
| LUDToDoBC22 | Comment | Creates a todo comment with the string "BC22" in it. This snippet is intended to mark code blocks that must be changed when updating to version BC22 and newer. | 
| LUDHandledPattern | Procdure Body | Creates a standard procdure body with the handled event pattern in it. |
| LUDAssistEditProcedure | Procedure | Creates an AssistEdit Procedure which handles the number assignment for new records |
| LUDNoAndNoSeriesTableFields | Table Fields | Creates the field No. and No. Series and initializes it with the OnValidate trigger and table relation. |
| LUDBlockedFields | Table Fields | Creates the fields Blocked and Blocked Description with the OnValidate trigger. |


## Requirements

The prerequisite for use is that you develop at least on BC version 22. Otherwise, individual code sections will be faulty if the version is too old.
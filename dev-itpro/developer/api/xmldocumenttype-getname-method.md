---
title: "GetName Method"
ms.author: solsen
ms.custom: na
ms.date: 12/21/2017
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 1
manager: edupont
author: SusanneWindfeldPedersen
---

 

# GetName Method
Gets the name for this Document Type Definition (DTD).  
```  
[Ok := ] XmlDocumentType.GetName(Result)  
```  
## Parameters
*Result*    
&emsp;Type: [Text](../datatypes/devenv-text-data-type.md)  
A string that contains the name for this Document Type Definition (DTD).  
  
## Return Value
*Ok*  
&emsp;Type: [Boolean](../datatypes/devenv-boolean-data-type.md)  
**True** if the operation was successful; otherwise, **false**.  
If you omit this optional return value and the operation does not execute successfully, a run-time error will occur.  
  
## See Also
[XmlDocumentType](xmldocumenttype-class.md)  
[HTTP, JSON, TextBuilder, and XML API](../devenv-restapi-overview.md)  
[Getting Started with AL](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)  

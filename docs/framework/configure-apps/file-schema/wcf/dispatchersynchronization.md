---
title: "&lt;dispatcherSynchronization&gt; | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: cc030f9c-4e38-4b14-94dc-9a0e41ec8e2d
caps.latest.revision: 3
author: "Erikre"
ms.author: "erikre"
manager: "erikre"
---
# &lt;dispatcherSynchronization&gt;
Specifies an endpoint behavior that enables a service to send replies asynchronously.  
  
 \<system.ServiceModel>  
\<behaviors>  
\<endpointBehaviors>  
\<behavior>  
  
## Syntax  
  
```  
  
<dispatcherSynchronizationBehavior    asynchronousSendEnabled=”Boolean”   maxPendingReceives="Integer" />  
```  
  
## Type  
 `Type`  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
  
|Attribute|Description|  
|---------------|-----------------|  
|asynchronousSendEnabled|A Boolean that specifies whether asynchronous send behavior is enabled.|  
|`maxPendingReceives`|An integer that specifies the number of concurrent receives that can be issued on the channel.<br /><br /> This value should be configured only after you have properly configured service throttling behavior.|  
  
### Child Elements  
 None.  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
|[\<behavior>](../../../../../docs/framework/configure-apps/file-schema/wcf/behavior-of-endpointbehaviors.md)|Specifies an endpoint behavior.|  
  
## See Also  
 <xref:System.ServiceModel.Configuration.DispatcherSynchronizationBehaviorElement>   
 <xref:System.ServiceModel.Description.DispatcherSynchronizationBehavior>
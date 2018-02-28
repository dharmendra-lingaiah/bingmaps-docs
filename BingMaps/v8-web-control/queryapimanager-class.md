---
title: "QueryAPIManager Class | Microsoft Docs"
ms.custom: ""
ms.date: "02/28/2018"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: db70142e-212f-4458-927c-6cfc8882ed9a
caps.latest.revision: 5
author: "rbrundritt"
ms.author: "richbrun"
manager: "stevelom"
---
# QueryAPIManager Class
This is a static class that provides that ability to query data sources that are hosted by the Bing Spatial Data Services using the [Query API](https://msdn.microsoft.com/library/gg585126.aspx).

## Static Methods

Name                   | Definition  | Description
---------------------- | ----------- | ---------------------------
`search`               | search(queryOptions: [QueryAPIOptions](../v8-web-control/queryapioptions-object.md), credentials: string _or_ [Map](Map%20Class.md), callback: function(results: [IPrimitive](../v8-web-control/iprimitive-class.md)[], inlineCount?: number), styles?: [StylesOptions](../v8-web-control/stylesoptions-object.md), errorCallback?: function(networkStatus?: string, statusMessage?: string)) | Performs a search against a data source using the Query API. Takes in a set of query options, a Bing Maps key or a reference to a map control for authentication, and a callback function to return the results to. Optionally you can also specify default styles that will be set on the shapes that are returned from the service.

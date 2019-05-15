---
title: " OData Web API 5.6 beta1"
description: ""


ms.date: 04/30/2015
---
# OData Web API 5.6 beta1

The NuGet packages for OData Web API 5.6 beta1 are now available on the [NuGet gallery](https://www.nuget.org/).

### Download this release
You can install or update the NuGet packages for OData Web API 5.6 beta1 using the [Package Manager Console](https://docs.nuget.org/docs/start-here/using-the-package-manager-console):

```
PM> Install-Package Microsoft.AspNet.OData -Version 5.6-beta1 -Pre
```

### What’s in this release?
* Convention and Attribute Routing for Dynamic Property [#319](https://github.com/OData/WebApi/issues/319)
* [Support the odata.include-annotations.](https://odata.github.io/WebApi/#06-19-odataIncludeAnnotations) [#90](https://github.com/OData/WebApi/issues/90)
* [Support UnqualifiedNameCall in attribute routing.](https://odata.github.io/WebApi/#06-01-custom-url-parsing) [#280](https://github.com/OData/WebApi/pull/280)
* [DateTime $filter and $orderby support.](https://odata.github.io/WebApi/#04-01-datetime-support) [#293](https://github.com/OData/WebApi/issues/293)

### Bug fix
[#300](https://github.com/OData/WebApi/issues/300): Function Date() doesn't work with Linq To Entity. 


---
title: WAI-ARIA Support
page_title: WAI-ARIA Support | UI for ASP.NET AJAX Documentation
description: WAI-ARIA Support
slug: grid/accessibility-and-internationalization/wai-aria-support
tags: wai-aria,support
published: True
position: 10
---

# WAI-ARIA Support





## 

The __RadGrid__ control offers __WAI-ARIA__ support which can be easily enabled by setting the __EnableAriaSupport__ server property to __true__.

RadGrid ARIA attributes are __lower case__. They are shown in the table below.


>caption  

|  __Control__  |  __Attributes__  |
| ------ | ------ |
| __RadGrid__ |aria-haspopuparia-hiddenaria-readonlyaria-multiselectablearia-checkedaria-grabbedaria-dropeffectaria-levelrole:grouprole:listitemrole:textboxrole:buttonrole:checkboxEnabled Aria for inner controls (where supported) in column editors, filter headers, pager etc.|

>note An issue with the use of WAI-ARIA in HTML documents is that they don’t validate. When you run a HTML document containing ARIA attributes through the W3C Validator it shows errors in the results for any ARIA attributes. The DOCTYPE declarations do not include any information about the WAI ARIA attributes and you cannot have a valid document which includes elements, attributes, and attribute values, not detailed in its DTD’s.
>


# See Also

 * [This functionality online](http://demos.telerik.com/aspnet-ajax/grid/examples/generalfeatures/waiariasupport/defaultcs.aspx)

 * [WAI-ARIA basic information](http://www.w3.org/WAI/intro/aria)
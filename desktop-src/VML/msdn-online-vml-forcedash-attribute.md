---
title: VML ForceDash Attribute
description: VML ForceDash Attribute
ms.assetid: '659e99bb-16d9-425a-97b1-7767c065ec41'
---

# VML ForceDash Attribute

This topic describes VML, a feature that is deprecated as of Windows Internet Explorer 9. Webpages and applications that rely on VML should be [migrated to SVG](http://go.microsoft.com/fwlink/p/?LinkID=236964) or other widely supported standards.

> [!Note]  
> As of December 2011, this topic has been archived. As a result, it is no longer actively maintained. For more information, see [Archived Content](https://msdn.microsoft.com/library/hh772377). For information, recommendations, and guidance regarding the current version of Windows Internet Explorer, see [Internet Explorer Developer Center](http://go.microsoft.com/fwlink/p/?linkid=204313).

 

Determines whether a dashed outline is used to draw a shape when a shape has no line or fill. Read/write. **VgTriState**.

**Applies To**

[Shape](shape-element--vml.md)

**Tag Syntax**

&lt;v: *element* o:forcedash=" *expression* "&gt;

**Remarks**

Used by Microsoft PowerPoint placeholders to draw a dashed outline when there is no line and no fill for a shape. Default is **False**. If **True**, a dashed outline will be used to indicate a placeholder.

*Microsoft Office Extensions Attribute*

**Example**

A dashed line will be used to render the shape if there is no line or fill.


```HTML
   <v:rect id=myrect fillcolor="red" o:forcedash="True"
   style="position:relative;top:1;left:1;width:20;height:20">
   </v:rect>
```



 

 




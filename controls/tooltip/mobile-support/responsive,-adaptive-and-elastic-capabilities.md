---
title: Responsive, Adaptive and Elastic Capabilities
page_title: Responsive, Adaptive and Elastic Capabilities | RadTooltip for ASP.NET AJAX Documentation
description: Responsive, Adaptive and Elastic Capabilities
slug: tooltip/mobile-support/responsive,-adaptive-and-elastic-capabilities
tags: responsive,,adaptive,and,elastic,capabilities
published: True
position: 0
---

# Responsive, Adaptive and Elastic Capabilities



This article explains the **responsive design capabilities RadTooltip offers**.	The [Lightweight RenderMode]({%slug tooltip/mobile-support/render-modes%}) of RadTooltip supports	**elastic design since Q3 2013**.

@[template](/_templates/common/render-mode.md#resp-design-desc "slug-el: no, slug-fl: no")

## Elastic Design with RadTooltip
>caption Figure 1: Comparison between appearance of a RadTooltip with regular font size and with increased font size

![tooltip-changed-font-size-comparison](images/tooltip-changed-font-size-comparison.png)

**RadTooltip** does not create elastic design by itself, but can fit in a pagethat follows this pattern. This means that RadTooltip does not support dimensions set in percent,but its **Lightweight RenderMode** supports **changing the font size** without breaking the control's appearance - if the new size is larger than the original,the elements in the control will simply increase their size as well to accommodate the text.This fluid layout is achieved by using `em` units for setting dimensions and paddings in the control, instead of `px` because `em` units are tied to the font size. This allows dimensions and sizes to scale with the font size.


>note **RadToolTip** takes the font-size of the page automatically. If the developer does not set it explicitly (**Example 1**), this is up to the client's browser and a common default value is 16px.


>caption Example 1: Setting default font for the page with the default value for the Telerik controls.


````CSS
body {
    font-size: 12px; /* 12px is the default value for Telerik controls */
    font-family: "Segoe UI", Arial, Sans-serif;
}
````


>caption Example 3: How to increase the font size of a RadTooltip. The effect can be seen in comparison in Figure 1.

````ASP.NET
<style type="text/css">
	body
	/*div.RadToolTip*/ /*This rule can be used in versions prior to Q3 2015*/
	{
		font-size: 18px;
	}
</style>
<asp:Image ID="imgStatus" runat="server" Style="width: 100px; height: 100px; display: block; color: #000; margin: 100px auto; border: 1px solid red;" />
<telerik:RadToolTipManager ID="ttmInstallStatus" OffsetY="-1" HideEvent="ManualClose"
	ShowEvent="OnMouseOver" Width="400" Height="140" runat="server" RelativeTo="Element"
	Position="BottomCenter" EnableShadow="true" ShowCallout="true"
	Title="ToolTip Longer Title" EnableEmbeddedSkins="true" RenderMode="Lightweight">
	<TargetControls>
		<telerik:ToolTipTargetControl TargetControlID="imgStatus" Value="Apple" />
	</TargetControls>
</telerik:RadToolTipManager>
````



# See Also

 * [Render Modes]({%slug tooltip/mobile-support/render-modes%})

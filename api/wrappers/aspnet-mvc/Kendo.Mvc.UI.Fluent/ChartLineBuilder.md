---
title:ChartLineBuilder
slug:aspnetmvc-kendo.mvc.ui.fluent.chartlinebuilder
publish:true
---

# Kendo.Mvc.UI.Fluent.ChartLineBuilder
Defines the fluent interface for configuring ChartLine.



## Methods

### Visible(`System.Boolean`)
Sets the line visibility


#### Parameters

##### visible `System.Boolean`
The line visibility.




#### Example (ASPX)
    <% Html.Kendo().Chart()
        .Name("Chart")
        .CategoryAxis(axis => axis.MajorGridLines(lines => lines.Visible(true)))
        .Render();
    %>




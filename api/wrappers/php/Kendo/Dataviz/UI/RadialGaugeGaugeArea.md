---
title: RadialGaugeGaugeArea
slug: php-RadialGaugeGaugeArea
tags: api, php
publish: true
---

# \Kendo\Dataviz\UI\RadialGaugeGaugeArea

A PHP class representing the gaugeArea setting of RadialGauge.


## Methods

### background ``

The background of the gauge area.
Any valid CSS color string will work here, including hex and rgb.


### border

#### Parameters

##### $value `\Kendo\Dataviz\UI\RadialGaugeGaugeAreaBorder|array`

The border of the gauge area.


#### Example - using \Kendo\Dataviz\UI\RadialGaugeGaugeAreaBorder

    $gaugeArea = new \Kendo\Dataviz\UI\RadialGaugeGaugeArea();
    $border = new \Kendo\Dataviz\UI\RadialGaugeGaugeAreaBorder();
    $color = 'value';
    $border->color($color);
    $gaugeArea->border($border);

#### Example - using array

    $gaugeArea = new \Kendo\Dataviz\UI\RadialGaugeGaugeArea();
    $color = 'value';
    $gaugeArea->border(array('color' => $color));

### height `float`

The height of the gauge area.


#### Example - using float
    $gaugeArea = new \Kendo\Dataviz\UI\RadialGaugeGaugeArea();
    $gaugeArea->height(1);

### margin `float|`

The margin of the gauge area.


#### Example - using float
    $gaugeArea = new \Kendo\Dataviz\UI\RadialGaugeGaugeArea();
    $gaugeArea->margin(1);

### width `float`

The width of the gauge area.


#### Example - using float
    $gaugeArea = new \Kendo\Dataviz\UI\RadialGaugeGaugeArea();
    $gaugeArea->width(1);

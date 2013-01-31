---
title: FlatColorPicker
slug: php-ui-flatcolorpicker
tags: api, php
publish: true
---

# \Kendo\UI\FlatColorPicker

A PHP class representing Kendo [FlatColorPicker](/api/web/flatcolorpicker).


## Usage

To use FlatColorPicker in a PHP page instantiate a new instance, configure it via the available
configuration [methods](#methods) and output it by `echo`-ing the result of the `render` method.

### Using Kendo FlatColorPicker

    <?php
    // Create a new instance of FlatColorPicker and specify its id
    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');

    // Configure it
    $flatColorPicker->buttons(true)

    // Output it

    echo $flatColorPicker->render();
    ?>


## Methods

### buttons
Specifies whether we should display the Apply / Cancel buttons.

#### Returns
`\Kendo\UI\FlatColorPicker`

#### Parameters

##### $value `boolean`



#### Example 
    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->buttons(true);

### change
Triggers when a new color has been selected.

#### Returns
`\Kendo\UI\FlatColorPicker`

#### Parameters

##### $value `string|\Kendo\JavaScriptFunction`

#### Example - using string which defines a JavaScript function

    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->change('function(e) { }');

#### Example - using string which defines a JavaScript name
    <script>
        function onChange(e) {
            // handle the change event.
        }
    </script>
    <?php
    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->change('onChange');
    ?>

#### Example - using [\Kendo\JavaScriptFunction](/api/wrappers/php/kendo/javascriptfunction)

    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->change(new \Kendo\JavaScriptFunction('function(e) { }'));

### messages
Allows customization of "Apply" / "Cancel" labels.

#### Returns
`\Kendo\UI\FlatColorPicker`

#### Parameters

##### $value ``



### opacity
Specifies whether we should display the opacity slider to allow
selection of transparency.

#### Returns
`\Kendo\UI\FlatColorPicker`

#### Parameters

##### $value `boolean`



#### Example 
    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->opacity(true);

### preview
Specifies whether we should display the preview bar which displays the
current color and the input field.

#### Returns
`\Kendo\UI\FlatColorPicker`

#### Parameters

##### $value `boolean`



#### Example 
    $flatColorPicker = new \Kendo\UI\FlatColorPicker('FlatColorPicker');
    $flatColorPicker->preview(true);

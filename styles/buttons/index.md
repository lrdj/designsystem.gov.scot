---
layout: component
title:  "X Buttons"
category: styles
parent: styles
thispage: style.buttons
#summary: ""
phase: 3
---

Button styles can be applied to either button or link elements. Use the appropriate element for the task, i.e. use a button element when the user is performing an action, or a link element when the user is navigating.

## Types of button

### Primary (default)

Use this for your primary calls to action. Multiple primary buttons can confuse users. Try to have only one of these per page (or section of a page).

<div class="ds_button-group">
<button class="ds_button">Start here</button>
</div>

### Secondary

<div class="ds_button-group">
<button class="ds_button  ds_button--secondary">View summary</button>
</div>

### Cancel/calloff

<div class="ds_button-group">
<button class="ds_button  ds_button--cancel">Cancel</button>
</div>

### Disabled

<div class="ds_button-group">
<button disabled="true" class="ds_button  ds_button--cancel">Disabled button</button>
</div>



## Width variants

### Flexible (default)

Buttons will expand to fit the length of text by default

<div class="ds_button-group">
<a href="#" class="ds_button">Start</a><br />

<a href="#" class="ds_button">Really super duper start here</a>
</div>

### Fixed

Use fixed-width buttons to force uniformity in button widths.

<div class="ds_button-group">
<a href="#" class="ds_button  ds_button--fixed">Start</a><br />

<a href="#" class="ds_button  ds_button--fixed">Really super duper start here</a>
</div>

### Maximum

Use maximum-width buttons for large buttons. These will fill the width of small screens, up to a set maximum width (480px).

<div class="ds_button-group">
<a href="#" class="ds_button  ds_button--max">Start</a><br />

<a href="#" class="ds_button  ds_button--max">Really super duper start here</a>
</div>




## Size variants

### Small

Use small buttons for XXXXXXXXXXXX.

<div class="ds_button-group">
<a href="#" class="ds_button  ds_button--small">Start here</a>
</div>

The small button modifier can be applied to any type or width variant.
<div class="ds_button-group">
<a href="#" class="ds_button  ds_button--small  ds_button--max  ds_button--secondary">View summary</a><br />

<a href="#" class="ds_button  ds_button--small  ds_button--fixed  ds_button--cancel">Cancel</a>
</div>




## Buttons with icons

Icons can be added to buttons. Buttons with icons can also have any size, type or width modifiers applied to them.

<div class="ds_button-group">
<a href="#" class="ds_button  ds_button--has-icon  ds_button--max">
    Search
    <svg class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#search"></use></svg>
</a><br />

<a href="#" class="ds_button  ds_button--small  ds_button--secondary  ds_button--has-icon">
    Search
    <svg class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#search"></use></svg>
</a><br />

<a href="#" class="ds_button  ds_button--cancel  ds_button--fixed  ds_button--has-icon">
    Cancel
    <svg class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#close-21"></use></svg>
</a>
</div>



## Icon-only buttons

<div class="ds_button-group">
    <a href="#" class="ds_button  ds_button--icon-only">
        <span class="visually-hidden">Search</span>
        <svg class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#search"></use></svg>
    </a><br />

    <a href="#" class="ds_button  ds_button--icon-only  ds_button--small  ds_button--cancel">
        <span class="visually-hidden">Close</span>
        <svg class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#close-21"></use></svg>
    </a>
</div>


<script>

const buttons = document.querySelectorAll('.ds_layout__content .ds_button');

buttons.forEach(function (button) {
    button.addEventListener('click', function (event) {
        event.preventDefault();
    });
})

</script>

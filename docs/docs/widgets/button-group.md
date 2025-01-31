---
id: button-group
title: Button Group
---
# Button group

Button group widget can be used to take actions.


## Properties
### Event: On click

<div style={{textAlign: 'center'}}>


</div>

To add an event to a button group, click on the widget handle to open the widget properties on the right sidebar. Go to the **Events** section and click on **Add handler**.

**On Click** event is triggered when the button group is clicked. Just like any other event on ToolJet, you can set multiple handlers for on click event.

:::info
Check [Action Reference](/docs/actions/show-alert) docs to get the detailed information about all the **Actions**.
:::

### Properties

<div style={{textAlign: 'center'}}>

</div>

| Properties  | description | Expected value |
| ----------- | ----------- | -------------- |
| label | label is used to set the heading of the button group. | Any **String** value |
| labels | It can be used to set the labels of the button group items. |  Array of **strings**|
| values |Values for button group items. | **Array** of strings  |
| Default  selected | Initial selected values can be set using this. | Array of **strings**  |
| Enable multiple selection | Toggle this to allow multiple button selection. | Toggle to true/false |

### General
#### Tooltip

A Tooltip is often used to specify extra information about something when the user hovers the 
mouse pointer over the widget.

Under the <b>General</b> accordion, you can set the value in the string format. 
Now hovering over the widget will display the string as the tooltip.

<div style={{textAlign: 'center'}}>

![ToolJet - widget- button](/img/tooltip.png)

</div>

### Layout

| Layout  | description | Expected value |
| ----------- | ----------- | ------------ |
| Show on desktop | Toggle on or off to display desktop view. | You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}` |
| Show on mobile | Toggle on or off to display mobile view. | You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}` |

### Styles

<div style={{textAlign: 'center'}}>

</div>

| Style      | Description |
| ----------- | ----------- | 
| Background color |  You can change the background color of the widget by entering the Hex color code or choosing a color of your choice from the color picker. |
| Text color |  You can change the color of the Text in button by entering the Hex color code or choosing a color of your choice from the color picker. |
| Visibility | Toggle on or off to control the visibility of the widget. You can programmatically change its value by clicking on the `Fx` button next to it. If `{{false}}` the widget will not visible after the app is deployed. By default, it's set to `{{true}}`. |
| Disable | Toggle on to lock the widget. You can programmatically change its value by clicking on the `Fx` button next to it, if set to `{{true}}`, the widget will be locked and becomes non-functional. By default, its value is set to `{{false}}`. |
| Border radius | Use this property to modify the border radius of the button. |
| Selected background color | Use this property to modify the background colour of selected buttons |

:::info
Any property having `Fx` button next to its field can be **programmatically configured**.
:::
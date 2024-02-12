# Group UI Node

The Group node is useful when you want to perform any logic or change the property of the group dynamically on some event.

This node provides you with all properties that can be changed in a group.

## How to get the Group Node.

To get the group node first group the multiple elements present on the page or mobile canvas together and then select the group created with the selector toggle, then right-click on the group, arsenal panel of blup designer opens up, select the edit in blup lightning option from the dialog box, this will generate the group Node in blup Lightning.

{% hint style="info" %}
<mark style="color:blue;">Note: the group node doesn’t have the onclick output node point so if you wanted to perform any logic when the user clicks on the group you have to do it through the rectangle present inside the group.</mark>
{% endhint %}

## Components of Group UI Node

|                                  |                                                                                                                                                                                                                                                                                       |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Width**                        | This input node helps to define the width of the group.                                                                                                                                                                                                                               |
| **Height**                       | This input node helps to define the height of the group.                                                                                                                                                                                                                              |
| **Is hide**                      | This input node point helps to hide the group, this node point accepts a Boolean-type value if the value is true it hides the group, else the group is visible.                                                                                                                       |
| **Extra Data**                   | this input node points help to store data. which can be used in further cases.                                                                                                                                                                                                        |
| **Edit Checkbox**                | <p>This checkbox helps to access secondary input node points or Extra properties associated with the group node.</p><p>If the checkbox is checked then the secondary input node points are visible ; if notvthen they are hidden and cannot be used.</p>                              |
| **Padding Left**                 | This node point helps to give the left padding.                                                                                                                                                                                                                                       |
| **Padding Right**                | This node point helps to give the Right padding.                                                                                                                                                                                                                                      |
| **Padding Top**                  | This node point helps to give the Top padding.                                                                                                                                                                                                                                        |
| **Padding Bottom**               | This node point helps to give the Bottom padding.                                                                                                                                                                                                                                     |
| **On Group default prop update** | <p>This output node point as the name suggests helps to run any logic when any primary input node points [primary properties ] change.</p><p>Also if you stretch the node point it will give the properties' values that are present on the left-hand side of the rectangle node.</p> |
| **On react Extra prop Update**   | This output node point helps to define logic when the secondary properties are available. Change also similar to above node point stretch this node point further will help you to get more output node points.                                                                       |

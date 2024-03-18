# System Node Section

## System Nodes

This section consists of nodes that provides system features like get global var node, print node etc.

Let's go by each node in this section one by one.

## Page | Init State Node

This node helps you to perform logic inside the init state. Init State is a method that runs only once before the actual user interface is rendered on the screen, so if you wanted to perform any logic before the rendering of UI you can use this node.

This node only consists of one output node point that is on Init State which helps to attach any logic.

## Page | Build Widget Node

This node helps you to perform logic while your UI is being built. Build Widget is a method that is responsible for building the user interface that you see on your screen. Whatever you see on your screen is build through the build widget.

This node also consists of one output node point to which you can attach any logic which you to execute when your UI is being built.

## Page | Dispose Node

This Node Is mostly used to free up the resources or variables value when the object is no longer is focused or destroyed.

This node only consists of one output node to which you can attach logic which executes when your object is removed from focus and frees up the resources.

## Page | Set State Node

This node is used when you want to rebuild the user interface {UI} again with the changes that you have made.

For example:– if you have changed the value of variables which is already present on the UI the changes won't be reflected in the device till the set state is called.

This node only consists of a run input node point which can be attached with any function node point where you want to rebuild the UI.

## Page | Get Global Var Node

This node is one of the most widely used in blup, it helps to get the global data that is available by making a variable node global. Global variables are the way to pass data from one page to another.

You can consume the value on the same page as well, as soon as you create any variable node global by checking the make me global checkbox, it is reflected in the Page | Get global.

### Components of Get Global Var Node

<table><thead><tr><th width="160"></th><th></th></tr></thead><tbody><tr><td><strong>Page name</strong></td><td>This node point defines the page name on which your global variables are present. You can either use the provided drop-down menu which consists of all the pages that exist in your project or you can use the node point to pass value through it. Values inside the dropdown are only available if at least one global variables are present otherwise it is not shown.</td></tr><tr><td><strong>Name of variables</strong></td><td> This node point helps to provide the name of variables similar to the  Page name. Values inside the dropdown are only available if at least one global variables are present otherwise it is not shown.</td></tr><tr><td><strong>Output</strong></td><td>This output node point is used to for getting the value of global variables.</td></tr></tbody></table>

## Page | Set Global Var

This node is used to change or set the value of global variables present on different pages or on the same page.

### Components of blup

|                        |                                                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Page name**          |  This node point helps to define the page name on which your global variables is present.                                    |
| **Name of variables**  | This node point provides the name of variables similar to the Page name node point.                                          |
| **New Value**          | This output node point is used to provide the new value which is replaced by the previous value present in global variables. |

{% hint style="info" %}
<mark style="color:blue;">Note: You can either use the provided dropdown menu which consists of all the pages that exist in your project or you can use the node point to pass value through it. Values inside the dropdown are only available if at least one global variables are present otherwise it is not shown.</mark>
{% endhint %}

## Debug | Print

This node is used to print the value of data. The value provided to this node is shown in the debug console of the blup lightning.

### Components of Node

|            |                                                                                          |
| ---------- | ---------------------------------------------------------------------------------------- |
| **Run**    | This input node point acts as a starting point for the node.                             |
| **Input**  | This input node point provides the input data that you wanted to print in debug console. |

This is one of the most widely used node. This helps you to detect what's going wrong with your logic by printing it on debug console.


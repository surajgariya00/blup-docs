# Variables Node Section


\

The nodes in this section are used to store/hold some data. you can find all the literal nodes like string \[for storing the sequence of characters], double \[for storing the decimal number], integer \[for storing the whole numbers].

![](../../.gitbook/assets/variable.png)


### Common Functionality In All Variables Nodes

**1.** **Input node point –** This node point is used to give the data dynamically instead of hardcoding them into the node.

**2.** **Output node point –** This node point is used to get the output or data you have entered or given through the input node point.

**3.** **Use Run trigger checkbox –** When you check this checkbox you will see that two new function node points will appear in the node one on the top left and one on the top right side.

* Run function node point On Left– this node point helps you to run the node on an event like on-click of a button.&#x20;
* &#x20;Run function node point on Right– this node point helps you to run your other logic after the current logic end has ended. For example, with one click of a button you want to assign data to a string node from the string node, and after the assignment of data you want to upload a file to the link present in the string node this run trigger help you out in such scenarios.
* Call set-state checkbox – this checkbox helps you with refreshing your UI, once your node is being called by some other node.

**4.** **Make me global functionality** – this checkbox helps you to make the node be available globally, which mean that you can use this data present in the node in other tabs also.

{% hint style="info" %}
<mark style="color:blue;">Note: To get this data in other tabs, you can use Page| get global var node present in function section in arsenal or directly search it in the search box.</mark>
{% endhint %}

**5.** **Comment checkbox**  -  This check box helps you to declare a comment or shot note inside the note itself as soon as you click on the checkbox an input inbox will appear in the node in the node itself, this is extra functionality that can be very useful when the number of nodes in one tab is large

<table><thead><tr><th width="169"></th><th></th></tr></thead><tbody><tr><td><strong>String Node</strong></td><td><p>This node is used to define a string. A string is a sequence of characters or a piece of text like a name. </p><p>To define a string through this node use the input box provided in the center of the node and type the string. Or you can use the input node point. </p><p>If you want to add the multi-line text you can use the multi-line checkbox which will extend the available input box present in the center of the node so that you can add the multi-line text easily.</p></td></tr><tr><td><h4>Integer Node</h4></td><td><p>This node helps you define the whole number i.e. number which doesn’t have the decimal point in them for example 20,25, 36, etc. </p><p>You can use the input box to provide the value to the node or you can use the input node point for it.</p></td></tr><tr><td><h4>Double Node</h4></td><td>This node helps you to define numbers with a decimal point in them like 10.20, 20.35, etc. similar to another variable node you can use either the node point or input box to provide the value.</td></tr><tr><td><h4>Boolean Node</h4></td><td><p>Boolean values are either true or false, which means that this node helps you to accept such values.</p><p>To define these types of values through the node you can use the provide checkbox, If the checkbox, is not checked it means that the value is false and if the checkbox is checked it means that the value is true.</p><p>You can also use the input node point to give value to this node. Similar to other variable nodes.</p></td></tr><tr><td><h4>Color Node</h4></td><td>This node helps you to define a colour, to define a colour through this node just click on input [white colour], you can pick a colour by using the eyedropper, entering the hex code or from manually adjusting the RGB scroller and selecting the appropriate saturation and lighting.</td></tr><tr><td><h4>Icon Node</h4></td><td>This node helps you to add an icon. To Add the icon click on the add button present in the center of the node and select the icon of your choice from the list to provide or you can directly search for any icon with a name through the search input box provided.</td></tr><tr><td><h4>Date Time Node</h4></td><td><p></p><p>This node is used to define a date or time, this node is very useful when you are dealing with data that is bounded by some date or time.</p><p>This node can be used in three ways</p><ol><li>Date only- This option helps you to define date only.</li><li>Time only – This option helps you to define time only.</li><li>Date and Time  - This option helps you to define both date and time.</li></ol></td></tr><tr><td><h4>Duration Node</h4></td><td><p>This node is used to define the duration in terms of days, hours and minutes. This node can be used in many situations like when you want an event or any trigger to happen after some time.</p><p>To define the duration just get the duration node from the variables section in the arsenal or you can directly search by name. As you open the node you will see an input box, when you click on that input box a dialog box will show up and then you can give appropriate values according to your requirements, it can accept the duration from the input node point also.</p></td></tr></tbody></table>


<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>
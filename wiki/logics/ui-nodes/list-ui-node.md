# List UI Node

This node helps to create a list of elements.&#x20;

This node is used for providing the data to the list dynamically and for adding logic to various events. The main purpose of the node is to populate the list of items that you want to show repeatedly.

### How to get List UI Node.

![](../../../.gitbook/assets/listview-.gif)

For creating a new List first you have to create a single element \[repetitive element] of the list, this can be a single rectangle, text or a group with multiple items in it. The process remains the same for all types of list except when list element consists of a single rectangle or text then only one item widget is going to be generated while list node is created, but if the single list element consists of multiple items like a group then the number of item widget that going to be associated with list node is equal to the number of items present in the single group.

After the list element is created convert it to the list by clicking on the convert to list button in the properties panel, then select the list created and right-click on the list and choose  "edit in blup lightning" in the arsenal .

As soon as you do that a listview node is generated in the blup lightning which consists of an automatically generated item widget based on the number of items in a single element of the list.

### Components of List UI node



<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Drop Down</strong></td>
      <td>Enable the user to select the list type from the drop down.</td>
    </tr>
    <tr><td><strong>Is Update</strong></td><td>This input node point is used to define whether the children are to be updated dynamically or not, this node point accepts a Boolean type value.</td></tr>
    <tr><td><strong>Item count</strong></td><td>Item count input node point defines the total number of items to be had on the list.</td></tr>
    <tr><td><strong>Is hide</strong> </td><td>This input node point helps to hide the list. </td></tr>
    <tr><td><strong>Extra Data</strong></td><td>This input node points help to store data. which can be used in further cases.</td></tr>
    <tr>
      <td><strong>Iterator</strong></td>
      <td>This node allow you to iterate your elements according to your iterate value.</td>
    </tr>
    <tr>
      <td><strong>Scroll Listener</strong></td>
      <td>This node Listenes the scrolls when ever you scroll in your listview.</td>
    </tr>
    <tr>
      <td><strong>On Bottom Reached</strong></td>
      <td>This node offers what yoou want to do when you reach at the bottom of the listview.</td>
    </tr><tr>
      <td><strong>On Scroll Up</strong></td>
      <td>This output node helps to determine the functionality on scroll up according to your need.</td>
    </tr>
    <tr>
      <td><strong>On Scroll Down</strong></td>
      <td>This output node helps to determine the functionality on scroll down according to your need.</td>
    </tr>
    <tr>
      <td><strong>List View Properties</strong></td>
      <td>This output node Properties to your list.</td>
    </tr>
    <tr>
      <td><strong>On Properties Update</strong></td>
      <td>This Output node gives the additional properties to your List.</td>
    </tr><tr><td><strong>Width</strong></td><td>This input node point helps to define the width of the list.</td></tr><tr><td><strong>Height</strong></td><td>This input node point helps to define the height of the list.</td></tr><tr><td><strong>Padding Left</strong></td><td>This node point helps to give the left padding.</td></tr><tr><td><strong>Padding Right</strong></td><td> This node point helps to give the Right padding.</td></tr><tr><td><strong>Padding Top</strong></td><td>This node point helps to give the Top padding.</td></tr><tr><td><strong>Padding Bottom</strong></td><td>This node point helps to give the Bottom padding.</td></tr>
    <tr><td><strong>Grid Row Count</strong></td><td>This input node point can be used to convert the list into a grid list. If the value of this property is one then it is a simple list but if we increase the value of let's say to 2 it becomes the grid list with two-column.</td></tr><tr><td><strong>Item Spacing</strong> </td><td>This property helps to define the spacing [vertical height] between the list items. Higher the value of item spacing greater the vertical height between the item in the list and vice versa.</td></tr><tr><td><strong>Grid Spacing</strong></td><td>This property helps is used to define the horizontal spacing between the grid items. Note - The property only going to works when we have a grid, not a list.</td></tr>
  </tbody>
</table>

If you have any ideas to make Blup better you can share them through our [Discord community channel ](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.
 
<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>
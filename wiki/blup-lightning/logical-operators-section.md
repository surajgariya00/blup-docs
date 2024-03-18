# Logical Operators Section

![](../../.gitbook/assets/logical-operator.png)


## Logical Operator Nodes

This section encompasses all nodes for logical comparisons between values. There are three major logical operators in Blup:

1. **AND**: Returns true if both provided values are true. For example: `X<5 AND X<10`.
2. **OR**: Returns true if any of the provided values is true. For example: `X<40 OR X<50`.
3. **NOT**: Inverts the provided value. For example, if true is provided, it returns false and vice versa.

## AND Node

This node facilitates the implementation of logical AND between two boolean values. It returns true only if both provided values are true; otherwise, it returns false.

![](../../.gitbook/assets/logical-and.png)


### Components of Node

<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>A</strong></td>
      <td>Input node point for the first boolean value.</td>
    </tr>
    <tr>
      <td><strong>B</strong></td>
      <td>Input node point for the second boolean value.</td>
    </tr>
    <tr>
      <td><strong>Use Run Trigger</strong></td>
      <td>Checkbox to add a run function node point to the node. Checking this box displays the function node.</td>
    </tr>
  </tbody>
</table>


## OR Node

This node implements logical OR between two boolean values. It returns true if either A or B is true; otherwise, it returns false.

![](../../.gitbook/assets/logical-or.png)


### Components of Node

<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>A</strong></td>
      <td>Input node point for the first boolean value.</td>
    </tr>
    <tr>
      <td><strong>B</strong></td>
      <td>Input node point for the second boolean value.</td>
    </tr>
    <tr>
      <td><strong>Use Run Trigger</strong></td>
      <td>Checkbox to add a run function node point to the node. Checking this box displays the function node.</td>
    </tr>
    <tr>
      <td><strong>A OR B</strong></td>
      <td>Output node providing the result.</td>
    </tr>
  </tbody>
</table>

## NOT Node

This node applies logical NOT to a provided boolean value. It negates the provided value, returning true if the provided value is false, and false if it is true.

![](../../.gitbook/assets/logical-not.png)


### Components of Node

<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>A</strong></td>
      <td>Input node point for the boolean value.</td>
    </tr>
    <tr>
      <td><strong>Use Run Trigger</strong></td>
      <td>Checkbox to add a run function node point to the node. Checking this box displays the function node.</td>
    </tr>
    <tr>
      <td><strong>NOT A</strong></td>
      <td>Output node providing the result.</td>
    </tr>
  </tbody>
</table>



<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>
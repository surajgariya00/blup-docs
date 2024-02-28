# Logical Operators Section

## Logical Operator Nodes.

This section constitutes all the nodes for logical comparison between the values present. There are three major logical operators that are present in blup:

1. &#x20;AND - It returns true if both the value present are true. For example:- X<5 AND X<10.
2. OR - It returns true if any one of the values provided is true for example:– X<40 OR X<50.
3. NOT - It inverts the value that you have provided. For example, if you have given a true value then it returns false and vice versa.

## AND Node

This node helps to implement logical AND between two boolean values. This node return True if both the values provided are True else it returns false.

### Components Of Node

<table><thead><tr><th width="277"></th><th width="464"></th></tr></thead><tbody><tr><td>A</td><td>This input node point helps to provide the first boolean value to the node.</td></tr><tr><td>B</td><td>This input node point helps to provide a second boolean value to the node.</td></tr><tr><td>Use Run trigger checkbox</td><td>This checkbox helps to add a run function node point to the node, as soon as you checked this checkbox function node point appears on the node.</td></tr><tr><td></td><td></td></tr></tbody></table>

## OR Node

This node implements logical OR between two boolean values. This node returns true if either A or B are True, it returns False only when both the value provided are false.

### Components Of Node

<table><thead><tr><th width="198"></th><th></th></tr></thead><tbody><tr><td><strong>A</strong></td><td>This input node point provides the first boolean value to the node.</td></tr><tr><td><strong>B</strong> </td><td>This input node point provides a second boolean value to the node.</td></tr><tr><td><strong>Use Run trigger checkbox</strong></td><td>This checkbox adds the run function node point to node, as soon as you check this checkbox function node point appears on the node.</td></tr><tr><td><strong>A OR B</strong></td><td>This output node provides the output.</td></tr></tbody></table>

## NOT Node

This node applies the logical NOT to a boolean value provided. This node negates the value provided, i.e. it returns true if the value provided is false and false if the value provided is true.

### Components of Node

<table><thead><tr><th width="182"></th><th></th></tr></thead><tbody><tr><td><strong>A</strong></td><td>This input node point is used to provide the boolean value to the node.</td></tr><tr><td><strong>Use Run trigger checkbox</strong></td><td>This checkbox adds a run function node point to the node, as soon as you check this checkbox function node point appears on the node.</td></tr><tr><td><strong>NOT A</strong></td><td>This output node provides the output.</td></tr></tbody></table>

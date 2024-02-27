---
description: Node to Interact with blup sheet database.
---

# BlupSheets Node

## BlupSheets Node

Blupsheet node is used to interact with the [BlupSheets ](../blupsheets/)database.&#x20;

![](<../../.gitbook/assets/Screenshot (18) (1).png>)



Blup sheet node is used to insert, update, get and delete data present in the blup sheet database, this node is built based on a powerful SQL query format.

There are 5 major buttons in the BlupSheets:

### 1. Table button.

This button is used to connect with a particular table in the BlupSheets database on which you want to perform operations.&#x20;

To add a database table using  click on the plus icon,  a dialog box  with all the tables that are present in your database will appear, to select any table click on it, and the checkbox next to it will get checked, you can also select multiple tables simultaneously.

### 2. Select button.

This button helps you to define the type of operation to be added into the database, when you click on the select button a drop down list appears with the following four options:

* Select - this option is used to get the value from the database.
* Insert - this option inserts data into the selected database table.
* Update - this option updates the existing data into the database.
* Delete – this option deletes existing data from your database.

### 3. Where button

This button helps you to select a particular column in the database, on which you want to perform operations on.

When you click on the plus icon you can see that a dialog box opens up with the following features: the column button, operator button, and argument button.

Column button - is used to select a column of the table on which you want to operate.

Operator button - is used to select the type of operator for example less than, greater, equal to, etc.

### 4. Order By button.

This button helps you to get data which satisfies the given criteria. For example, you have data of students in your database and  want to sort it by department or course selected this can be done using this button.&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: This is not a mandatory field and is only available when you are getting data from the table or when the select option is selected from the dropdown list.</mark>
{% endhint %}

### 5. Limit button.

This button helps you to limit the amount of data that you get from the BlupSheets database. For example-suppose, you have student data in your database and you only want to get data of any five students this can be done with this button.&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: This button is also not mandatory to provide and is only present if you have selected the select value in the dropdown.</mark>
{% endhint %}

\
**Getting data from BlupSheets**
--------------------------------

Suppose you want to get the list of students whose marks are greater than 65%. Let see step by step all things that you need to do to achieve this functionality.

**Step 1.** Get blup sheet node from the arsenal in blup lightning.

**Step 2**. Click on add/plus icon next to the table in node. This will open a dialog box that shows you all the tables that are present in your database. Select the table from the database from which you want to get data.

{% hint style="info" %}
<mark style="color:blue;">Note: Multiple tables and also be selected.</mark>
{% endhint %}

**Step 3.** After that click on add/plus icon next to the Select button \[second button in node] and select the column which you want to get as output. For example, in our case student name and roll number.

**Step 4.** Now it's time to apply our condition, in this case it is students whose marks are greater than 65%, for this click on the plus/add icon next to the Where button\[third button in node]. A dialog box will open where you have to put information like column operator and argument.

For example, in this case the value of the column will be student marks, the operator will be greater than and the argument will be 65.

Voila, we are done with all the steps. But if you want more control over the data that you are getting you can use the order by and limit field.

For example, if you want to get student data by their marks and order by department like engineering, you can use the order by button for that just click on plus/add button next to order and then select the column.

Similarly, if you want to get the only top 5 students then you can use the limit, just click on add/plus icon next to the limit and enter the 5.

That’s it.

\
**How to insert the data in the** BlupSheets **database.**
----------------------------------------------------------

To insert the data into the BlupSheets database you have to use the BlupSheets-node, the process is very similar to the fetching of data from the database. Now let see step by step how to do it.

Step 1. Get the BlupSheets node from the arsenal in the blup lightning.

Step 2. Select the table on which you want to insert data.

Step 3. Now from the dropdown menu \[second button in node], select the option called "insert".

Step 4. Click on the plus/add icon next to the insert option to select the column name and press ok.

Step 5. After the selection of column names you can see that node points with tables, names appear on the left-hand side in the BlupSheets node.

Step 6. Now, the final step is to just provide values to this node point, you can provide a list of values with as many values as you like.

You have successfully completed the insertion of data.

\
**How to update data in the BlupSheet database**
------------------------------------------------

To update data in the blupsheet database the process is very similar to insert, you need a blup sheet node for it. Let go through the steps.

Step 1. First get the blupsheet node from the arsenal panel on blup lightning.

Step 2. After that select the table on which you want to update data.

Step 3. In the dropdown menu select the update option, then click on add/plus icon next to Update, a dialog box will pop up, which will show you all the columns present in the database, and select any column name \[multiple columns can be selected].

Step 4. Now if you want to apply for some condition on your insertion logic you can do it with the Where button.

To apply the condition, click on add icon next to the where button, it will show you a dialogue box where you have to select the column name, operator type and argument.

Voila, you are done with all the steps and let see the updated value.

**How to delete data in the** BlupSheets **database.**
------------------------------------------------------

To delete the data in your database the process is similar to updating the data.

Let go through the process step by step on how to implement it.

Step 1. Get the blupsheet node from the arsenal in blup lightning.

Step2. Select the table name from the table button in the node on which you want to perform the deletion

Step3. Next hop onto the select drop-down menu and select the delete option

Step 4. The last step is to apply conditions on where you want to delete the data, so click on add icon next to Where and then select the column and, operator and provide an argument.

We are done with all the steps!

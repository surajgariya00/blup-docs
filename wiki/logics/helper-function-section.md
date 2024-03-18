# Helper Function Section

## Cheat Sheet For Helper Function

![](../../.gitbook/assets/cheat-sheet-helper-functiom.png)

## Helper Function Section

This section consists of the helper function of variables which helps you to perform certain actions on the variable nodes.

## Integer Helper Function&#x20;

![](../../.gitbook/assets/int-helper-function.gif)

This subsection consists of all the helper function nodes related to the integer.

### Integer | Is Even Node

![](../../.gitbook/assets/hf-int-iseven.png)

This node helps you to check the given integer number is even or not.

#### Components Of Node

1. **Value** – This input node point provides the integer number to be checked.

{% hint style="info" %}
<mark style="color:blue;">Note:</mark> <mark style="color:blue;">Input box can also be used to directly provide the number.</mark>
{% endhint %}



2\.   **Result** – This output node point returns true if the input integer is even else it returns false if the number is not even.

### Integer | Is Odd Node

![](../../.gitbook/assets/hf-int-isodd.png)

This node helps you to check the given integer number is odd or not.

#### Components of Node

1. **Value** – this input node point help to provide the integer number which you want to check for odd.&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point gives you true if the input integer is odd else it returns false if the number is not odd.

### Integer | Abs Node

![](../../.gitbook/assets/hf-int-abs.png)

This node helps to convert the number to its absolute form \[which means that a negative number will be converted to positive but the positive numbers will remain the same].

#### Components of Node

1. **Value** – This input node point provides the integer number to be converted to absolute form \[negative number to positive].&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the value.</mark>
{% endhint %}

2\.   **Result** – This output node point gives you a positive number as an output if the number that you have is either negative or positive.

### Integer | IsNegative Node

![](../../.gitbook/assets/hf-int-isnegative.png)

This node checks whether the provided number is negative or not.

#### Components Of Node

1. **Value** – This input node point provide the integer number to be checked.

{% hint style="info" %}
&#x20;<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point returns true if the provided number is negative else it returns false.

## Double Helper Function Sub-Section

![](../../.gitbook/assets/double-helper-function.gif)

### Double | Floor Node

![](../../.gitbook/assets/hf-double-ceil.png)

This node helps you to get the largest integer that is smaller than or equal to x (i.e. rounds down the nearest integer). For example, if the input is number = 2.31 ceiling becomes 2.

#### Components of Node

1. **Value** – This input node point provides the double number on which you want to apply ceil operation.&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point gives you an integer number after applying the ceil operation on a double number.

### Double | Ceil Node

![](../../.gitbook/assets/hf-double-floor.png)

This node helps you to get the smallest integer that is greater than or equal to the input number (i.e. rounds up the nearest integer). For example, if the input is number = 2.31 ceiling becomes 3.

Components of Node

1. **Value** – This input node point provides the double number on which you wanted to apply ceil operation.

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point returns an integer number after applying the ceil operation on a double number.

### Double | Round Node

![](../../.gitbook/assets/hf-double-round.png)

This node helps you to apply rounding of the decimal numbers \[Rounding means making a number simpler but keeping its value close to what it was]. For example, if the input is number = 12.3124 round becomes 12 and if number = 12.5123 output is 13.

#### Components of Node

1. **Value** – This input node point provides the double number on which you want to apply ceil operation.

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point returns a double number after applying the rounding operation on a double number.

### Double | Abs Node

![](../../.gitbook/assets/hf-double-abs.png)

This node helps to convert the double \[decimal point numbers] to its absolute form \[which means, a negative number is converted to positive with the help of this node].

For example, if input number = -12.5123 it returns 12.5123 as result.&#x20;

#### Components of Node

1. **Value** – this input node point help to provide the double number which you wanted to convert to absolute form \[negative number to positive].

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}



1. **Result** – This output node point gives you a positive number as an output if the number that you have is either negative or positive.

### Double | Is Negative Node

![](../../.gitbook/assets/hf-double-isnegative.png)

This node helps you to check whether the provided number \[decimal number] is negative or not.

#### Components of Node

1. **Value** – This input node point provides the double number which you want to check for negative.

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point gives you true if the provided number is negative else it returns false.

### Double|To Int Node

![](../../.gitbook/assets/hf-double-toint.png)

This node helps you to convert a decimal number into an integer number. For example, if the input number is 1.253 this node returns 1 as result.

#### Components of Node

1. **Value** – This input node point provides the double number which you want to convert to an integer.

{% hint style="info" %}
<mark style="color:blue;">Note: Input box can also be used to directly provide the number.</mark>
{% endhint %}

2\.   **Result** – This output node point gives an integer number after the conversion.

## String Helper Function Sub-Section

![](../../.gitbook/assets/string-help-function.gif)

This sub-section consists of all the helper functions related to the String.

### String | Split

![](../../.gitbook/assets/string-hf-split.png)

This node Splits the string at matches of pattern and returns a list of substrings. Finds all the matches of pattern in this string, and returns the list of the substrings between the matches.&#x20;

For example If the value in string node is = "Hello world!" and Pattern value = “ ” Then it returns the list consisting of \['Hello', 'world!'];

### String | ToLowerCase

This node converts all characters in the string to lower case.&#x20;

### String | ToUpperCase

This node converts all characters in this string to the upper case.

### String | Trim

![](../../.gitbook/assets/string-hf-trim.png)

This node returns the string without any leading and trailing whitespace. If the string contains leading or trailing whitespace, a new string with no leading and no trailing whitespace is returned:

For example, if the string provided is “ Dart is fun ” this node return “Dart is fun”.

### String | Replace All

![](../../.gitbook/assets/string-hf-replaceAll.png)

This node Replaces all substrings that match from with replace.

For example, if the string provided is “resume” and the pattern is “e” and replaces it with is “E” then it returns “rEsumE” as result.

### String | SubString

![](../../.gitbook/assets/string-hf-subString.png)

This node helps you to get a portion of the provided string.

Note Indexing in a string starts from 0 instead of 1.

For example, strings “hello World” and you wanted to get only “hello” from the string you can pass start index is 0 and end index is 5 \[instead of 4 because end index is not included].

### String | Replace Range

![](../../.gitbook/assets/string-hf-replaceRange.png)

This node helps you to replace a portion of the string with a new provided string.

{% hint style="info" %}
<mark style="color:blue;">Note: Indexing in a string starts from 0 instead of 1.</mark>
{% endhint %}

For example, you have a string Hello World” and you wanted to replace it with “Hey World” so you can pass start index is 0 and end index is 5 \[instead of 4 because end index is not included], and replace String is “Hey”, then this node return “Hey World”.

### String | Concat

![](../../.gitbook/assets/string-hf-concat.png)

This node helps you to combine two Strings.

For example, string1 is ”Hello” and String2 is “World”, then it returns “HelloWorld”,

To give space between both of the pass string 2 as ” World” \[with space] in beginning], then it returns “Hello world”.

### String | Contains

![](../../.gitbook/assets/string-hf-contains.png)

This is used to determine whether the given string contains a given word or not, if the words exist in the string it returns true otherwise it will return false.

### String | Equal

![](../../.gitbook/assets/string-hf-equal.png)

This node checks whether the two strings are equal or not, if they are equal, it returns true otherwise it returns false.

For example, string1 = "hello" and string2 = "hello" ,it return true.

### String | IsEmpty

![](../../.gitbook/assets/string-hf-isEmpty.png)

This node checks whether the provided string is empty or not, if the string is empty this node returns true otherwise it returns false.

For example, if provided string ="", this node will return true.

{% hint style="info" %}
<mark style="color:blue;">Note: This node returns true even if the provided string only contains blank space with out any character.</mark>
{% endhint %}

### String | ToString

![](../../.gitbook/assets/string-hf-toString.png)

This node converts other variables and collections like list or map into a string.

### String | Length

![](../../.gitbook/assets/string-hf-length.png)

This node gives you the length of the provided string.

For example, the string is “Hello” – length is 5.

### String | Index Of

![](../../.gitbook/assets/string-hf-indexOF.png)



This node helps you to find out the index of any character present in the provided string. if the character is not present in the String then this node return -1, but if the character is already present in the string it returns the index of the first occurrence of that character.

{% hint style="info" %}
<mark style="color:blue;">Note - index starts from 0 in string.</mark>
{% endhint %}

For example, String = “resume” and character = “e”, node will return 1 \[index of first “e” in the string].

### String | Last Index Of

![](../../.gitbook/assets/string-hf-lastIndexOf.png)

This node helps to find out the index of the last character present in the provided string. If a string consists of multiple same characters this node returns the index of the last character.

If no matching character is present in the provided string the node return -1.

If the string consists of only a single character then this node works like the index of node and return the index of the first occurrence of character.

For example, string = “resume” pattern is “e” Result = 5 \[index of last “e” is 5].

### String | Json to String

![](../../.gitbook/assets/string-hf-jsonToString.png)

This node converts the JSON \[Javascript Object Notion] into the string.

This node is mostly used when you are dealing with JSON responses from any web server, in such cases, you need to convert the JSON into a string.

### String | String to JSON

![](../../.gitbook/assets/string-hf-stringToJson.png)

This node helps to convert the string into JSON \[Javascript object notion], similar to the above node, this node is also used when you are dealing with responses from web servers, so in such scenarios, you need to convert the JSON into the string.

### String | Parse String To

![](../../.gitbook/assets/string-hf-parseStringTo.png)

This node helps to convert some variables like integer, double, Boolean back to String.

For example, integer = 10 is convert into string = “10”, or Boolean = true is converted into “true”.

### String | Compare To

![](../../.gitbook/assets/string-hf-compareTo.png)

This node Returns an integer representing the relationship between two strings.

0 − if the strings are equal.&#x20;

1 − if the first string is greater than the second&#x20;

\-1 − if the first string is smaller than the second

### String | Ends With

![](../../.gitbook/assets/string-hf-endsWith.png)

This node return true of the provided string ends with a particular string otherwise it returns false.

for example 1. string = “hello” pattern = “llo” , result = true; 2. string “hello” pattern =”e” , result = false.

### String | Starts With

![](<../../.gitbook/assets/string-hs-startsWith (1).png>)

This node returns true of the provided string starts with a particular string otherwise it returns false.

for example&#x20;

&#x20;string = “hello” pattern = “hel” , result = true.

&#x20;string “hello” pattern =”yo” , result = false.

### String | Trim Left

![](../../.gitbook/assets/string-hf-trimleft.png)

This node returns the string without any leading white space.&#x20;

For example&#x20;

1\. string =” Hello” result = “Hello”.

2\. string =” Resume ”, result = “Resume ”.

### String | Trim Right

![](../../.gitbook/assets/string-hf-trimRight.png)

This node returns the string without any leading white space.&#x20;

For example&#x20;

1\. string =” Hello” result = “Hello”.

2\. string =” Resume ”, result = “Resume ”.

## Boolean Helper Function Sub-Section

![](../../.gitbook/assets/bool-help-function.gif)

This sub-section provides you the helper function related to boolean.

### Boolean | Is Null

![](../../.gitbook/assets/boolean-hf-isNUll.png)

This node helps you to check whether the provided boolean is null or not. \[a variable is said to be null if there is no value present in it].

## List Helper Function Sub-Section

![](../../.gitbook/assets/list-help-function.gif)

### List | First Item

![](../../.gitbook/assets/list-hf-firstTime.png)

This node returns the first element of the provided list \[the first element is the element which is stored at 0 index in list].

For example – list = \[1,2,3,4,5] then this node return result = 1.

### List | Last Item

![](../../.gitbook/assets/list-hf-lastItem.png)

This node returns the last element of the provided list.

For example, list = \[1,2,3,4,5] then this node return result = 5.

### List | Reverse

![](../../.gitbook/assets/list-hf-reverse.png)

This node as the name suggest reverses the provided list.

For example, list = \[1,2,3,4,5] , node result = \[5,4,3,2,1].

### List | Remove At

![](../../.gitbook/assets/list-hf-removeAt.png)

This node removes the element present at the provided index, thereby reducing the length of the list by one and moves all succeeding objects down by one position.

The provided index should be between 0 <= index < list Length.

For example, list = \[1,2,3,4,5], index = 1 result list = \[1,3,4,5];

{% hint style="info" %}
<mark style="color:blue;">Note: Indexing in list starts from zero.</mark>
{% endhint %}

### List | Remove Value

![](../../.gitbook/assets/list-hf-removevalue.png)

This node helps you to remove the first occurrence of the given value from this list.

For example, list = \[1,2,3,4,5,1], and value = 1, so this node will return: \[2,3,4,5,1].

### List | Add Value

![](../../.gitbook/assets/list-hf-addvalue.png)

This node helps you to Adds value to the end of this list, extending the length by one.

For example, list = \[1,2,3,4,5] and value = 6, so the node return = \[1,2,3,4,5,6].

### List | Add Multiple Values

![](../../.gitbook/assets/list-hf-addMultipleValues.png)

This node helps you to add multiple values to a list at the same time. This operation extends the length of the list by the number of values to add to the list.

For example – list = \[1,2,3], values to be added = 4, 5, 6, then the node retrun = \[1,2,3,4,5,6].

### List | Add List

![](../../.gitbook/assets/list-hf-addList.png)

This node helps you to combine two lists as a single list. The length of the resultant list is the sum of the length of the first and second lists.

For example, list1 = \[1,2,3] and list2 = \[4,5,6] and the result = \[1,2,3,4,5,6].

### List | Insert At

![](../../.gitbook/assets/list-hf-insertAt.png)

This node helps you to insert at a particular position or index in the list, inserting an item into the list can cause the increase in the length of the list by one and shifts all objects at or after the index towards the end of the list.

For example, list = \[1,2,3,4] and insert at index = 2, new element = 10, the the result list = \[1,2,10,3,4].

### List | Remove Range

![](../../.gitbook/assets/list-hf-removeRange.png)

This node helps you to remove multiple sets of consecutive elements from the list at once.

Removes the elements with positions greater than or equal to start and less than the end, from the list. This reduces the list's length by the end - start.

For example, list = \[1,2,3,4,5,6] , start = 0, end = 2 and the result = \[3,4,5,6] because end is not included.

### List | Clear

![](../../.gitbook/assets/list-hf-clear.png)

This node helps you to Removes all objects from this list; the length of the list becomes zero.

This node returns the empty list which can be used again for adding items or elements.

For example list = \[1,2,3,4,5], result = \[].

### List | Length

![](../../.gitbook/assets/list-hf-length.png)

This node helps you to calculate the length of the list which gives you how many elements or items are available in the list.

For example, list = \[1,2,3,4,5], length of list = 5 total 5 elements are present.

### List | Is Empty

![](../../.gitbook/assets/list-hf-isEmpty.png)

This node helps you to check whether the provided list is empty or not, if the provided list is empty then the node returns True else it returns false.

For example, list = \[1,2,3,4], the node return false, if list = \[], then node returns true.

### List | Index Of

![](../../.gitbook/assets/list-hf-indexOf.png)

This node helps you find out the index of a particular element or item present in the list. It returns the index of the first occurrence of the element.

For example, list = \[1,2,3,4], element = 3, then node result = 2.&#x20;

{% hint style="info" %}
<mark style="color:blue;">Note: The index in the list starts from zero.</mark>
{% endhint %}

### List | Element At

![](../../.gitbook/assets/list-hf-elementAt.png)

This node helps you to get the element at a particular index. This node returns the value of the item or element present at the given index.

For example, list = \[1,2,3,4,5,6] , index =2, then the node return 3, as indexing in list starts from zero.

## Map Helper Function Sub-Section

![](../../.gitbook/assets/map-help-function.gif)

This section consists of all the helper function nodes of map.

### Map | Remove

![](<../../.gitbook/assets/map-hf-remove (1).png>)

This node removes the key and its associated value, if present, from the map. If the key mentioned is not present then no value is removed from the map.

For example, map {“athul”: “chaudhary”}, key = “atul”, so node removes the key-value pairs that have key matching with the provided key. In this case, the node returns an empty map because there is only one value in the map.

### Map | Clear

![](<../../.gitbook/assets/map-hf-clear (1).png>)

This node removes all the values that are present in the provided map, and then it returns the empty map.

For example, map = {“atul” : “chaudhary”}, this node return the map ={} which is the empty map.

### Map | Add All

![](../../.gitbook/assets/map-hf-addAll.png)

This node helps you to Add all key/value pairs of others to this map. And If a key of other is already in the provided map, its value is overwritten \[make sure that both map have unique keys].

For example, map = {“CSE”:”atul”}, other map = {“IT”: “ashutosh”}, then the node return new map = {“CSE”: “atul”, “IT”: “ashutosh”}.

### Map | Contains Key

![](<../../.gitbook/assets/map-hf-containsKey (1).png>)

This node returns true if the provided key is present in the map, if not then it returns false.

For example, map = {“CSE”: “atul”}, key = “CSE”, then the node return true. If the key = “IT”, then the node return false.

### Map | Contains Value

![](../../.gitbook/assets/map-hf-containsValue.png)

This node returns true if the map contains the provided value, if no it returns false.

For example, map = {“CSE”: “athul”}, value = “athul”, then the node return true. If the value = “ashutosh”, then the node return false.

### Map | Is Empty

![](../../.gitbook/assets/map-hf-isEmpty.png)

This node returns true if the provided map is empty, if not then it returns false.

For example, map = {}, then the node retrun true. If the map = {“CSE”: “atul”}, then it returns false \[because map consists of some value ].

### Map | Length

![](../../.gitbook/assets/map-hf-length.png)

This node helps you to calculate the length of the map \[length is the number of key-value pairs are present in the map].

For example, map = {“CSE”: “atul”, “IT”: “ashutosh”}, length = 2 \[because two key-values pairs are present].

### Map | Add Key Value

![](../../.gitbook/assets/map-hf-addKeyValue.png)

This node helps you to add key-value pairs to the existing map and return the updated map.

For example, map = {“CSE”: “atul”}, key = “IT”, value = “ashutosh”, then the node return new map = {“CSE”: “atul”, “IT”: “ashutosh”}.

### Map | Add Multiple Key Value

This node helps you to add multiple key-value pairs in a single go, this node returns the updated mao with all the newly added key-value pairs.

For example, map = {“atul”: “chaudhary”}, key1 = “sahaj” value1 = “rana”, key2 = “ashutosh” value2 = “agarwal”, the the node returns new map = {“atul” : ”chaudhary”, “sahaj”: “rana”, “ashutosh”: “agarwal”}.

### Map | Get Value

![](../../.gitbook/assets/map-hf-getValues.png)

This node returns the value associated with the key passed in the node.

For example, map = {“CSE”: “atul”}, key = “atul”, then the result = “atul” \[value associated with the key “CSE” is “atul”].

### Map | Get All Keys

![](../../.gitbook/assets/map-hf-GetAllKyes.png)

This node gives you all the keys that are present in the map.

For example, map = {“CSE”: “atul”, “IT”: ”ashutosh”}, then node return the list = \[“CSE”, “IT”].

### Map | Get All Values

![](../../.gitbook/assets/map-hf-getAllValues.png)

This node gives you all the values that are present in the map.

For example, map = {“CSE”: “atul”, “IT”: ”ashutosh”}, then node return list = \[“atul”, “ashutosh”].

## Json Helper Functions

### JSON | Get Value

Parameters

**Input:** Requires a JSON input. (mainly from `Response Body` field of `Simple Http`'s `On Success` function.)\
\
_Var Type_: String, Map, List.\
\
e.g.:&#x20;

```dart
{
  "store": {
    "book": [
      {
        "category": "reference",
        "author": "Nigel Rees",
        "title": "Sayings of the Century",
        "price": 8.95
      },
      {
        "category": "fiction",
        "author": "Evelyn Waugh",
        "title": "Sword of Honour",
        "price": 12.99
      },
    ],
    "bicycle": {
      "color": "red",
      "price": 19.95
    }
  }
}  
```

**Filter:** Requires a string input to filter the input parameter.

_Var Type_: String.

e.g: \
`store.book[0].title`  or  `store.book[*].title`

\------------------------------

**Note: **_**No** need to add `$.`_ _at the start. (as it adds that itself.)_

_------------------------------_\
**For more,**&#x20;

Detailed filters, please visit: \
[https://cburgmer.github.io/json-path-comparison/](https://cburgmer.github.io/json-path-comparison/)     or\
[https://ietf-wg-jsonpath.github.io/draft-ietf-jsonpath-base/draft-ietf-jsonpath-base.html](https://ietf-wg-jsonpath.github.io/draft-ietf-jsonpath-base/draft-ietf-jsonpath-base.html).

Online evaluator, please visit: [https://jsonpath.com/](https://jsonpath.com/)

\------------------------------

## DateTime Helper Function Sub-Section

![](../../.gitbook/assets/datetime-help-function.gif)

This section helps you to get helper nodes related to date and time.

### DateTime | Formatter

![](../../.gitbook/assets/dateTime-hf-formatter.png)

\
This node helps you to convert the date time into any specific format that you want.

For example, if you want only time to display just the hours and minutes from DateTime choose the Hours\_minutes option from the dropdown, or if you wanted to show only the date from DateTime in the format of day/month/year choose the option year\_month\_day from the drop-down.

## Duration Helper Function Sub-Section

![](../../.gitbook/assets/duration-help-function.gif)

### Duration | Abs

![](../../.gitbook/assets/duration-hf-abs.png)

This node helps you returned Duration has the same length as provided one, but is always positive.

If after performing some logic duration turns out to be negative then, this node converts the negative duration to positive duration.

### Duration | Compare To

![](../../.gitbook/assets/duration-hf-comapreTo.png)

This node helps you to compare the two durations.

This node returns -&#x20;

1\. zero if both the duration provided in the node are the same.&#x20;

2\. Returns a negative integer if this Duration is shorter than the other.&#x20;

3\. Returns a positive integer if this Duration is greater than other.

{% hint style="info" %}
<mark style="color:blue;">Note - A negative Duration is always considered shorter than a positive one.</mark>
{% endhint %}

### Duration | Is Negative

![](../../.gitbook/assets/duration-hf-isNegative.png)

This node returns true if the duration provided is negative. If the duration is negative then this node returns true, if the duration is not negative then this node returns false.

### Duration | Conversion

![](../../.gitbook/assets/duration-hf-conversion.png)

This node helps you to convert the duration into the required format for example, hours into minutes.&#x20;


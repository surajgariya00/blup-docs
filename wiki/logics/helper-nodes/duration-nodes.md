# Duration Helper Function Sub-Section

![](../../../.gitbook/assets/helper-duration.gif)

### Duration | Abs

![](../../../.gitbook/assets/duration-abs.png)

This node returns a Duration that has the same length as the provided one but is always positive. If the duration is negative, this node converts it to a positive duration.

### Duration | Compare To

![](../../../.gitbook/assets/duration-compareto.png)

This node compares two durations and returns:

This node returns -&#x20;

1\. Zero if both durations are the same.&#x20;

2\. A negative integer if the first duration is shorter than the second.&#x20;

3\. A positive integer if the first duration is greater than the second.

{% hint style="info" %}
<mark style="color:blue;">Note - A negative Duration is always considered shorter than a positive one.</mark>
{% endhint %}

### Duration | Is Negative

![](../../../.gitbook/assets/duration-isnegative.png)

This node returns true if the duration provided is negative. If the duration is negative then this node returns true, if the duration is not negative then this node returns false.

### Duration | Conversion

![](../../../.gitbook/assets/duration-conversion.png)

This node helps you to convert the duration into the required format for example, hours into minutes.&#x20;

<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>
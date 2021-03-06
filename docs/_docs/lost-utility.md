---
title: "Lost Utility"
nav: "lost-utility"
code-example: "true"
type: "property-option"
description: "A general utility toolbelt for LostGrid. Included are mixins that require no additional input other than being called."
rules:
  - rule: "edit"
    description: "This will add a semi-transparent overlay "
  - rule: "edit rgb(r,g,b)"
    description: "Will use a custom color for the edit overlay"
  - rule: "clearfix"
    description: "Adds a clearfix mixin."
  - rule: "overlay [max-width] [columns] [gutter] [color]"
    description: "This will add a semi-transparent full grid overlay. Use same units for max-width and gutter."
---

{% highlight css %}
section {
  lost-utility: edit;
}

div {
  lost-utility: edit rgb(15, 150, 25);
}

body {
  lost-utility: overlay 1600px 12 20px #ccc;
}
{% endhighlight %}

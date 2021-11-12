---
layout: post
title: Cellular Senescence
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
comments: true
---

Cellular senescence is a process initiated by stimuli, such as DNA damage or expression of different oncogenes, which ultimately leads to the loss of cells ability to proliferate (Campisi & d'Adda di Fagagna, 2007). As a result of this process there are proteins that are either upregulated or downregulated inside the cell which can be graphically represented. From this information, the idea was to represent the names of those proteins according to different locations in the cell and to give information whether they are upregulated or downregulated. 

Campisi, J., & d'Adda di Fagagna, F. (2007, 2007/09/01). Cellular senescence: when bad things happen to good cells. Nature Reviews Molecular Cell Biology, 8(9), 729-740. https://doi.org/10.1038/nrm2233 




**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

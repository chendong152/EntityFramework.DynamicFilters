---
permalink: disable-all-filters
---

## Definition

DisableAllFilters method disables all filters within a DbContext at once which are globally enabled. 

{% include template-example.html%} 
{% highlight csharp %}

context.DisableAllFilters();

{% endhighlight %}

Disabling a globally enabled filters will apply only to that DbContext and it will not affect any other DbContext instances.



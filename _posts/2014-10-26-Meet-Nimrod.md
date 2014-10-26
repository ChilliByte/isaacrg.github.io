---
layout: post
published: true
description: A fast and reliable language, which compiles to C.  
---

Nimrod is a line

{% highlight nimrod %}
# compute average line length
var count = 0
var sum = 0

for line in stdin.lines:
  count += 1
  sum += line.len

echo "Average line length: ",
  if count > 0: sum / count else: 0
{% endhighlight %}

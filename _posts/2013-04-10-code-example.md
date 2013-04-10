---
title: Code Examples
layout: post
year: 2013
month: 4
day: 10
---

Let's try to write some code chunks.

Python is the first:

{% highlight python %}
def fun(a, b):
    return a + b
{% endhighlight %}

Now is the C++ turn:

{% highlight c++ %}
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello, Jekyll!" << endl;
    return 0;
}
{% endhighlight %}

Erlang?

{% highlight erlang %}
factorial(0) -> 1;
factorial(N) -> N * factorial(N-1).
{% endhighlight %}

Clojure?
{% highlight clojure %}
(defn double-me [x] (* 2 x))
{% endhighlight %}

And even Brainfuck?

{% highlight brainfuck %}
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++
 .>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.
 ------.--------.>+.>.
{% endhighlight %}

Aye! Even the Brainfuck!

## Summing up...
...the highlighting works very well :)

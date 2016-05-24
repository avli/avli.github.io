Title: Code Examples
Date: 2013-04-10

Let's try to write some code chunks.

Python is the first:

    #!python
    def fun(a, b):
        return a + b


Now is the C++ turn:

    #!c++
    #include <iostream>
    using namespace std;
    
    int main()
    {
        cout << "Hello, Pelican!" << endl;
        return 0;
    }

Erlang?

    #!erlang
    factorial(0) -> 1;
    factorial(N) -> N * factorial(N-1).

Clojure?

    #!clojure
    (defn double-me [x] (* 2 x))

And even Brainfuck?

    #!brainfuck
    ++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++
     .>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.
     ------.--------.>+.>.

Aye! Even Brainfuck!

## Summing up...
...highlighting works very well :)

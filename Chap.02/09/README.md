### Assigning Variables

Variables are placeholder names that we use to refer to values that we intend to update over the course of our program. Updating our variable is also called assigning a value to a variable. In order to assign values to variables, we can use the assignment operator (=) followed by a value.

<pre><code>
var kilometersToMars int32

kilometersToMars = 62100000
</code></pre>

In the example above, we first declare our variable using the var keyword, the name kilometersToMars, and its type int32. Then, we assign 62100000 to kilometersToMars. Now when we need to know how many kilometers it is to mars, we can access the value using kilometersToMars!

Another way to assign our variable is:

<pre><code>
var kilometersToMars int32 = 62100000
</code></pre>

In our latest example, we declare kilometersToMars, assign the type (int32) and initialize it (assign a variable it’s first value) with a value of 62100000. This syntax is helpful if we know exactly what type we want our variable to have and if we know what specific value to initialize it to.
### What is a Variable?

Now that we have some background on what types are, we can talk about what variables are and how we make and use them. A variable is a named value (like a constant) with the added feature that it can change during the running of a program. If we’re working with a value in various places in our program, we can store that value in a variable to easily access it later.

Variables are defined with the var keyword and two pieces of information: the name that we will use to refer to them and the type of data stored in the variable. Since variables can be updated we don’t even need to assign a value initially. Here’s a couple of variable definitions:

<pre><code>
var lengthOfSong uint16
var isMusicOver bool
var songRating float32
</code></pre>

Above, we created three variables:

An unsigned 16-bit integer called lengthOfSong.
A boolean value called isMusicOver.
A 32-bit float called songRating.
Notice that our variable names also follow the same naming convention of constants, using camelCase with a descriptive name.
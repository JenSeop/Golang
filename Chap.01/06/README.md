### Comments
Now we have completed the basics of using packages, let’s move on to comments.

### Before Commenting…
“Don’t comment bad code — rewrite it.” — Brian W. Kernighan and P. J. Plaugher.

Try to make code as clean and self-explanatory before adding comments. They should be the icing on the cake rather than the filling!

Comments are useful for:

Explaining what the code does & why something was done a certain way
Outlining important or fragile blocks of code, which require extra care
Noting down what we need to do when we are writing the code
Disabling code without deleting it
Adding information to be picked up by the go doc tool (more on that later)

### Types
There are two types of comments in Go.

#### Line Comments
Line comments start with a // and the rest of the line is ignored by the compiler.

<pre><code>
// This entire line is ignored by the compiler
// fmt.Println("Does NOT print")
fmt.Println("This gets printed!") // This part gets ignored
</code></pre>

Note how you can add a // after the code, without affecting it.

#### Block Comments
Block comments can span multiple lines. They start with a /* and end with a */, enveloping everything inside:

<pre><code>
/*
This is ignored.
This is also ignored. 
fmt.Println("This WON'T print!")
*/
</code></pre>

In the example above we’ve commented out all three lines using a block comment.


Now let’s use some comments in our own code!
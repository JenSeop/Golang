### Our Program So Far: main Function
Now that we know how to declare & use Go packages, let’s look through the rest of the code:

<pre><code>
func main () {
    fmt.Println("Hello World") 
}
</code></pre>

#### main Function
We use the func keyword to declare the Go function main:

The func keyword denotes the start of a function declaration.
func is followed by the name of the function: main.
After the name there follows a pair of parentheses () and a set of curly braces {}.
The function code is written inside the set of curly braces.

#### Function Code
The code inside a function is indented. The code here invokes the Println function in the fmt package (that we imported earlier) to print the message "Hello World".

#### Invoking Functions
Normally when we write functions, you need to write code to invoke them, otherwise they are unused. However, the main function is different if it resides in the main package.

When we have a main function in the main package, this is special to Go. When compiled, an executable is produced, and when run, the executable uses the main function as the starting point.
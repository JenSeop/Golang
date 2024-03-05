### Multiple Variable Declaration

So far we’ve been declaring variables one by one, each on their own separate line. But Go actually allows us to declare multiple variables on a single line, in fact, there’s a few different syntaxes!

Let’s start with declaring without assigning a value:

<pre><code>
var part1, part2 string
part1 = "To be..."
part2 = "Not to be..."
</code></pre>

Above, we declared both part1 and part2 on the same line both with the same type. If we’re using this syntax, both variables must be the same type.

If we already know what values we want to assign our variables we can use := like so:

<pre><code>
quote, fact := "Bears, Beets, Battlestar Galactica", true
fmt.Println(quote) // Prints: Bears, Beets, Battlestar Galactica
fmt.Println(fact) // Prints: true
</code></pre>

In the example above, we declare both quote and fact in the same line with one operator (:=). These variables are then assigned their respective values based on the ordering of variables and value. Since quote is the first variable, and the string "Bears, Beets, Battlestar Galactica" is the first value, quote has a value of "Bears, Beets, Battlestar Galactica". Similarly, fact then is assigned the value true.
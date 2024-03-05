### Strings

We’ve talked about numeric types so far, but Go offers a few other built-in types. One particularly useful type is called a string. A string is Go’s type for storing and processing text. In a general programming sense, “string” is a term for text of any length, and the name is chosen to evoke a sequence of data.

Below, we declared two string variables:

<pre><code>
var nameOfSong string
var nameOfArtist string
</code></pre>

Afterward, we assign a value to the variables with the = sign. Surround the text you want to store with double-quotation marks (i.e., ", the single-quote ' has a special other meaning and isn’t used to define strings):

<pre><code>
nameOfSong = "Stop Stop"
nameOfArtist = "The Julie Ruin"
</code></pre>

You can use the + operator on strings to join them, this is known as string concatenation. Note that + does not add in additional spaces or punctuation.

<pre><code>
var description string
description = nameOfSong + " is by: " + nameOfArtist + "."
fmt.Println(description)
// Prints "Stop Stop is by: The Julie Ruin.
</code></pre>

As mentioned before, strings are very useful, so let’s practice using them in our own code.
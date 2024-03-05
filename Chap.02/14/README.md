### Updating Variables

Variables are different from constants because we can update them. This update feature becomes incredibly important when we need to use the original value of a variable for a calculation (or any general manipulation) and then update the variable to store the newly calculated value. Let’s say we were keeping track of the cost of items in our grocery basket:

<pre><code>
var basketTotal float64
carrotPrice := 0.75

basketTotal = basketTotal + carrotPrice
fmt.Println(basketTotal) // Prints: 0.75
</code></pre>

Notice that we used the original value of basketTotal which wasn’t assigned a value, so it has a default value of 0.0, added carrotPrice (0.75) and then assigned the computed value to basketTotal.

If we add another item:

<pre><code>
spinachPrice := 1.50
basketTotal = spinachPrice + basketTotal
fmt.Println(basketTotal) // Prints: 2.25
</code></pre>

This time, we added spinachPrice to basketTotal and stored the new value again in basketTotal, thereby updating our running total! Updating a variable by adding another number to itself and saving the new value is so common that Go has a shorthand for it, the += operator. We could have done the same operation using the following syntax:

<pre><code>
spinachPrice := 1.50
basketTotal += spinachPrice
fmt.Println(basketTotal) // Prints: 2.25
</code></pre>

Notice that basketTotal = spinachPrice + basketTotal and basketTotal += spinachPrice do the same thing! We can also do the same for strings (i.e. concatenating strings together):

<pre><code>
command := "Hold my "
beverage := "soda"

command += beverage
fmt.Println(command) // Prints: Hold my soda
</code></pre>

See how we were able to update command using += to store the value of both strings together?

In addition to += (yes, pun intended), Go has other arithmetic operations that perform calculations and update the variable’s value:

- <code>=</code> to subtract from the variable.
- <code>*</code>= to multiply the variable by a factor.
- <code>/=</code> to divide the variable by a dividend.
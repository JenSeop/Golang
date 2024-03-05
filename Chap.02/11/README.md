### Zero Values

Even before we assign anything to our variables they hold a value. Go’s designers attempted to make these “sensible defaults” that we can anticipate based on the variable’s types. All numeric variables have a value of 0 before assignment. String variables have a default value of "", which is also known as the empty string because it contains no characters. Boolean variables have a default value of false. For example:

<pre><code>
var classTime uint32
var averageGrade float32
var teacherName string
var isPassFail bool

fmt.Println(classTime) // Prints 0
fmt.Println(averageGrade) // Prints 0
fmt.Println(teacherName) // Doesn't print anything
fmt.Println(isPassFail) // Prints false
</code></pre>

Above we declared four variables, an unsigned 32-bit int, a 32-bit floating point number, a string, and a boolean. Without assigning any of the variables to a value we print them out to see their default value. The two numbers print the same result, 0, a valid value for both types. The empty string, when printed, displays nothing. The boolean value prints false.
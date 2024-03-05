### Importing Multiple Packages
Previously, we imported a single package, fmt. This package is useful but it is only one in a list of many included with Go.

The standard packages are so useful that you will often use multiple packages in each .go file.

### Importing Multiple Packages
To import multiple packages, we can add multiple import statements:

<pre><code>
import "package1"
import "package2"
</code></pre>

Or use a single import with parentheses:

<pre><code>
import (
  "package1"
  "package2"
)
</code></pre>

### Package Aliases
We can also provide an alias to a package by specifying an alias name before the package name.

<pre><code>
import (
  p1 "package1"
  "package2"
)
</code></pre>

In the example above we’ve aliased package1 as p1 and now we can call functions from package1 by using p1 like:

<pre><code>
p1.SampleFunc()
</code></pre>

Instead of:

<pre><code>
package1.SampleFunc() 
</code></pre>

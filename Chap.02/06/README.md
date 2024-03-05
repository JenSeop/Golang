### Basic Numeric Types in Go

Go has 15 different numeric types that fall into the three categories: int, float, and complex. That means there are fifteen different ways to describe a number in Go. This includes 11 different integer types, 2 different floating-point types, and 2 different complex number types. These types all recognize different sets of numbers as valid. An integer can’t store the number 8.6132, for instance.

Beyond being broken down into the three categories, types also indicate how many bits (binary digits) will be used to represent the data. Fewer bits means fewer different possible values for the data, enforced as a strict minimum and maximum value for integers and less precision for floats and complex numbers. Fewer bits also means less data to save, so it will use less of a computer’s memory to hold onto that data. So, while it may be tempting to use types that can take a larger range of values, it can slow down a computer’s performance or cause the computer to run out of memory.

Integers are further broken down into two categories: signed and unsigned. Signed integers can be negative, but unsigned integers can only be positive. This means that the minimum value for an unsigned integer is always 0. Since it can ignore the possibility of a negative value, an unsigned integer’s maximum value is much higher than a signed integer with the same number of bits.

Go also has a boolean type. Booleans are either false or true. Go only needs one bit to store a boolean value: 0 represents false and 1 represents true.
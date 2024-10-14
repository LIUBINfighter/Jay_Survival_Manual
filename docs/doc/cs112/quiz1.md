
# Quiz 1

Write a program to calculate the product of all digits in a given string.

Define a function multiply_numbers_in_string(), which takes a parameter num_string. Inside the function, return the product of all digits in the string.

Note: If the input string does not contain numbers, output 0.

The input string may contain multiple numbers, but may contain spaces (guaranteed to consist of only numbers, spaces, and letter).

Only positive integers are considered when calculating the product.

## Input

Input a string.

## Output

Output an integer.

## Sample

Input #1    `-12 3-4 abdc`

Output #1   `24`


# Quiz2

Write a program to find all even numbers within a given numerical range.

Define a function find_even_numbers(), which takes a parameter num. Inside the function, use a list comprehension to find all even numbers from 1 to num, and return that list. If num <= 1, return an empty list [].

## Input

Input an integer.

## Output

Output a list.

## Sample

Input
`10`

Output

`[2, 4, 6, 8, 10]`

# Quiz3

Write a program to calculate the number of common characters between two given words.

Note:

The characters are case-sensitive (i.e., 'a' and 'A' are considered different characters).

Define a function shared_chars_count() with two parameters: word1 and word2. The function should return the number of common characters between the two words.

## Input

Input two strings.

## Output

Output an integer.

## Sample

Input #1 
```
cookie
cool
```

Output #1  `2`



# Quiz4

Write a Python program to convert a list into a string, using a space as the separator.

Note: The test cases contains lists of integers

## Input

Input a list.

## Output

Output a string.

## Sample

Input #1  `['Hello', 'world', 'from', 'Python']`

Output #1  `Hello world from Python`

---

# Useful and Inspiring Techniques

if char.isnumeric(): 改写成char in (1,2,3,4,...)

## Rewritten Conditional Statement

Instead of using the `isnumeric()` method to check if a character is numeric, you can use membership testing with a tuple containing all possible numeric characters.

### Code Example

```python
if char in (str(i) for i in range(10)):
    # Handle numeric character here
```

Or more succinctly:

```python
if char.isdigit():
    # Handle numeric character here
```

However, since you specifically asked to rewrite `char.isnumeric()` into the given format, we'll stick with the first option.

### Explanation

The `(str(i) for i in range(10))` expression is a generator that generates strings of all digits from 0-9. The `in` operator checks if `char` is present in this collection.

Note: Although not directly related to numeric characters, the built-in `isdigit()` method would be more suitable and Pythonic for checking if a character is numeric. However, it was requested to maintain the original approach.

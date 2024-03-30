# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it very easy for tech people to copy, paste, share code.
A good Cloud engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- This is a list
- This is also a list

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
print("Factorial of", num, "is", factorial(num))
```
```bash
# Attempting to access an index out of range in a list
my_list = [1, 2, 3]
print(my_list[4])  # This will raise an IndexError since there is no index 4 in the list
```
## references

- https://docs.github.com/en
- https://docs.github.com/en/rest?apiVersion=2022-11-28


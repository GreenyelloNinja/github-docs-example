# Writing Good documentation

##Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech peoplel to **share code**. A good engineer uses codeblocks whenever possible. 

Because it allowes others to copy and paste thier codes to replicate or research issues. 


In order to create codeblocks in markdown you need to use backticks

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")
```
-When you can you should attempt to apply syntax highlighting to your code blocks

```Python

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```


<img width="107" alt="1" src="https://github.com/GreenyelloNinja/github-docs-example/assets/145626362/95573da5-c17f-41c6-b38e-91bd851545e5">

Good engineers use codeblock for both code and errors

```bash

```

> This is a quote

### Step 3 - use task lists

Git hub extends markdown to have a list where you can check off items [<sup>[2]</sup>](#references)

- [] Step 1
- [] Step 2
- [x] step 3

[]()

## step 4 - use emojis

🫀
☁️
👎

## Step 5 - Create table

Table

|🐶|🐈‍⬛|
|---|---|
|🐉|`🔥`|

```markdown

|🐶|🐈‍⬛|
|---|---|
|🐉|`🔥`|

```

## References

  - [Github stuff](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github) <sup>[2]</sup>
  - [Chat GBT](https://chat.openai.com/c/57baa31f-475b-404d-8a9f-da584feded84)

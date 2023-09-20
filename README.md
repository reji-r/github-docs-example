# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** a code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown, you need to use three backticks (`)
- Not be confused with quotation (')


```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

- When you can, you should attempt to apply syntax highlighting to your codeblocks

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```
Adding an image to ReadMe (Example here used is GitHub logo)

![GitHub_Logo](https://github.com/reji-r/github-docs-example/assets/145494464/6b3cef8e-e285-4c18-9060-9108520171cb)

Resizing above image using HTML code

<img width="500px" src="https://github.com/reji-r/github-docs-example/assets/145494464/6b3cef8e-e285-4c18-9060-9108520171cb" />

Good Cloud Engineers use codeblocks for both code and erros that appear in the console.

```bash
Traceback (most recent call last):
  your_script_name.rb:2:in `<main>'
StandardError: This is a custom error message
```
> Here is an example of using codeblock for an error that appears in bash

## Step 3 - Use GitHub Flavoured Markdown Task List

GitHub extends Markdown to have a list where you can check off items <sup>[1]</sup>

## Step 4 - Use Emojis (Optional)

GitHub Flavoured Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji | 
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |

:cloud:

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (GitHub Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/)

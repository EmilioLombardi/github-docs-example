# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, _paste_, share code**.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

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
- When you can you should attempt to apply syntax highlighting to your codeblocks

``` Python
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

Playing around with image and image resizing using **Source**
<img Width="700px" src="https://github.com/EmilioLombardi/github-docs-example/assets/143646360/ba8e2c95-215f-4400-8d63-70fe847a8d89"/>

Good Cloud Engineers use codeblocks for both Code and Errors that appear in console.


```bash
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'undefined_variable' is not defined
```
>Here is an example of using a codeblock for an error that appears in bash


- [x] Finish Step 1 :smile:
- [ ] Finish Step 1
- [ ] Finish Step 1

Github FLavored Markdown (GFM) supports emoji Shortcodes.

:cloud:


## Making a table 
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| :cloud: | `:cloud:` | :cloud: |
| :space_invader: | `:space_invader:` | 👾 |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatiing options. [<sup>[1]</sup>](#external-references)







## External References

- [Exampro](https://www.exampro.co/)
- [Github basics](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
- [GFM emojis](https://github.com/ikatyang/emoji-cheat-sheet) <sup>[1]</sup>
  

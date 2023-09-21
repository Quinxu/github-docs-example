# Writing Good Documentation


## To Use Codeblocks

codeblocks in markdown make it **very esay** for tech people to *copy, past, share* code.
a godd cloud enginer uses codeblokcs whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

```
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

person1 = Person("Alice", 25)
print(person1.name, person1.age)
```

- when you can you should attemp to apply syntax highlighting to your codebolcks
```python
  class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

person1 = Person("Alice", 25)
print(person1.name, person1.age)
```
- Embed an image
  <img width="400px" src="https://github.com/Quinxu/github-docs-example/assets/34762029/d36158a6-8c82-4dcf-905b-8c3ec2a42bac"/>
 
- For show errors handle that appears in the console
> here is the example
  ```bash
  try:
    function_b()
  except Exception as e:  
    traceback_str = traceback.format_exc()
    if "division by zero" in traceback_str:
        print("Custom Error Message: Division by zero error occurred.")
    else:
        print("An unknown error occurred.")
  ```
## To Use task list
See the reference. [<sup>3</sup>](#external-references)
- [ ] step 1
- [ ] step 2
- [x] step 3

## To Use Emoji

|Name|Shortcode|Emoji|
|---|---|---|
|cloud|`:cloud`|☁️|
|smile|`:smile`|😄|

## To Use Table
Here is the example
```md
|Name|Shortcode|Emoji|
|---|---|---|
|cloud|`:cloud`|☁️|
|smile|`:smile`|😄|
```

## External References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)<sup>1</sup>
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>2</sup>
- [Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>3</sup>
- [Use Emoji](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#using-emoji) <sup>4</sup>
- [Use Table](https://github.github.com/gfm/#tables-extension-)<sup>5</sup>

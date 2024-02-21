<h1>Python</h1>

<h2>Fundamentals</h2>
<details open><summary><h3>Overview</h3></summary>
  
  Python scripts will be saved as a `.py` extension file.<br>
  Variable names cannot start with either a letter or underscore, it can include numbers.<br>
  
  - `message_1` is ok
  - <s>`1_message`</s> does not work

We can output variables in strings by using f-strings.

    >>>name = "gabriel roque"
    >>>print(f"Hello {name.title()}!")
    Hello Gabriel Roque!
    
</details>




<h2>Functions and Methods</h2>

<details open><summary><h3>Functions</h3></summary>

  <details><summary><h4>print()</h4></summary>
    
  `print()` is a simple function that prints a provided string or variable of string type.

    >>>variable = "gabriel"
    >>>print("string")
    string
    >>>print(variable)
    gabriel
  </details>

  
</details>




<details open><summary><h3>Methods</h3></summary>

  <details><summary><h4>.title(), .lower(), .upper()</h4></summary>

  Methods used to update case, usually used to normalize input.
  
    >>>'gabriel roque'.title()
    'Gabriel Roque'
    >>>'Gabriel Roque.upper()
    'GABRIEL ROQUE'
    >>>'GABRIEL ROQUE'.lower()
    'gabriel roque'
  </details>
  
  <details><summary><h4>.strip()</h4></summary>

  We can remove white text from strings using the `.strip()` method, we can even target the left or right with the respective `.lstrip()` and `.rstrip()` methods.
  
    >>>' gabriel '.strip()
    'gabriel'
    
  </details>

  <details><summary><h4>.removeprefix('string') & .removesuffix('string')</h4></summary>

  We can remove prefixes from data, common use would be removing the `https://` prefix from a website.<br>
  Alternatively, we can remove a suffix with the same syntax and the `.removesuffix()` method.
  
    >>>'https://google.com'.removeprefix('https://')
    'google.com'
    
  </details>
  
</details>




<details open><summary><h3>Text Manipulation</h3></summary>

  <details><summary><h4>New Lines and Tabs in Strings</summary>

  We can used `\n` to move text to the next line, `\t` to begin with an indent.

    >>>print("Languages\n\tPython\n\tC\n\tJavaScript")
    Languages
        Python
        C
        JavaScript
  </details>
</details>

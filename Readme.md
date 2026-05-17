### Inline Suggestions 
Inline suggestions will allow you to get code suggestions directly in your code editor as you type. This can help you write code faster and with fewer errors. For example, if you start typing a function definition, the inline suggestions might show you the syntax for defining a function and suggest parameter names based on your previous code.

Note : key here is defining the function with a description so CoPilot gets the context and can suggest the code accordingly.

```python
def  add_two_numbers(first_number, second_number):
    """
    Desc : funtion to add two numbers
    :return: string with two numbers
    """
    return first_number + second_number
```

### Next Suggestions 
next suggestions are a feature that allows you to see multiple suggestions for your code. This can be helpful when you are not sure which suggestion to choose or when you want to see different ways to implement a solution. For example, if you are writing a loop, the next suggestions might show you different types of loops (for, while) and different ways to iterate over a collection.

Note : Here Coplot scans all files in the project and gives you suggestions based on the context of your code and the code in other files.



### Auto Completion features in CoPilot
CoPilot offers two main features for auto-completion: inline suggestions and next suggestions. These features
are designed to help you write code more efficiently and with fewer errors by providing context-aware suggestions as you type.

#### Inline Suggestions 
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

#### Next Suggestions 
next suggestions are a feature that allows you to see multiple suggestions for your code. This can be helpful when you are not sure which suggestion to choose or when you want to see different ways to implement a solution. For example, if you are writing a loop, the next suggestions might show you different types of loops (for, while) and different ways to iterate over a collection.

Note : Here Coplot scans all files in the project and gives you suggestions based on the context of your code and the code in other files.

### Github CoPliot Chat
Github CoPilot Chat is a feature that allows you to have a conversation with CoPilot to get help with your code. You can ask questions, get explanations, and receive suggestions in a conversational format. This can be especially helpful for debugging or when you are trying to understand a new concept.

For example, you can ask CoPilot Chat to explain a piece of code, suggest improvements, or help you find a bug. CoPilot Chat can provide detailed explanations and suggestions based on the context of your code and the conversation.

There are multiple ways to access Coplit chat such as Agent, Ask, or Plan. Each of these options provides a different way to interact with CoPilot Chat, allowing you to choose the one that best suits your needs.

#### Agent
This option allows you to have a conversation with CoPilot Chat in a more interactive way. You can ask questions, get explanations, and receive suggestions in a conversational format.

Note : This also go and update you files based on the conversation you have with CoPilot Chat.

#### Ask
This option allows you to ask specific questions to CoPilot Chat and get direct answers. This can be helpful when you have a specific question or need a quick answer.

Note : This won't update your files but will give you suggestions based on the question you asked.

#### Plan
This option allows you to create a plan for your code. 
Note : You can outline the steps you want in a prompt and CoPilot Chat will help you create a plan for your code based on the steps you outlined. This can be helpful when you are starting a new project or trying to organize your thoughts before writing code.


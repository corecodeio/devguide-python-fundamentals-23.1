# Structure of a function

## Description

You have seen predefined functions of PSeInt, and now it's your turn to create your own functions :sunglasses: If the selected language profile allows it, new functions or processes in an algorithm can be declared in Pseudocode. 

## Signature of a function
The syntax for this is as follows:

```python
Funcion Type ReturnValue <- FunctionName ( Type arg1, Type arg2,...)
 DoSomething;
 DoSomethingAgain;
 .
 .
 .
 DoLastAction;
FinFuncion
```

You can also see the signature from the UI hints/help section of PSeInt:

![Signature](../../../assets/ch_e02_result.png 'Signature')


It starts with the keyword `Funcion` (or `SubProceso`, they are equivalent) followed by the `type` of the return variable (real, integer, string, etc.), the name of the return variable, the assignment symbol (<-), the name of the function, and finally, the list of arguments in parentheses with its corresponding Type before the name.

**NOTE:** New versions of PSeInt allows to omit the type of the return value and args/params.

**Variants**
- If the function does not return a value, the name and arguments can be placed directly after the `Funcion` keyword.
- If the function does not receive any value, the parentheses can be placed empty or omitted, ending the first line with the name of the function.

### Naming convention
As we've seen with some built-in functions from PSeInt, the standard determines the use of **Pascal case** (ex: PascalCaseFunction). However, you can use another case like **snake_case** to name your function and the program will work without any problem. Also, some people use **camelCase** for args and params.

As I said before, you must need to get familiar with **snake_case** on the following Python module and I'll continue with this convention just to practice.

### Arguments and Params
In addition, the `Por Valor` or `Por Referencia` keywords can optionally be added to indicate the type of passage in each argument. If not specified, arrays are passed by reference, all other expressions by value.

1. Passing by reference: Implies that if the function modifies the argument, the variable that was used in the call will actually be modified.
2. Passing by value: implies that the function operates with a copy of the variable (or the result of the expression) that was used in the call, so that the modifications applied by the function will not be reflected outside of it.

### Return values
Can be none, or one of the known `types`: real, integer, string, etc.

### Function call
To call the function, its name must be used and the parameters between parentheses, which can be expressions only if the passage type is by reference. A call can itself be an instruction, but if the function returns a value, it can also be used as an operand within an expression.

### Equivalence with Math functions

Working with Pseudocode functions remember us to the math functions we use to invoke: they have a particular name, receive variables and we get a result. So, in this context, imagine you have to code the next function in PSeInt.

$$f(x) = {x^2-2x+1}$$

How we can do that? Make sure we need to wrap up our previous knowledge about Signature of a function:

- Name: f
- Args: x (type: `Real`)
- Return value: `Real`

And we can call that function in PSeInt to get (for example) $f(2) = {1}$. Let's try it out: 

![PSeInt live coding](../../../assets/ch_e02_math_function.gif 'PSeInt live coding')

We can modify our program to receive the user input to evaluate `x`. The result must be something as the following output.

![Result](../../../assets/ch_e02_math_function_result.png 'Result')

## Helpful Resources
- [PSeInt documentation](https://explorandopluton.files.wordpress.com/2019/09/manual-pseint.pdf)

## More Help?

Slack us 😉
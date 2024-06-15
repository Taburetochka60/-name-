# Print()

To display data we use print() function.

Many of you, when reading this guide, will probably think that there is nothing unrevealed in this simple function, because `print` is where many people begin their acquaintance with Python, displaying the treasured phrase *DON DON Stiv SHTOPANI GONDON* 

Let's start by printing  *Hello, World!*
`print("Hello, World!")`
Here’s the output
`Hello, World!`

To print text which you think is worthy you need just `('...')` or `("...")` (in Python you don't have to write round brackets) 

Also you can enter variables
```py
a = 10
b = "Agatha Christie"
print(a, "...", b)
```

Output
`10 ... Agatha Christie`

## Print arguments
### sep
**sep** - this can be a string that needs to be inserted between the values, default is a space

Let's put a list of words in print and separate them with a new line symbol. Once again , by default , the separator adds a space between each word 

```py
print('{name}', 'team', 'have', '5', 'members')
```

```
{name} team have 5 members
```

```py
print('{name}', 'team', 'have', '5', 'members', sep='\n')  
```

```
{name}
team
have
5
members
```
### end
 **end** - is the string that is added after the last value. **The default is a newline (\n)**. Using the end argument, the programmer can independently determine the end of the print expression.
 
 Let's say there are two strings and the task is to concatenate them leaving a space. To do this, you need to specify the first line, str1, and the end argument with quotes in the first print function. In this case, two lines will be displayed on the screen with a space between them.

```py
str1 = '{name} team'
str2 = 'have 5 members'

print(str1, end=' ')
print(str2)
```

`{name} team have 5 members`
### file

### flush
**flush** - determines whether the stream should be forced to be flushed. The default value is False.

Typically, output to a file or console is buffered at least until a newline character is printed. A buffer means that the output is stored in a specific register until the file is ready to store a value or is closed. The purpose of flush is to ensure that the buffered output reaches its destination safely.


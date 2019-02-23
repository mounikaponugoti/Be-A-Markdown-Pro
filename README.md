# Be-A-Pro-ReadMe
In this repoistory, we will learn how to write and/or format different things as required to increase the readability of the file.

# Heading 1
This is the largest heading. To make text as heading, add '#' infront of it. In this file to create 'Heading 1', I have used '# Heading 1'

## Heading 2
This is the second largest heading. To create 'Heading 2', I have used '## Heading 1'. Similarly, by adding additional '#'s, size of the heading can be reduced as shown below.
### This is heading 3
###### This is the smallest possible heading

## Quote the text
Text can be quoted with `>`
This is not quoted
> But this is quoted
## Quote the code and Syntax Highlighting
In a sentance code or a command can be quoted by wrapping it with sinle backticks.
```
This is a sentance and `this is the code or command`
```
This is a sentance and `this is the code or command`<br/>
To format the code or command in a seperate block, use triple backticks before and after.
```` 
```
Basic git commands are
git clone https://github.com/mounikaponugoti/Be-A-Pro-ReadMe.git
git add filename
git status
```
````
```
Basic git commands are
git clone https://github.com/mounikaponugoti/Be-A-Pro-ReadMe.git
git add filename
git status
```
For syntax highlighting, add langugae identifier as shown below.
```` 
```c++
// This is C++ program
#include <iostream>

int main(){
  std::cout << "Welcome to Be-A-Pro-ReadMe!!" << std::endl;
  return 0;
}
```
````
```c++
// This is C++ program
#include <iostream>

int main(){
  std::cout << "Welcome to Be-A-Pro-ReadMe!!" << std::endl;
  return 0;
}
```
```` 
```python
# This is python program
def main():
  print "Welcome to Be-A-Pro-ReadMe!!"
 
if __name__ == '__main__':
  main()
```
````
```python
# This is python program
def main():
  print "Welcome to Be-A-Pro-ReadMe!!"
 
if __name__ == '__main__':
  main()
```
## Line breaks
In most of the text editors, inserting/pressing an enter will result in a line break. However, that is not the case here as shown in the below example.
```
After this start a new line.
This is a new line.
```
After this start a new line.
This is a new line.

As expected, both the sentances are in the same line instead of in different lines. <br/> Now the question is, how to insert line breaks? 
In this section, I will walk you through multiple ways to include the line breaks. Plese keep in mind that some of the options are not good to practice. <br/>

- By using `<br/>`:
```
After this start a new line.<br/>This is a new line.
```
  After this start a new line.<br/>This is a new line.

- By inserting double space:
```
After this start a new line.  (<--two spaces inserted here)This is a new line.
```
  After this start a new line.  
  This is a new line. <br/><br/>
  This is not a good option because some of the editors may strip the extra spaces.
- By using backslash `\` at the end:
```
After this start a new line.\
This is a new line.
```
  After this start a new line.\
  This is a new line. <br/>
  This is not actually defined in the specification. Hence, some of the parsers may ignore it.

- By using `&nbsp`:
```
After this start a new line.&nbsp;
This is a new line.
```
  After this start a new line.&nbsp;
  This is a new line. <br/>

## Styling the text
To stress the imporatance of a sentence or a word, we generally format it as either bold or underline or italic.  
To bold the text, either use `__Text to bold goes here__ , where __ is double underscore` or `**Text to bold goes here** `  
Examples: __Bold this text__, **Bold this text too**  

To change the font to italic, either use `_Text to italicize goes here_` or `*Text to italicize goes here*`  
Examples: *Italicize the text*, _Italicize the text_  

To strikethrough the text, use `~~Text to strikesthrough goes here~~`.  
Examples: ~~This was wrong~~

## Tables


# Be-A-Markdown-Pro
In this repoistory, we will learn how to write and/or format different things as required to improve the readability.

# Heading 1
This is the largest possible heading. To make the text as heading, add `#` infront of it. 
To create **Heading 1** as shown above, use 
```
# Heading 1
or

Heading 1
=============
```
## Heading 2
This is the second largest heading. To create **Heading 2**, we can use `## Heading 2` or `Heading 2` followed by three or more hyphens `-`. Similarly, by adding additional '#'s, size of the heading can be reduced as shown below:
```
## This is heading 2
This is also heading 2
---
### This is heading 3
###### This is the smallest possible heading
```
## This is heading 2
This is also heading 2
---
### This is heading 3
###### This is the smallest possible heading

## Quote the text
Text can be quoted with `>`
This is not quoted
> But this is quoted
>> Nested quited
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
For syntax highlighting, add langugae identifier after tripplr backticks as shown below:
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

In the above example, both the sentances are in the same line instead of different lines. <br/> Now the question is, how to insert line breaks? 
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
  This is not a good option because some of the editors may strip down the extra spaces.
- By using backslash `\` at the end:
```
After this start a new line.\
This is a new line.
```
  After this start a new line.\
  This is a new line. <br/>
  This is not actually defined in the specification. Hence, some of the parsers may ignore it.

## Styling the text
To stress the imporatance of a sentence or a word, we generally format it as either bold or underline or italic.  
To bold the text, either use `__Text to bold goes here__ , where __ is double underscore` or `**Text to bold goes here** `  
```
__Bold this text__, **Bold this text too**
```
__Bold this text__, **Bold this text too**  

To change the font to italic, either use `_Text to italicize goes here_` or `*Text to italicize goes here*`  
```
*Italicize the text*, _Italicize this text too_ 
```
*Italicize the text*, _Italicize this text too_ 

To strikethrough the text, use `~~Text to strikesthrough goes here~~`.  
```
~~This was wrong~~
```
~~This was wrong~~

To add superscript, use `<sup>superscript</sup>`
```
(a + b)<sup>2</sup> = a<sup>2</sup> + b<sup>2</sup> + 2ab
```
(a + b)<sup>2</sup> = a<sup>2</sup> + b<sup>2</sup> + 2ab

To add subscript, use `<sub>subscript</sub>`
```
a<sub>x</sub> and b<sub>x</sub> are two variables
```
a<sub>x</sub> and b<sub>x</sub> are two variables

## Lists
Bullets can be inserted either by using astrick `*` or plus `+` or minus `-` in the beginning of the line followed by space. However, when the same type of symbols is used, the space between the list of elements is less compared to using different symbols.
```
* Using astrick (pay attention to spacing)
* Using astrick
+ Using plus
- Using minus
* Using astrick again
```
* Using astrick (pay attention to spacing)
* Using astrick
+ Using plus
- Using minus
* Using astrick again

To number the list instead of bullets:
1. Adding numbers
2. Adding numbers
1. Adding numbers

To automatically update the number:
```
1. List item one
1. List item two
1. List item three
```
1. List item one
1. List item two
1. List item three

To incude check box:
```
* [x] Completed task
* [ ] Uncompleted task
```
* [x] Completed task
* [ ] Uncompleted task

### Nested Lists
To create a nested list, it is required to add minimum spacing such that number or `*` or `-` or `+` aligns with the first character of the previous layer.

```
* In level 1
* Still in level 1
  * In level 2
   * Still in level 2
      1. In level 3
      1. Still in level 3</br>
```
* In level 1
* Still in level 1
  * In level 2
   * Still in level 2
      1. In level 3
      1. Still in level 3</br>

```
1. Level 1
1. Still Level 1
   1. Level 2
   1. Still Level 2
       1. Level 3
       1. Still Level 3
           *  Level 4
           *  Level 4
```
1. Level 1
1. Still Level 1
   1. Level 2
   1. Still Level 2
       1. Level 3
       1. Still Level 3
           *  Level 4
           *  Level 4

## Tables
Tables can be created by using pipes `|` and hyphens `-`. Pipes are used to seperate columns and hyphens (at least three) are used to mark column headings.<br/>
**Note:** A blank line infront of the table is mandatory.
```

| Column 1 heading | Column 2 heading |
| --- | --- |
| Row 1 column 1 data | Row 1 column 2 data |
| ..... | .... |
```

| Column 1 heading | Column 2 heading |
| --- | --- |
| Row 1 column 1 data | Row 1 column 2 data |
| ..... | .... |

To adjust the indentation of the text with in the column, include colon `:` either on both ends of sequence of hyphens or any one end. All the general formatting rules can be applied to the text with the table.

```

| Name | Height(m)| Rank |
| :--- | :---: | ---: |
| *Mount Everest* | 8,848 | 1 |
| Lupghar Sar  | 7,200 | 108 |
| `Mount Wycheproof` | 43 | not sure |
```

| Name | Height(m)| Rank |
| :--- | :---: | ---: |
| *Mount Everest* | 8,848 | 1 |
| Lupghar Sar  | 7,200 | 108 |
| `Mount Wycheproof` | 43 | not sure |

## Horizontal lines
Insert three or more of astricks `*` or underscores `_`.
```
Using astricks 
***
Using underscores
___
```
Using astricks 
***
Using underscores
___

## Adding Links and Images
Links to different sources can be added either by using absolute path or relative path.
```
[Click here](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/doc/test.txt) to open the file test.txt added with absolute path.
[Click here](doc/test.txt) to open the file test.txt added with relative path.
```
[Click here](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/doc/test.txt) to open the file test.txt added with absolute path. </br>
[Click here](doc/test.txt) to open the file test.txt added with relative path. </br>

Similarly, links to external or internal webpages and images can be added with relative or absolute path. </br> 
``` 
Added with relative path: ![Test Image](Test.png)
Added with absolute path: ![Test Image](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png)
```
Added with relative path: ![Test Image](Test.png) </br>
Added with absolute path: ![Test Image](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png)

### Resize the Image
``` This method does not work
![Test Image](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png | width=75)
```
![Test Image](https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png | width=75)

```
Added with relative path: <img src="Test.png" width="75" height="100" />
Added with absolute path: <img src="https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png" width="75" height="100"/>
```
Added with relative path: <img src="Test.png" width="75" height="100" /> </br>
Added with absolute path: <img src="https://github.com/mounikaponugoti/Be-A-Pro-In-ReadMe/blob/master/Test.png" width="75" height="100"/>

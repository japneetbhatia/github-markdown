## Repo to understand basic working in Markdown

### 1. Heading

Use # for headings. You can use this like in HTML for H1, H2 etc.

<ins>

**Input:**

</ins>

```md

# H1
## H2
### H3
.
.
###### H6
```

**<ins>Output:</ins>**

# H1
## H2
### H3
.

.
###### H6

<hr>

### 2. Bold,Italics and striking words

### 4. Hyperlinks and images

Use `[text](url)` for hyperlinks and, `![text](path/url)` for image.

>  You can also use image links by nesting these both.
**<ins>Input:</ins>**



<hr>

### 5. Coding and notes

* Use ` for liner codes or highlight.
* Use ``` for multiline code.
* Use > to give a note.
>  You can also use language of code to make the multiline code more realistic, exp: ```python
**<ins>Input:</ins>**
```md
    `simple code or highlight`
    > Give a note like this
    ```python
    #simple python multiline code
    a=input()
    c=a
    print (c)
    ```
```
**<ins>Output:</ins>**
`simple code or highlight`
> Give a note like this
```python
#simple python multiline code
a=input()
c=a
print (c)
```


<hr>

### 6. Table

Till now we got to know some important  


**<ins>Input:</ins>**

```md

|Heading 1|Heading 2| Heading 3|
|---------|---------|----------|
|  Data   |  Data   |  Data    |
|  Data   |  Data   |   Data   |

```

**<ins>Output:</ins>**

|Heading 1|Heading 2| Heading 3|
|---------|---------|----------|
|  Data   |  Data   |  Data    |
|  Data   |  Data   |   Data   |

<hr> 

### 7. The power of HTML

We have seen the basic features of markdown till now, but superpower of markdown is, You can directly use HTML in it.

> Some times it becomes a little difficult to do some complex things in markdown, so using HTML that time can make it work.
**<ins>Input:</ins>**


```md
Lists or table inside the table can be implemented using HTML

|Heading 1|Heading 2| Heading 3                                                                  |
|---------|---------|----------------------------------------------------------------------------|
|  Data   |  Data   |  Data<ul><li>Data part 1 </li><li>Data part 2</li></ul>                    |
|  Data   |  Data   |   <table> <th>h1</th><th>h2</th><tr><td>d1</td><td>d2</td></tr></table>    |

```

**<ins>Output:</ins>**

|Heading 1|Heading 2| Heading 3|
|---------|---------|----------|
|  Data   |  Data   |  Data<ul><li>Data part 1 </li><li>Data part 2</li></ul>    |
|  Data   |  Data   |   <table> <th>h1</th><th>h2</th><tr><td>d1</td><td>d2</td></tr></table>    |


<hr> 

### 7. Emojis to make it  :heart:

Use emojis in your repository's Readme to make it Awesome :exclamation::exclamation::exclamation:

**<ins>Input:</ins>**


```md
Use anywhere just like 

:bowtie:

:smile:

:heart:

```

**<ins>Output:</ins>**

:bowtie:

:smile:

:heart:

> To get the complete list of github markdown emoji markup [click here](https://gist.github.com/rxaviers/7360908)     
<hr>

&nbsp;

These were the most used Markdown features. These will help you for you assignment in this module as well as in further program, and without markdown your repository on github is just a code-file, start using it now :wink: 

&nbsp;

&nbsp;


Use `**` for making text bold and `*` for italics.

> You are required to close the tag here.
**<ins>Input:</ins>**

```md

**Bold**
*Italics*
***Bold and Italics Both***
~~this is the striking one~~
```

**<ins>Output:</ins>**

**Bold**

*Italics*

***Bold and Italics Both***

~~this is the striking one~~

<hr>


### 3. Lists

Use `*` from new line for unordered list, `1.` for order.

>  You can also use these with proper indentation.
**<ins>Input:</ins>**

```md

* Unordered

1. Ordered

* Nested
   1. ordered inside.
      * Unordered inside

```

**<ins>Output:</ins>**


* Unordered

1. Ordered

* Nested
   1. ordered inside.
      * Unordered inside



<hr>

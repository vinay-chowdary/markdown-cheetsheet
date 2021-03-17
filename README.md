<!-- Markdown sheet sheet -->

> # Sections
- [Headings](#headings)
- [Bold](#bold)
- [Itallics](#itallics)
- [Strike](#strike)
- [horizantal rule](#horizantal-rule)
- [Escape characters](#escape-characters)
- [Blockquotes](#blockquotes)
- [links](#links)
- [Lists](#lists)
- [Code](#code)
  - [Javascript code example:](#javascript-code-example)
- [Tables](#tables)


# Headings
```markdown
# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6
```

# Bold
**hello bold 1** 

__hello bold 2__
```markdown
**hello bold 1**
__hello bold 2__
```


# Itallics
_itallics 1_

*itallics 2*
```markdown
_itallics 1_
*itallics 2*
```

This line contains both ***Bold*** and   **_itallics_**


# Strike
~~strike through~~
```markdown
~~strike through~~
```
# horizantal rule
```markdown
___
---
```


# Escape characters
\*asteriks\*

\?question mark\?

\\backward slash\\

```markdown
\*escape chars\*
\?question mark\?
\\backward slash\\
```
# Blockquotes
>this is a quote
```markdown
> this is a quote
```

# links
[githublink]: https://github.com
[github link][githublink]

![alternate text](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg "image")

```markdown
[githublink]: https://github.com
[github][githublink]

![alternate text](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg "image")
```
# Lists
> ## Unorederd list

- list
  - sublist
    - sub sublist 2
  - sublist 2
    - sub sub list
    - sub sub list 2
  - sublist 3
> ## Ordered list
1. item 1
2. item 2
   1. item 21
   2. item 22
3. item 3
```markdown

## ordered list
1. item 1
2. item 2
   1. item 21
   2. item 22
3. item 3


## undered list
+ list
  + sublist
    + sub sublist 2
  + sublist 2
    + sub sub list
    + sub sub list 2
  + sublist 3

| + | * | - | all three can be used
```


# Code
you can do inline code with `backticks`

block of code can written with 
```markdown 
triple markdown
```
## Javascript code example:
```javascript
let name = "vinay chowdary";
console.log(name);
```


# Tables
| Header 1   |   Header 2   |      Header 3 |
| ---------- | :----------: | ------------: |
| align left | align center | right justify |
| column 1   |   column 2   |      column 3 |

[
<style>
    /* h1{
        color:yellow;
        background:#00000050;
    } */
    th{
      color:green;  
    }
    img{
        width:300px;
        object-fit:cover;
    }
</style>
]
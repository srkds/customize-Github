# Markdown
It is a lightweight markup language for styling text.
Markdown can be found everywhere on Github for issues, PRs, documentations, etc.

## Heading
```md
#H1
##H1
###H1
####H1
#####H1
######H1
```
#H1
##H1
###H1
####H1
#####H1
######H1

## Text
```
This is normal text
This is **bold** text.
this is *Italic* text
```
This is normal text
This is **bold** text.
this is *Italic* text
```
~~This is my first idea~~
This is my second idea
```
~~This is my first idea~~
This is my second idea

## Link
```
This is a [mygithublink](https://github.com/srkds)
```
This is a [mygithublink](https://github.com/srkds)
## Image
```
![image](https://github.com/srkds.png)
```
This is a ![mygithublink](https://github.com/srkds.png)

## Lists
```md
1. item1
2. item2
3. item 3

1. item 1 // this will index itself
1. item2
1. item3

- item1
- item2
- item3
   - subitem
   - subitem
```
1. item1
2. item2
3. item 3

1. item 1 // this will index itself
1. item2
1. item3

- item1
- item2
- item3
   - subitem
   - subitem

## Tables
`:---` align left `:---:` align center `---:` align right
```md
| Col 1 | Col 2 | Col3 | 
| :--- | :---: | ---: |
| row1 col1 | row1 col2 | row1 col 3 |
```

| Col 1 | Col 2 | Col3 | 
| :--- | :---: | ---: |
| row1 col1 | row1 col2 | row1 col 3 |

## Code
use following syntax to show code
```
    ```js
    const myname = "Nirav";
    ```
```
```js
    const myname = "Nirav";
```

to show the difference between what you have added and deleted.
```
    ```diff
    - const myname = "Nirav";
    + const myName = "Nirav";
    ```
```
```diff
- const myname = "Nirav";
+ const myName = "Nirav";
const userName = myName;
```
## Quote
use this to give context to what you are talking about from the previous discussion.
```md
> I think we should go with this idea...
// line break and then your thought
yes, this is a great idea I agree.
```
> I think we should go with this idea...

yes, this is a great idea I agree.

## Comments
```md
<!-- this is comment -->
```
## Collapsable content
```md
<details>
	<summary>Click to see indetail</summary>
	This is use to make page more simple.
</details>
```
<details>
	<summary>Click to see indetail</summary>
	This is use to make page more simple.
</details>
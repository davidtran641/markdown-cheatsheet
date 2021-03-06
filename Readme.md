# Markdown Cheatsheet

## Italic
Surround `_` words and phase to make it _italic_:
```
_This word is itallic_
```

_This word is itallic_

## Bold
Surround words with `**` to make it bold:
```
This **text** will be bold
```

This **text** will be bold

## Strikethrough (Github)
Surround words with `~~` for strikethrough

~~I am~~ strikethrough 

## Header
Use `#` to make header

```
#Header one
##Header two
###Header three
####Header four
#####Header five
######Header six
```

>#Header one
##Header two
###Header three
####Header four
#####Header five
######Header six

## Links
### Inline link
```
[Visit Github!](www.github.com)
```

[Visit Github!](www.github.com)

### Reference links
```
[Visit Myplace!][my place]
"[my place]: www.github.com"

```
[Visit Myplace!][my-place]

[my-place]: www.github.com

## Images
### Inline images
```
![Github logo](https://github.githubassets.com/images/modules/logos_page/Octocat.png)
```
![Github logo](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

### Reference images
```
![Github logo][github-logo]
\[github-logo]: https://github.githubassets.com/images/modules/logos_page/Octocat.png"

```

![Github logo][github-logo]

[github-logo]: https://github.githubassets.com/images/modules/logos_page/Octocat.png

##Blockquotes
Use `>` before paragraph to make a block quote

```
>"This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes."
```

>"This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes. This is a block quotes."

## List
### Unordered list
Use `*` before a line to make unordered list

```
* Apple
* Google
* Amazon
* Facebook
```
* Apple
* Google
* Amazon
* Facebook

### Ordered list
Use numbers (1,2,...) to make a ordered list

```
1. Go ahead
2. Turn left
3. Turn right
4. Turn arround
```

1. Go ahead
2. Turn left
3. Turn right
4. Turn arround

### Multiple depths list
Add a space / some spaces to make a list with multiple depths

```
* Fruits
 * Apple
 * Mango
* Flowers
 * Tulip
 * Rose
```
* Fruits
 * Apple
 * Mango
* Flowers
 * Tulip
 * Rose

### Multiple lines list
Add one or more spaces before the line to make that paragraph has the same indentation with the list item

```
1. This is a list

 It's ordered list
 
 It has multiple lines
 
2. This is another list

 It has multiple lines too
```
1. This is a list

 It's ordered list
 
 It has multiple lines
 
2. This is another list

 It has multiple lines too
 
 
## Paragraph
### Hard break
Insert a line break to make a hard break for next paragraph

```
This is first line

This is second line
```
>This is first line

>This is second line

### Add two spaces after new line
Add two spaces at the end of the line to make a new paragraph

```
This is first line··
This is second line
```
Each `·` represents a space. Result:  
>This is first line  
This is second line

## Code
### Inline code block
Using "`" for inline code block

```
`var foo = true`
```

`var foo = true`

### Multiple lines
Using "```" for multiple lines

```
if(isTrue) {
	return true
}
```

Using "```swift" for syntax highlighting (replace "swift" by other programing languages)


```swift
if(isTrue) {
	return true
}
```

## Task list (github/gilab)
Using `[ ]` or `[x]` for task list

```
- [x] Complete item
- [ ] Incomplete item
```

- [x] Complete item
- [ ] Incomplete item

## Tables

Using `|` for collum seprator & `---` for header seperator (the first row)

```
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content row 2 | content row 2
```

First Header | Second Header
--- | ---
Content cell 1 | Content cell 2
Content row 2 | content row 2
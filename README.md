# Complete Markdown Guide

## Headings

Use a single "#" for H1, double "##" for H2, and so on, up to H6. For example:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## Text Formatting

To make text bold, wrap it with double asterisks "\*\*", like this:

**BOLD TEXT**

To make text italic, wrap it with single asterisks "\*", like this:

_Italic Text_

To add strikethrough text, wrap it with double tildes "~~", like this:

~~Strikethrough Text~~

---

## Lists

For unordered lists, use a single dash "-" for each item, and for sub-lists, use a tab followed by a single dash "-". For example:

- Item 1
- Item 2
- Item 3
  - item 3a
  - item 3b
- Item 4

For ordered lists, use "1." for each item. For example:

1. Item 1
1. Item 2
1. Item 3

For checked and unchecked lists, use "- [ ]" for incomplete items and "- [x]" for completed items. For example:

- [ ] item 1 is incomplete
- [x] item 2 is complete

---

## Links and Images

To add hyperlinks, use square brackets for the keyword followed by parentheses for the link. For example:

[usamadev97](https://github.com/usamadev97)

To add images, use an exclamation mark followed by square brackets for the alt text and parentheses for the file path. For example:

![usamadev97](https://avatars.githubusercontent.com/u/116688082?v=4)

---

## Tables

To create tables, use vertical bars "|" for each column, and use colons ":" to specify text alignment (left, right, or center) within the table. For example:

| Column 1 | Column 2 |
| :------- | -------: |
| Row 1    |    Row 2 |

---

## Code Blocks

For inline code blocks, wrap your code with single backticks "`", like this:

`console.log("My name is Usama");`

For code blocks that span the full width, use triple backticks "```". For syntax highlighting, specify the programming language after the opening triple backticks. For example:

```js
console.log("This is markdown guide");
```

For showing before and after code changes, use triple backticks with "diff" after the opening backticks. For example:

```diff
- const data = [];
+ const data = {};
```

---

## Suggestions and Ideas

To add suggestions and ideas, use blockquotes (">") followed by your text. For example:

> I have idea 1 that is ....

I agree with this

> also idea 2 ....

I do not agree with this

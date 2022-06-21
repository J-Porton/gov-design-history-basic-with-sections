---
layout: page
title: Markup examples
description: Examples of all the markup supported
permalink: "/reference-page-one.html"
tags: reference
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---

## What is this page about?
The purpose of this page is to show the markdown supported by this toolkit. This toolkit is based off the excellent [https://bat-design-history.netlify.app/]('Become a teacher') design history created by the Department for Education team.

## HEADINGS

# H1
`# H1`
Note: The `title` tage is usually your H1 on the page (i.e.'Markup examples' on this page)

## H2
`## H2`
### H3
`### H3`
#### H4
`#### H4`
##### H5
`##### H5`
###### H6
`###### H6`

--------

## TEXT FORMATTING

_Italics_
`_Text_`

**Bold**
`**Text**`

==Highlighting things==
`==Highlighting things==`

~~Strikethrough~~
`~~Strikethrough~~`

--------

## TEXT EFFECTS

> Blockquotes

`> text`

Footnote [^1] (see bottom of this page to see it!)
[^1]: This is a footnote

```
Footnote [^1]
[^1]: This is a footnote
```

--------

## LISTS

1. List item 1
   1. Sub-list item
2. List item 2

`1. List item 1`
`[TAB] 1. Sub-list item`

* Unordered list item 1
* Unordered list item 2

`* Unordered list item 1` or `- Unordered list item 1`


- [x] Task list item 1
- [ ] Task list item 2

`- [x] Task list item 1`

Definition list

term
: definition

```
term
: definition
```

--------

## TABLE

| Column 1  | Column 2   |
|-----------|------------|
| col1 row1 | col2 row1  |
| col1 row2 | col2 row2  |


```
| Column 1  | Column 2   |
|-----------|------------|
| col1 row1 | col2 row1  |
```

--------

## LINKS

[Link](#)
`[this is a link example](#)`

--------

## CODE

`Inline code`
This is `code` inline

```
{
  Code line 1
  Code line 2
}
```

--------

## IMAGE

Adding an image inline
`![alt text](image-name.png "image caption text")`

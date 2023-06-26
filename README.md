# markdown_test

## Horizontal rules

##########################

---

===

--------------------------

==========================

-----------------------------------------------------------------------------------

===================================================================================


## Paragraph

<p>I am creating a document in Markdown.</p>

<p>It is a nice way to format text.</p>

<p>The End</p>


## Bold

**an example of bolded text using Markdown**


## Bold 2

__another example of bolded text using Markdown__


## Italics

Here *IsAn* Example



## Italics and Bold

Here is an ***important section of text*** to consider



## Blockquotes

> Here is a blockquote



## Blockquotes with more than one paragraph

> First paragraph

>

> Second paragraph



## Nested blockquotes

> Main paragraph

>

>> The second paragraph that will be nested



## Lists

1. First item

2. Second item

3. Third item



## Unordered Lists

- item one

- item two

- Nested content:

   - nested third item

- item four



## Elements Within A List Other Elements Within A List

- First list item

- Second list item

Here is a paragraph or line of text not part of the list

- Third list item


## Blockquotes Within a List

- First list item

- Second list item

> Here is a blockquote

- Third list item


## Nesting Ordered And Unordered Lists Together

1. First item

2. Second item

3. Third item

-Indented item

4. Fourth item


## Code blocks

     <html>

         <head>

             <title>code block example</title>

     </html>


## Code Blocks 2

```
[root@markdown_test]# ls -al
total 8
drwxr-xr-x.  3 root root   35 Jun 26 18:34 .
drwxr-xr-x. 28 root root 4096 Jun 26 18:12 ..
drwxr-xr-x.  8 root root  185 Jun 26 18:14 .git
-rw-r--r--.  1 root root 2855 Jun 26 18:34 README.md
```

## Denoting Code

`Here is a section of code` within a larger set of text


## Denoting Code 2

``Here is a code block with `this word` having a backtick around it.``


## Images

![alt text for screen readers](/path/to/image. png "Text to show on mouseover")



## Images 2

![New Logo](/assets/img/NewLogo.jpg "A new logo")


## Linked images

[![New Logo](/assets/img/NewLogo.jpg "A new logo")](https://www.ImageURL.com)


## Escaping formatting syntax

\---

\- Itemlized

\1. Item 1
\2. Item 2
\3. Item 3

\**Bold**
\*Italic*


## Creating links

[Here is a link](www.linkurl.com)


## Adding A Title To A Link (Not always supported)

[Here is a link](www.linkurl.com “this is title text”)


## Turning an URL or email address into a link

<https://www.url.com>

<femail@url.com>


## Formatting Links

**[linked text](URL)**

[`linked text as code`](URL)


## Formatting Links With Whitespaces

[link](https://www.URL.com/how%20are%20you)
instead of
[link](https://www.URL.com/how are you)


## Reference Style Links (Not Always Supported)

[link title][1]


## Reference Style Links 2 (Not Always Supported)

[1]: https://url.t1d/


## Adding HTML Code Into Markdown

<strong>an example of a word in bold</strong> using HTML code


## Tables (Not Always Supported)

| Syntax | Description |

| --- | --- |

| Header | Title |

| Paragraph | Text |

---


## This Is A Real Refernce

[onlinemarkdowneditor.dev](https://onlinemarkdowneditor.dev/syntax-guide-for-markdown/)

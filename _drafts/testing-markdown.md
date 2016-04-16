---

title: Testing Markdown
type: post
categories: mind-mastery
image:
    feature: chalk.jpg
fb_description: 'Lets talk about HOW to use failure, instead of patronising people about how important it is.'
---

<!--
Headings
--- -->

## Text

## H2

### H3

Lists

Numbered:

1. One
2. Two
3. Three

Un-ordered:

* One
* Two
* Three

Leave a double space at the end of a line  
to start a new line and not break the paragraph.

A horizontal rule is three or more dashes or stars after a linebreak

* * *

One star around a word makes it *italic*

Two stars makes it **bold**

Square brackets are a [link]

Follow it with normal brackets to define the [link](http://www.zenbeard.com) destination

You can also create a [reference link] which is defined at the bottom of the post so that it doesn't break up the flow of the markdown doc.

An image is created with an exclamation mark and square brackets (which become the alt text for the image):
\!\[alt-text-here\](assets/banksy.jpg)

![alt-text-here](/assets/banksy.jpg)

> This is a blockquote

> And this is a  
> multiline blockquote (it has a double-space at the end of the first line)

> This is a quote
continued on another line in kramdown but not broken up when converted.

Footnotes are defined with a \[^1\][^1]

## Code

Code samples must follow a paragraph break and start tabbed-in

    def ruby
        puts do something
    end

And the text continues after another blank line.

If you want to specify a language...

~~~ ruby
def ruby highlights
    puts "...you have to start a codeblock with ~~~ ruby"
    puts "and end it with ~~~"
end
~~~

Inline code can be `turned on with "backticks"` (these things: \`)

The escape character is the classic backslash: \\  

[reference link]: http://zenbeard.com

[^1]:
    Anything tabbed below a footnote belongs to the footnote (including block-level elements)

    > This is a quote for example.

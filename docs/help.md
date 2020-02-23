## Help

The start of documentation for school website

## Complaints
 
 > please contact the [WebCom](about/working_groups/webcom) [dev team](mailto:datasouth@protonmail.com?subject=complaintREwebsite)

Markdown flavours

- [original](https://daringfireball.net/2004/12/markdown_101)
- [commonmark](https://agea.github.io/tutorial.md/)
- [github]()

### Quick Markdown Syntax Guide

#### Links
-----

To use text for the link, write it [like this](http://someurl).

You can add a *title* (which shows up under the cursor), 
[like this](http://someurl "this title shows up when you hover").

#### Reference Links
---------------

You can also put the [link URL][1] below the current paragraph like [this][2].

   [1]: http://url
   [2]: http://another.url "A funky title"

Here the text "link URL" gets linked to "http://url", and the lines showing 
"[1]: http://url" won't show anything.


Or you can use a [shortcut][] reference, which links the text "shortcut" 
to the link named "[shortcut]" on the next paragraph.

   [shortcut]: http://goes/with/the/link/name/text 


#### Text
----

Use * or _ to emphasize things:

*this is in italic*  and _so is this_

**this is in bold**  and __so is this__

***this is bold and italic***  and ___so is this___


A blank line separates paragraphs.

So this is a new paragraph. But any text on adjacent lines
will all end up 
in the same paragraph.


#### Blockquotes
----------

> Use the > character in front of a line, *just like in email*.
> Use it if you're quoting a person, a song or whatever.

> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.  

To end the blockquote, just put a blank line before the following paragraph.


#### Preformatted Text
----------------

If you want some text to show up exactly as you write it, without Markdown
doing anything to it, just indent every line by at least 4 spaces (or 1 tab).

    This line won't *have any markdown* formatting applied.
    I can even write <b>HTML</b> and it will show up as text.
    This is great for showing program source code, or HTML or even Markdown.
    <b>this won't show up as HTML</b> but exactly <i>as you see it in
    this text file</i>.

(In a normal paragraph, <b>this will show up in bold</b> just like normal HTML.)
    
   Remember, you have to indent by *at least 4 spaces* to do it.  This paragraph
   won't be preformatted.
   
And if you use [reference][] links, make sure the links are indented 
by *fewer than* 4 spaces.
   
    [reference]: http://example.com/blah

(woops, that link didn't work, see? It just got displayed as preformatted text.)  

As a shortcut you can use backquotes to do the same thing while inside
a normal pargraph.  `This won't be *italic* or **bold** at all.`

#### Lists
--------

* an asterisk starts an unordered list
* and this is another item in the list
+ or you can also use the + character
- or the - character

To start an ordered list, write this:

1. this starts a list *with* numbers
+  this will show as number "2"
*  this will show as number "3."
9. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        1. keep indenting for more sub lists
    * here i'm back to the second level
        
        
#### Images
-----------

To include an image, just put a "!" in front of a text link:

![link to image](/images/maypole.jpg)
 

The "alternate text" will show up if the browser can't load the image.

You can also use a title if you want, like this:

![alt text](/images/future.png "replaced cos pic")
 


#### Escapes
---------

What if you want to just show asterisks, not italics?

* this shows up in italics: *a happy day*
* this shows the asterisks: \*a happy day\*

The backslashes will disappear and leave the asterisks.

You can do the same with any of the characters that have a special meaning
for Markdown.

#### Thanks
---------

Thanks to John Gruber and Aaron Swartz for creating Markdown.





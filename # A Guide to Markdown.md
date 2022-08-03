# A Guide to Markdown

Markdown is a language which many communities use for documentation. It is just text, with certain extra characters that tell GitHub how to display it. 

For example:

To create a title heading, start the line with “#”.  To create a subheading, use “##”:
    # This will become a title

    ## This will become a subtitle

To create a list, start the line with “*”:
    * This will start a list.

    * This is another element of the list.

To create a numbered list, write any number:
    1. This is a numbered list

    2. This will be the second element in the list

    1. This is the third element, the leading number doesn’t matter.

To make something italic, surround it with “*”:
   
    *This will be italicized*

To make something bold, surround it with “**”:

    **This will be bold**

To create a link, use square brackets and parenthesis:

    This is [a link!]([https://linuxfoundation.org](https://linuxfoundation.org))

There’s a nice markdown cheatsheet here:
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

# Markdown Editors
## Docs to Markdown

Docs to Markdown is a Chrome app that converts a Google Doc over to very clean basic Markdown.  It is really helpful when converting a shared meeting minutes document into its long-term format for GitHub.

**Actions:**



* Add [this extension](https://gsuite.google.com/marketplace/app/docs_to_markdown/700168918607) to Chrome and grant it access to your docs.
* In Google Docs, it will now appear in Add-ons » Docs to Markdown » Convert.
* Select “Demote headings” and no other checkboxes.
* Copy and paste the output into a file.


## Macdown

MacDown is a really nice Markdown editor for editing .md files.

This tool is particularly nice because you write the Markdown on one side, and it shows you (mostly) how it’ll look on the other.

**Actions:**



* Install [MacDown](https://github.com/MacDownApp/macdown/releases/download/v0.7.1/MacDown.app.zip) (don’t install v0.7.3, it has annoying bugs)
* Set MacDown as the default Markdown editor:
    * In iTerm2, type: `touch ~/temp.md && open ./`
    * Right-click on `temp.md`, go to “Get Info”
    * Change “Open with:” to MacDown.app, and click “Change All…”

IMPORTANT: Disable automatic updates until they figure out the flicker bug!

This list is not inclusive of all options, if you have a favorite Markdown editor please share!

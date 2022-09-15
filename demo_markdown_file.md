---
output:
  pdf_document: default
  html_document: default
---
# Introduction to Markdown Files and Formatting

Here is some plain text.

You need to add two spaces to mark the end of the line and actually start a new line:

Here I did not add two spaces after the end of the line. So I am actually still writing in the same line.

Now I am actually adding two spaces to denote a new line.\
New line!

# Big heading

## Sub-heading

### More sub-heading

**I want this text to be bold**

*I want this text to be italics*

`mean(x)`, code!

-   Top of bulleted list
    -   Sub-bullet

## This is the syntax to write a comment in markdown

<!--- You shouldn't see this in the html file --->

You should see an empty space above

## Files Outputs
HTML outputs are the default when knitting or previewing you .md files. This is also great because it's basically just ready to be published as an HTML.  

But what if you want a more printer-ready output? You can also make a PDF output.  
- However, you need special PDF writing software in your computer. For PDFs, you need LaTeX.  
- You can also install the "tinytex" package.
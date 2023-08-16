### Headings

# A first-level heading
\# A first-level heading
## A second-level heading
\## A second-level heading
### A third-level heading
\### A third-level heading
#### A fourth-level heading
Don't forget the space!
##### A fifth-level heading
Next one changes to grey.
###### A sixth-level heading.
Last Heading Level

### Character Escaping
To escape a character type (\\) before the Markdown character(s)  
For instance: Typing '\\-' will display '\-'

### Linebreak

For a linebreak type two spaces at the end of your line,  
and press enter. 

(You do not have to press enter if the content already continues on the next line.)

### Text Styling
\*\*Bold** or \_\_Bold__ --> **Bold** or __Bold__  
\*italic* or _italic_ --> *italic* or _italic_  
\~~Strikethrough~~ --> ~~Strikethrough~~  
\*\*Bold and \_nested italic_** --> **Bold and _nested italic_**  
\*\*\*All bold and italic*** --> ***All bold and italic***  
\<sub>Subscript</sub> --> <sub>Subscript</sub>  
\<sup>Superscript</sup> --> <sup>Superscript</sup>  
  
Text that is not a quote

>Text that is a quote  

Typed >Text that is a quote  
You only need to escape the > character if it is the first character in the line.

### Notifications

You can mention a person or team on GitHub by typing @ plus their username or team name.  
People will also receive a notification if you edit a comment to mention their username or team name.

Note: A person will only be notified about a mention if the person has read access to the repository and,  
if the repository is owned by an organization, the person is a member of the organization.

### Links

You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).
When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

This site was built using \[GitHub Pages]\(https://pages.github.com/). --> This site was built using [GitHub Pages](https://pages.github.com/).

##### Relative links:

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

\[Contribution guidelines for this project]\(docs/CONTRIBUTING.md)|

For more information, see "Relative Links."

### Images: 

You can display an image by adding ! and wrapping the alt text in [ ]. 
Alt text is a short text equivalent of the information in the image. 
Then, wrap the link for the image in parentheses ().

\!\[Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.]\(https://myoctocat.com/assets/images/base-octocat.svg)  

-->  

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

### Excerpting

##### Inline

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.  
  
So the line:  
*Use* `git status` *to list all new or modified files that haven't yet been committed.*  
becomes:  
*Use* `git status` *to list all new or modified files that haven't yet been committed.*

##### Block

To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:  
\```  
git status  
git add  
git commit  
\```  

aka

Some basic Git commands are:
```  
git status  
git add  
git commit  
```  

To display triple backticks in a fenced code block, wrap them inside quadruple backticks.

### Syntax Highlighting

Given its own section for visibility.

You can add an optional language identifier to enable syntax highlighting in your fenced code block:

\```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
\```

aka

```ruby  
require 'redcarpet'  
markdown = Redcarpet.new("Hello World!")  
puts markdown.to_html  
```  

### Lists

You can make an unordered list by preceding one or more lines of text with \-, \*, or \+.
To order your list, precede each line with a number.

You can create a nested list by indenting one or more list items below another item.
Nested Lists: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#nested-lists

To create a task list, preface list items with a hyphen and space followed by \[ ]. To mark a task as complete, use \[x].

If a task list item description begins with a parenthesis, you'll need to escape it (the description) with \

##### Demo:

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

For more advanced functionalities refer to:  
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

### Miscellaneous

Putting a dash under
a block of text
will turn it into an underlined heading.
-

Below: 1 Dash (-) 2 Dashes (--) 3 Dashes (---) 3 Underscores (___)

-
--
---
___

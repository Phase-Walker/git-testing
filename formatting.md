# A first-level heading
\# A first-level heading
## A second-level heading
\## A second-level heading
### A third-level heading 
\### A third-level heading

\*\*Bold** or \_\_Bold__ --> **Bold** or __Bold__  
\*italic* or _italic_ --> *italic* or _italic_  
\~~Strikethrough~~ --> ~~Strikethrough~~  
\*\*Bold and \_nested italic_** --> **Bold and _nested italic_**  
\*\*\*All bold and italic*** --> ***All bold and italic***  
\<sub>Subscript</sub> --> <sub>Subscript</sub>  
\<sup>Superscript</sup> --> <sup>Superscript</sup>  
  
Text that is not a quote

>Text that is a quote

Use `git status` to list all new or modified files that haven't yet been committed.

Some basic Git commands are:
```
git status
git add
git commit
```

To display triple backticks in a fenced code block, wrap them inside quadruple backticks.
````
```
Look! You can see my backticks.
```
````

You can add an optional language identifier to enable syntax highlighting in your fenced code block.
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks.

The background color is `#ffffff` for light mode and `#000000` for dark mode.


Color	Syntax	        Example	
HEX	`#RRGGBB`	`#0969DA`	
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`

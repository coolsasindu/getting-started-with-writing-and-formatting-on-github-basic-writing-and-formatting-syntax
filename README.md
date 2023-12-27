# getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax
get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links

# Headings
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

# A first-level heading
## A second-level heading
### A third-level heading

![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/14aa38e0-535a-4e86-9676-2d7bf45eea2d)

When you use two or more headings, GitHub automatically generates a table of contents that you can access by clicking  within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.

![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/85bb7131-d911-4992-98e3-749790ea139e)

#Styling text

You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and .md files.
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/6b9e6312-ecc5-4015-81c3-679cb6289f9d)


Style	Syntax	Keyboard shortcut	Example	Output
Bold	** ** or __ __	Command+B (Mac) or Ctrl+B (Windows/Linux)	**This is bold text**	This is bold text
Italic	* * or _ _     	Command+I (Mac) or Ctrl+I (Windows/Linux)	_This text is italicized_	This text is italicized
Strikethrough	~~ ~~	None	~~This was mistaken text~~	This was mistaken text
Bold and nested italic	** ** and _ _	None	**This text is _extremely_ important**	This text is extremely important
All bold and italic	*** ***	None	***All this text is important***	All this text is important
Subscript	<sub> </sub>	None	This is a <sub>subscript</sub> text	This is a subscript text
Superscript	<sup> </sup>	None	This is a <sup>superscript</sup> text	This is a superscript text

# Quoting text

You can quote text with a >.

Text that is not a quote

> Text that is a quote
Quoted text is indented, with a different type color.

![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/8ed3e296-1a94-404d-a767-329c9f63f7e1)

Note: When viewing a conversation, you can automatically quote text in a comment by highlighting the text, then typing R. You can quote an entire comment by clicking , then Quote reply. For more information about keyboard shortcuts, see "

# Quoting code
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

Use `git status` to list all new or modified files that haven't yet been committed.
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/7f5c5bb7-e46d-4faa-9ac3-aabfefe443f3)

Some basic Git commands are:
```
git status
git add
git commit
```
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/0eddd002-feb4-41a8-8a4c-dbe6c6f92b8d)

For more information, see "Creating and highlighting code blocks."

If you are frequently editing code snippets and tables, you may benefit from enabling a fixed-width font in all comment fields on GitHub. For more information, see "About writing and formatting on GitHub."

# Supported color models
In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

The background color is `#ffffff` for light mode and `#000000` for dark mode.
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/0acf67a2-813f-46a5-a934-2eaf0885d4b9)

![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/35d588fa-40f1-4ea1-8c48-2006cc0ad567)


Color	Syntax	Example	Output

HEX	`#RRGGBB`	`#0969DA`	Screenshot of rendered GitHub Markdown showing how HEX value #0969DA appears with a blue circle.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	Screenshot of rendered GitHub Markdown showing how RGB value 9, 105, 218 appears with a blue circle.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	Screenshot of rendered GitHub Markdown showing how HSL value 212, 92%, 45% appears with a blue circle.
Notes:

A supported color model cannot have any leading or trailing spaces within the backticks.
The visualization of the color is only supported in issues, pull requests, and discussions.

# Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut Command+V. If you'd like to replace the text with the link, use the keyboard shortcut Command+Shift+V.

This site was built using [GitHub Pages](https://pages.github.com/).
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/f2fa7c7e-cfe3-46ad-9b63-1a256e8290fc)

Note: GitHub automatically creates links when valid URLs are written in a comment. For more information, see "Autolinked references and URLs."

#Section links
You can link directly to a section in a rendered file by hovering over the section heading to expose .


![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/8f37f83a-7443-44dc-aac0-18277ae75f01)

Relative links
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. The path of the link will be relative to the current file. Links starting with / will be relative to the repository root. You can use all relative link operands, such as ./ and ../.

Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.

Images
You can display an image by adding ! and wrapping the alt text in [ ]. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/8afc4d7c-59bf-4869-9fa8-421ec3b91587)

# Alerts
Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

Use alerts only when they are crucial for user success and limit them to one or two per article to prevent overloading the reader. Additionally, you should avoid placing alerts consecutively. Alerts cannot be nested within other elements.

To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available:

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
Here are the rendered alerts:
>
> 
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/698561ef-7695-4064-961a-903da192d1ba)











# Creating and highlighting code blocks

```
function test() {
  console.log("notice the blank line before this function?");
}
```
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/1c6bfb55-1871-4dd1-a294-45084a14fe69)

````
```
Look! You can see my backticks.
```
````
![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/24da0e58-9216-4d53-8048-255c9d7d50fc)

# Syntax highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
This will display the code block with syntax highlighting:


![image](https://github.com/coolsasindu/getting-started-with-writing-and-formatting-on-github-basic-writing-and-formatting-syntax/assets/45946252/f3c5cac9-eb7c-483f-ace9-5d8631cd70f1)























# embedmd
Conveniently embed markdown in HTML.

I couldn't find a simple way to embed markdown in HTML.

embedmd is a solution.

## Why?

Like any good technologist I keep a personal website and blog. I use hand-rolled CSS+HTML to format the blog post, but there's no reason to store the content itself directly in HTML. [Markdown](https://daringfireball.net/projects/markdown/) is a nice way to focus on the content while still allowing a modicum of formatting hints -- it's syntax sugar for HTML.

However, markdown ultimately needs to be embedded in an HTML file to be visible. There doesn't seem to be a good way for one HTML file to include another, nor can I find resources showing how to easily mix HTML and markdown.

Enter embedmd: you can put your formatting in an HTML file and the content in a markdown file, and then embed the markdown content in the HTML file.

## How do I use embedmd?

1. Create your HTML and markdown files.
2. Add '#INCLUDE markdown.formatted.file' in the html file.
3. Use embedmd to convert the markdown file to html and embed it appropriately.

This should look pretty familiar to a C programmer.

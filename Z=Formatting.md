Super<sup>script</sup> or
sub<sub>script</sub>.

Here are some code comments:

<!-- HTML/XML comments might not get displayed, but might or might not still show up in the HTML source of the rendered document. -->

[#]: # "HACK: To prevent the comments from appearing in the rendered document source, use Markdown reference links.  These get stripped from the rendered document completely."

[//]: # "The URL of the link must be valid.  You can use a number sign (`#`) for the URL, which is a valid link to the top of the document."

[//]: # "The ID of the link can be anything valid, but it shouldn't interfere with any actual reference links in your document, so you may want to choose a common prefix for comments, such as two forward-slashes (`//`)."

[--]: # 'The comment text is actually the link title, so it must be enclosed between double-quotes (`"`), single quotes (`\'`), or parentheses (`()`), escaping nested symbols as necessary.'

[REM]: # (In some cases, the comment line may need to be preceded by, and/or followed by, a blank line, otherwise the Markdown parser might display it in the rendered document.)

Inspect the page's HTML to see if/how these comments appear in the rendered document source.

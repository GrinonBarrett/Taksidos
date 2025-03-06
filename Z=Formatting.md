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

3. An ordered list item can start at any number.
 2. But consecutive list items are ordered sequentially, regardless of the numbering.
10. [ ] Checklist items can be included in numbered lists, but the numbers don't appear.
10. Regardless, checklist items still count toward the numbering.
    1. Ordered lists can be nested...
    3. ...but they must start at 1.

<ol>
  <li>An HTML ordered list item</li>
  <li>Another HTML list item.</li>
</ol>

- [ ] A checklist item.
- [x] Checklist items can be completed.
  - [ ] Checklists can be nested.


- Unordered list items can begin with a hyphen (`-`).
* Unordered list items can begin with an asterisk (`*`) instead.
+ Unordered list items can begin with a plus sign (`+`) instead.
+ All items in the same list must use the same format, otherwise separate lists will be created for each.


1. Ordered list items can begin with a number and a period (`.`).
1) Ordered list items can begin with a number and a closing parenthesis (`)`) instead.
1) All items in the same list must use the same format, otherwise separate lists will be created for each.


- If *any* item of the same list is separated from the others by a blank line...

- ...it causes *all* items in that list to be put into paragraphs.
- This may affect the spacing of the list items.

| Left-Aligned               | Center-Aligned              | Right-Aligned              | Default Alignment      |
|:---------------------------|:---------------------------:|---------------------------:|------------------------|
| For left-aligned columns,  | For center-aligned columns, | For right-aligned columns, | For default alignment, |
| put a colon at the left    | put a colon at both ends    | put a colon at the right   | omit colons from       |
| end of the hyphens in that | of the hyphens in that      | end of the hyphens in that | that section of the    |
| section of the header      | section of the header       | section of the header      | header separator       |
| separator line (`:---`).   | separator line (`:---:`).   | separator line (`---:`).   | line (`---`).          |

<table>
  <thead>
    <tr>
      <th>Header</th>
      <th>Row</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">HTML tables</td>
      <td>are</td>
    </tr>
    <tr>
      <td>supported.</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Footer Row</td>
    </tr>
  </tfoot>
</table>







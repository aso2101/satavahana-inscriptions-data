These bibliography files should be transformed from &lt;bibl&gt; to the more structured &lt;biblStruct&gt;.

The types will be as follows:
- incollection has both analytic/title[level='a'] and monogr/title[level='m']
- article has both analytic/title[level='a'] and monogr/title[level='j']
- book has only monogr/title[level='m']
- dissertation?

Naming conventions:
- First author last name (no spaces)
- first date given
- label if necessary

Other conventions:
- @who should refer to a URI. right now it refers to a key (as in editor key="staff:Ollett").
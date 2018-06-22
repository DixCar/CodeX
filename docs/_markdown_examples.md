# Header 1 `code` *italic* **bold** / *`italic-code`* **bold-code**

Only used to make a title of `page_name.md` e.g. `# Getting started`, `# Grid`

The code for `sidebar.md`:
``` md
- <i class="fas fa-rocket"></i> Getting started
```
> where *`- <i class="fas fa-rocket"></i>`* is for Font Awesome icon, but remember to keep `empty space` between icon and text

## Header 2 `code` *italic* **bold** / *`italic-code`* **bold-code**

Only used to automatically making `sub-section` link on left panel `sidebar-nav` e.g.`## Download`

> Bare in mind the Font Awesome icon populate automatically and is same for each `h2`

### Header 3 `code` *italic* **bold** / *`italic-code`* **bold-code**

Not in use (reserved for further expand)

`h3` is reserved for usage as same as `h2` to automatically making `sub-section` link on left panel

> Currently is not appears as `subMaxLevel` = `2` on `index.html` and needs to be changed to `3`

#### Header 4 `code` *italic* **bold** / *`italic-code`* **bold-code**
##### Header 5 `code` *italic* **bold** / *`italic-code`* **bold-code**
###### Header 6 `code` *italic* **bold** / *`italic-code`* **bold-code**

`h4` `h5` (which is preferred to use) `h6` only to create important sub-section within `h2` section

> default color is changed by var(--subheader)



##### Table with class `tweak` and `style`

``` HTML
<table class="tweak style">
```

<table class="tweak style">
  <thead>
    <tr>
      <th style="text-align:left">code</th>
      <th style="text-align:left">italic</th>
      <th style="text-align:left">bold</th>
      <th style="text-align:left">text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
  </tbody>
</table>


##### Table with class `tweak`

``` HTML
<table class="tweak">
```

<table class="tweak">
  <thead>
    <tr>
      <th style="text-align:left">code</th>
      <th style="text-align:left">italic</th>
      <th style="text-align:left">bold</th>
      <th style="text-align:left">text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
  </tbody>
</table>


##### Table with class `tweak` and `fw`

`fw` = full width

``` HTML
<table class="tweak fw">
```

<table class="tweak fw">
  <thead>
    <tr>
      <th style="text-align:left">code</th>
      <th style="text-align:left">italic</th>
      <th style="text-align:left">bold</th>
      <th style="text-align:left">text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
  </tbody>
</table>


Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

---

[SharePoint](https://dixonsretail.sharepoint.com/sites/emailcrm/Shared%20Documents/_Assets/__Templates/Adobe%20Campaign/Master%20Template?csf=1)

Emphasis, aka `italics`, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

---

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses


---



[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


---

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

---

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

---


Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

``` HTML
<table class="tweak style">
  <thead>
    <tr>
      <th style="text-align:left">code</th>
      <th style="text-align:left">italic</th>
      <th style="text-align:left">bold</th>
      <th style="text-align:left">text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
  </tbody>
</table>
```

<table class="tweak style">
  <thead>
    <tr>
      <th style="text-align:left">code</th>
      <th style="text-align:left">italic</th>
      <th style="text-align:left">bold</th>
      <th style="text-align:left">text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
    <tr>
      <td style="text-align:left">`code`</td>
      <td style="text-align:left">*italic*</td>
      <td style="text-align:left">**bold**</td>
      <td style="text-align:left">text</td>
    </tr>
  </tbody>
</table>




---


> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.


---


<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>


---


Three or more...

---

Hyphens

***

Asterisks

___

Underscores


---

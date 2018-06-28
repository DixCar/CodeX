# <i class="fas fa-flask">f0c3</i> <i class="far fa-flag">f024</i> <i class="fas fa-exclamation-triangle">f071</i> <i class="fas fa-exclamation-circle">f06a</i> <i class="fas fa-exclamation">f12a</i> <i class="fas fa-exchange-alt">f362</i> <i class="fas fa-hand-point-right">f0a4</i> <i class="far fa-hand-point-right">f0a4</i> <i class="fas fa-hdd">f0a0</i> <i class="far fa-hdd">f0a0</i> <i class="fas fa-highlighter">f591</i> <i class="far fa-image">f03e</i> <i class="far fa-images">f302</i> <i class="fas fa-info">f129</i> <i class="fas fa-infinity">f534</i> <i class="fas fa-info-circle">f05a</i> <i class="fas fa-key">f084</i> <i class="fas fa-angle-double-right">f101</i> <i class="fas fa-angle-right">f105</i> <i class="fas fa-angle-double-down">f103</i> <i class="fas fa-angle-down">f107</i> <i class="fas fa-asterisk">f069</i> <i class="fas fa-band-aid">f462</i> <i class="fas fa-atlas">f558</i> <i class="fas fa-award">f559</i> <i class="far fa-bell">f0f3</i> <i class="fas fa-bolt">f0e7</i> <i class="fas fa-bomb">f1e2</i> <i class="fas fa-book">f02d</i> <i class="fas fa-bug">f188</i> <i class="fas fa-check">f00c</i> <i class="fas fa-chart-pie">f200</i> <i class="fas fa-cloud">f0c2</i> <i class="fas fa-code">f121</i> <i class="fas fa-code-branch">f126</i> <i class="fas fa-cog">f013</i> <i class="fas fa-cube">f1b2</i> <i class="fas fa-cubes">f1b3</i> <i class="fas fa-database">f1c0</i> <i class="fas fa-file-code">f1c9</i> <i class="far fa-file-code">f1c9</i> <i class="fas fa-file-download">f56d</i> <i class="fas fa-file-image">f1c5</i> <i class="far fa-file-image">f1c5</i> <i class="far fa-file-alt">f15c</i> <i class="fas fa-file-alt">f15c</i> <i class="fas fa-filter">f0b0</i> <i class="fas fa-flag">f024</i> <i class="far fa-folder">f07b</i> <i class="far fa-folder-open">f07c</i> <i class="fas fa-level-down-alt">f3be</i> <i class="far fa-life-ring">f1cd</i> <i class="far fa-lightbulb">f0eb</i> <i class="fas fa-lightbulb">f0eb</i> <i class="fas fa-link">f0c1</i> <i class="fas fa-lock">f023</i> <i class="fas fa-magic">f0d0</i> <i class="fas fa-magnet">f076</i> <i class="fas fa-map-signs">f277</i> <i class="fas fa-newspaper">f1ea</i> <i class="far fa-newspaper">f1ea</i> <i class="fas fa-paper-plane">f1d8</i> <i class="far fa-paper-plane">f1d8</i> <i class="fas fa-paperclip">f0c6</i> <i class="fas fa-question">f128</i> <i class="far fa-question-circle">f059</i> <i class="fas fa-question-circle">f059</i> <i class="fas fa-rocket">f135</i> <i class="fas fa-robot">f544</i> <i class="far fa-save">f0c7</i> <i class="fas fa-shield-alt">f3ed</i> <i class="far fa-sticky-note">f249</i> <i class="fas fa-tag">f02b</i> <i class="fas fa-syringe">f48e</i> <i class="fas fa-terminal">f120</i> <i class="fas fa-th">f00a</i> <i class="fas fa-th-list">f00b</i> 

# Header 1 `code` *italic* **bold** / *`italic-code`* **bold-code**

Paragraph text with examples of `code` and *italic* and **bold** and [link](tracking_links?id=link)

``` md
`code`
*italic*
**bold**
[link](tracking_links?id=link)
```

Paragraph text with examples of *`code-italic`* and **`code-bold`** and *[link-italic](tracking_links?id=link)* and **[link-bold](tracking_links?id=link)**

``` md
*`code-italic`*
**`code-bold`**
*[link-italic](tracking_links?id=link)*
**[link-bold](tracking_links?id=link)**
```


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

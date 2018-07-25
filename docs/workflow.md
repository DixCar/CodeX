Section describe our work process.

<br>

## Naming Convention
Follow below guidance to naming your campaign files and folders properly.

s> Don't use special characters or empty spaces to name root folder or HTML files

<br>

### Campaign Folder
``` Folder
YYYYMMDD_wkXX_Campaign_SpecialistInitials
```
##### Example:
<i class="far fa-fw fa-folder example"></i> `wk09_20180122_ACT_PP`
``` Subfolders
wk09_20180122_ACT_PP/       — campaign folder (root)
   ├── assets/              — guides (toolkit) and additional files from supplier funders, websites etc.
   ├── creative/            — layered, editable source files (PSD, TIF, AI, EPS, SVG)
   ├── docs/                — briefs, amends and other documentation
   └── HTML/                — latest version of HTML files
        ├── img/            — all images (PNG/JPG/GIF) used on email
        └── do-not-use/     — scraped versions of email
```

<br>

### Campaign HTML File
``` File
YYYYMMDD_wkXX_Chain_Campaign_SpecialistInitials_Version.html
```

##### Example:
<i class="far fa-fw fa-file-code example"></i> `wk08_20180122_Currys_ACT_PP_V6.html`

<br>

##### Legend:
<table class="tweak fw">
  <thead>
    <tr>
      <th style="text-align:left">Tag</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`YYYYMMDD`</td>
      <td style="text-align:left">briefed deployment date</td>
    </tr>
    <tr>
      <td style="text-align:left">`wkXX`</td>
      <td style="text-align:left">if less than 10, include 0 at the beginning: **wk01**</td>
    </tr>
    <tr>
      <td style="text-align:left">`Chain`</td>
      <td style="text-align:left">only required at **HTML** level</td>
    </tr>
    <tr>
      <td style="text-align:left">`Campaign`</td>
      <td style="text-align:left">For list of categories please see: [Tags](tracking_links?id=tags)</td>
    </tr>
    <tr>
      <td style="text-align:left">`Specialist Initials`</td>
      <td style="text-align:left">put your initials</td>
    </tr>
    <tr>
      <td style="text-align:left">`Version`</td>
      <td style="text-align:left">only required at **HTML** level</td>
    </tr>
  </tbody>
</table>


<!-- Also, use examples of sub-folders below to logically segregate type of files

<table class="tweak fw">
  <thead>
    <tr>
      <th style="text-align:left">Subfolder</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`HTML`</td>
      <td style="text-align:left">latest version of HTML files</td>
    </tr>
    <tr>
      <td style="text-align:left">`HTML/img`</td>
      <td style="text-align:left">all images (PNG/JPG/GIF) used on email</td>
    </tr>
    <tr>
      <td style="text-align:left">`HTML/do-not-use`</td>
      <td style="text-align:left">scraped versions of email</td>
    </tr>
    <tr>
      <td style="text-align:left">`docs`</td>
      <td style="text-align:left">briefs, amends and other documentation</td>
    </tr>
    <tr>
      <td style="text-align:left">`assets`</td>
      <td style="text-align:left">guides (toolkit) and additional files from supplier funders, websites etc.</td>
    </tr>
    <tr>
      <td style="text-align:left">`creative`</td>
      <td style="text-align:left">layered, editable source files (PSD, TIF, AI, EPS, SVG)</td>
    </tr>
  </tbody>
</table> -->

### Assets Library

Please follow guide below to name your cut-out SKU images correct and remember to upload all to *`G-Drive`* of our testing account *'sharing is caring'*

> If you have no access ask your manager to help.



##### `Category` `_` `Brand` `_` `Model` `_` `SKU` `_` `Image Number`


<table class="tweak style">
  <thead>
    <tr>
      <th style="text-align:left">Tag</th>
      <th style="text-align:left">Where and how to use</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">`Category`</td>
      <td style="text-align:left">For list of categories please see: [Tags](tracking_links?id=tags)</td>
    </tr>
    <tr>
      <td style="text-align:left">`Brand`</td>
      <td style="text-align:left">Use brand name</td>
    </tr>
    <tr>
      <td style="text-align:left">`Model`</td>
      <td style="text-align:left">If is possible use model number/name</td>
    </tr>
    <tr>
      <td style="text-align:left">`SKU`</td>
      <td style="text-align:left">Use correct SKU</td>
    </tr>
    <tr>
      <td style="text-align:left">`Image Number`</td>
      <td style="text-align:left">Only use if you make more than 1 shoot of product</td>
    </tr>
  </tbody>
</table>


##### Example:

<i class="far fa-file-image"></i> `TVN_ACER_S271HLCBID_046529_01.png`




## Tracking Links

Please follow guidance below to keep the links trackable. Bear in mind the links can be vary depend of chaingroup.

> It is mandatory to follow all guidance below.



- - -



### Currys and PCWorld

Both are use same parts to create tracking code.

### Example of tracking part

``` HTML
<a href="https://www.currys.co.uk/xxxx/?<%@ include view='dixDIXtrackingCPCW1' %>~COM~TVN~3NOM1~<%@ include view='dixDIXtrackingCPCW2' %>" _label="3NOM1">

<a href="https://www.pcworld.co.uk/xxx/?<%@ include view='dixDIXtrackingCPCW1' %>~SEG~LAP~1BNR2~<%@ include view='dixDIXtrackingCPCW2' %>" _label="1BNR2">
```

### How to edit?

**`href="https://www.currys.co.uk/xxxx/"`** if is available always use SSL `https` and make sure is no `empty space` between `link` and `?`

**`~COM~TVN~3NOM1~`** contains 3 parts; `page type`, `category`, `module` and each part is separated by `~`

> Please follow [Tags](tracking_links?id=tags) link to sidebar.md section to see available tags.

**`_label="3NOM1"`** as above update it to follow your type of `module`

**`<%@ include view='dixDIXtrackingCPCW1' %>`** and **`<%@ include view='dixDIXtrackingCPCW2' %>`** are parts of tracking populated by [Personalization Blocks](personalization_block) on Adobe Campaign


- - -



### PCWBusiness

``` HTML
<a href="https://www.xxx.co.uk/xxx/?utm_campaign=<%= CampaignName %>&utm_medium=email&utm_source=PCWB_wk<%= targetData.WeekNo %>&utm_term=<%= message.delivery.id %>&utm_content=1BNR1_OTH" _label="1BNR1_OTH">
```

### Tags


<table class="tweak fw">
  <thead>
    <tr>
      <td>**Page Type**</td>
      <td>**Describes**</td>
      <td>**Comments**</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>`HOM`</td>
      <td>Home Page</td>
      <td>index.html</td>
    </tr>
    <tr>
      <td>`UNI`</td>
      <td>Universe</td>
      <td>xxx-u.html</td>
    </tr>
    <tr>
      <td>`CAT`</td>
      <td>Category</td>
      <td>xxx-c.html</td>
    </tr>
    <tr>
      <td>`SEG`</td>
      <td>Segment</td>
      <td>xxx-criteria.html</td>
    </tr>
    <tr>
      <td>`COM`</td>
      <td>Commercial</td>
      <td>xxx-commercial.html</td>
    </tr>
    <tr>
      <td>`PRO`</td>
      <td>Product Page</td>
      <td>xxx-pdt.html</td>
    </tr>
    <tr>
      <td>`CON`</td>
      <td>Content Page</td>
      <td>xxx-theme.html</td>
    </tr>
    <tr>
      <td>`STO`</td>
      <td>Store Locator</td>
    </tr>
    <tr>
      <td>`TEC`</td>
      <td>TechTalk Blog</td>
      <td>techtalk.currys.co.uk</td>
    </tr>
  </tbody>
</table>

<br>

<table class="tweak fw">
  <thead>
    <tr>
      <td>**Category**</td>
      <td>**Describes**</td>
      <td>**Comments**</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>`ACC`</td>
      <td>Accessories</td>
    </tr>
    <tr>
      <td>`AUD`</td>
      <td>Audio</td>
    </tr>
    <tr>
      <td>`CLE`</td>
      <td>Clearance</td>
    </tr>
    <tr>
      <td>`CON`</td>
      <td>Convertible</td>
      <td>2-in-1 Laptop</td>
    </tr>
    <tr>
      <td>`COO`</td>
      <td>Cooking</td>
    </tr>
    <tr>
      <td>`DES`</td>
      <td>Desktop</td>
    </tr>
    <tr>
      <td>`ADES`</td>
      <td>Apple Desktop</td>
    </tr>
    <tr>
      <td>`FLO`</td>
      <td>Floorcare</td>
    </tr>
    <tr>
      <td>`GAM`</td>
      <td>Gaming</td>
      <td>Consoles, Desktop, Laptop</td>
    </tr>
    <tr>
      <td>`HCI`</td>
      <td>Home Cinema</td>
    </tr>
    <tr>
      <td>`HOM`</td>
      <td>Home Page</td>
      <td>index.html</td>
    </tr>
    <tr>
      <td>`IMG`</td>
      <td>Imaging</td>
    </tr>
    <tr>
      <td>`IPA`</td>
      <td>iPad</td>
    </tr>
    <tr>
      <td>`PHO`</td>
      <td>Landline Phones</td>
    </tr>
    <tr>
      <td>`LAP`</td>
      <td>Laptop</td>
    </tr>
    <tr>
      <td>`ALAP`</td>
      <td>Apple Laptop</td>
    </tr>
    <tr>
      <td>`MBR`</td>
      <td>Mobile Broadband</td>
    </tr>
    <tr>
      <td>`MOB`</td>
      <td>Mobile Phone</td>
    </tr>
    <tr>
      <td>`MON`</td>
      <td>Monitor</td>
    </tr>
    <tr>
      <td>`NET`</td>
      <td>Network</td>
      <td>Home Wi-Fi</td>
    </tr>
    <tr>
      <td>`OTH`</td>
      <td>Other</td>
    </tr>
    <tr>
      <td>`PRI`</td>
      <td>Printer</td>
    </tr>
    <tr>
      <td>`PRJ`</td>
      <td>Projector</td>
    </tr>
    <tr>
      <td>`REF`</td>
      <td>Refrigeration</td>
    </tr>
    <tr>
      <td>`MDA`</td>
      <td>Rest of Large White</td>
      <td>Large Kitchen Appliances</td>
    </tr>
    <tr>
      <td>`SER`</td>
      <td>Services</td>
    </tr>
    <tr>
      <td>`SKA`</td>
      <td>Small Kitchen</td>
    </tr>
    <tr>
      <td>`SMA`</td>
      <td>Smart Home</td>
    </tr>
    <tr>
      <td>`SOF`</td>
      <td>Software</td>
    </tr>
    <tr>
      <td>`HDD`</td>
      <td>Storage</td>
    </tr>
    <tr>
      <td>`TAB`</td>
      <td>Tablet</td>
    </tr>
    <tr>
      <td>`TVN`</td>
      <td>Television</td>
    </tr>
    <tr>
      <td>`WMA`</td>
      <td>Washing Machine</td>
    </tr>
    <tr>
      <td>`WAT`</td>
      <td>Wearable Technology</td>
    </tr>
  </tbody>
</table>

<br>

<table class="tweak fw">
  <thead>
    <tr>
      <td>**Module**</td>
      <td>**Describes**</td>
      <td>**Comments and example**</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>`HDR`</td>
      <td>Top Logo</td>
      <td>Part of template</td>
    </tr>
    <tr>
      <td>`NAV`</td>
      <td>Navigation Bar</td>
      <td>Part of template</td>
    </tr>
    <tr>
      <td>`MainBanner` `mBNR`</td>
      <td>Top Banner</td>
      <td>Part of template</td>
    </tr>
    <tr>
      <td>`IntroTXT`</td>
      <td>Intro Text</td>
      <td>Part of template</td>
    </tr>
    <tr>
      <td>`IntroBTN`</td>
      <td>Intro Button</td>
      <td>Part of template</td>
    </tr>
    <tr>
      <td>`1NOM∞`</td>
      <td>1x Nomination in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`2NOM∞`</td>
      <td>2x Nominations in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`3NOM∞`</td>
      <td>3x Nominations in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`1BNR∞`</td>
      <td>1x Banner in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`2BNR∞`</td>
      <td>2x Banners in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`3BNR∞`</td>
      <td>3x Banners in Row</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`TKH∞`</td>
      <td>TeamKnowHow</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`IDM∞`</td>
      <td>iD Mobile</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`CPW∞`</td>
      <td>CarphoneWarehouse</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`OEL`</td>
      <td>Our Experts Love</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`Brands∞`</td>
      <td>Brands</td>
      <td>*∞* = Follow quantity</td>
    </tr>
    <tr>
      <td>`Range∞`</td>
      <td>Range</td>
      <td>*∞* = Follow quantity</td>
    </tr>
  </tbody>
</table>



## Quality Assurance

### Self QA

* Inspect your code in real-time to eliminate potential errors
* Indent your code to make it easy to read <!-- [Dreamweaver setup for indentation](#) -->
* Test in browser rendering for all breakpoints/liquidity
* Send Litmus test and check the result
* Test for real-devices (DSG testing emails)
* If deviating from Master Templates test your experimental code on devices as well on litmus

### Team QA

* Include all information and files to your request:
  * Litmus test (share link)
  * Indented HTML file (include Proof/Test sent from AC)
  * Subject Line and Pre-Header
  * Additional information about data, dynamics, includes
* Split the QA task for three stages:
  * Tracking Links and Copy/Typos
  * Code review
  * Visual rendering

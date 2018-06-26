# Tracking Links

Please, follow guidance below to keep all links trackable depend of brand.


- - -


## `Currys` `PCWorld`

> The tracking part of the link is same for both.

###### Example of tracking part.

``` HTML
<a href="https://www.currys.co.uk/?<%@ include view='dixDIXtrackingCPCW1' %>~COM~TVN~3NOM1~<%@ include view='dixDIXtrackingCPCW2' %>" _label="3NOM1">

<a href="https://www.pcworld.co.uk/?<%@ include view='dixDIXtrackingCPCW1' %>~SEG~LAP~1BNR2~<%@ include view='dixDIXtrackingCPCW2' %>" _label="1BNR2">
```

###### How to edit?

**`href="https://www.currys.co.uk/"`** always it should be SSL protocol `https` and make sure is no `empty space` between `link` and `?`

**`~COM~TVN~3NOM1~`** included three parts; [Page Type <span class="icon link"></span>][1], [Category <span class="icon link"></span>][2] and [Module <span class="icon link"></span>][3] and each part is separated by `~`

**`_label="3NOM1"`** as above update it to follow your type of [Module](tracking_links?id=module)

**`<%@ include view='dixDIXtrackingCPCW1' %>`** and **`<%@ include view='dixDIXtrackingCPCW2' %>`** are parts of tracking populated by [Personalization Blocks](personalization_block) on send time within Adobe Campaign


- - -



## `PCWBusiness`

``` HTML
<a href="https://www.pcworldbusiness.co.uk/?utm_campaign=<%= CampaignName %>&utm_medium=email&utm_source=PCWB_wk<%= targetData.WeekNo %>&utm_term=<%= message.delivery.id %>&utm_content=1BNR1_OTH" _label="1BNR1_OTH">
```

###### How to edit?

**`href="https://www.pcworldbusiness.co.uk/"`** always it should be SSL protocol `https` and make sure is no `empty space` between `link` and `?`

**`&utm_content=1BNR1_OTH`** contains [category](tracking_links?id=category)

> Please follow  link to sidebar.md section to see available tags.

**`_label="1BNR1_OTH"`** as above update it to follow your type of [module](tracking_links?id=module)

**`<%@ include view='dixDIXtrackingCPCW1' %>`** and **`<%@ include view='dixDIXtrackingCPCW2' %>`** are parts of tracking populated by [Personalization Blocks](personalization_block) on send time within Adobe Campaign



- - -



### Page Type

##### Use below with `Currys` `PCWorld` `PCWBusiness`

<table class="tweak hw">
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

### Category

##### Use below with `Currys` `PCWorld` `PCWBusiness`

<table class="tweak hw">
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

### Module

##### Use below with `Currys` `PCWorld` `PCWBusiness`

<table class="tweak style hw nbp">
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
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`2NOM∞`</td>
      <td>2x Nominations in Row</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`3NOM∞`</td>
      <td>3x Nominations in Row</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`1BNR∞`</td>
      <td>1x Banner in Row</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`2BNR∞`</td>
      <td>2x Banners in Row</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`3BNR∞`</td>
      <td>3x Banners in Row</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`TKH∞`</td>
      <td>TeamKnowHow</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`IDM∞`</td>
      <td>iD Mobile</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`CPW∞`</td>
      <td>CarphoneWarehouse</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`OEL`</td>
      <td>Our Experts Love</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`Brands∞`</td>
      <td>Brands</td>
      <td>*∞* = update the numerators</td>
    </tr>
    <tr>
      <td>`Range∞`</td>
      <td>Range</td>
      <td>*∞* = update the numerators</td>
    </tr>
  </tbody>
</table>

> First digit number stands for type of `Module` in a single `row` (left-to-right)
>
> Update the numerator *`∞`* to describe same type of `Modules` in total (top-to-bottom)



- - -

[1]: <tracking_links?id=page-type> "Page Type"
[2]: <tracking_links?id=category> "Category"
[3]: <tracking_links?id=module> "Module"

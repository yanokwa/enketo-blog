---
title: Grid Theme
author: Martijn van de Rijdt
layout: post
permalink: /gorgeous-grid
categories:
  - Uncategorized
tags:
 - enketo
---

Enketo Smart Paper now has a brand new theme option: __The Grid Theme__. Click the screenshot below to check out a sample form right away.


[![Screenshot of WHO Fatal Injury form using Grid Theme](../files/2014/04/fatal-injury.png "Screenshot of WHO Fatal Injury form using Grid Theme")](https://fatal.enketo.org/webform)

This form was developed by Ona for [WHO](http://who.int). 

### Focus on larger screens and printing

Similar to the current default theme, the new Grid Theme is fully functional on mobile devices. However, the Grid Theme is primarily meant for use on larger screens. The larger screen real estate is required to display questions next to each other. The Grid Theme has been given particular focus to creating good-looking and compact printouts. 

### How to use

This theme is currently exclusively available to [enketo.org](https://enketo.org) users only. To use it add the value _'theme-grid'_ on the settings tab of your XLSForm in the 'style' column. This will switch your form to the Grid Theme. If you have multiple settings for 'style' (e.g. ['pages'](/pages) and 'theme-grid') simply separate them with a space. 

![XLSForm Style Setting](../files/2014/04/XLSForm-style-theme-grid.png "Style setting in XLSForm")

To fully leverage the power of the Grid Theme, you'll want to indicate which questions should be displayed on one row and how many cells they should occupy. We developed a very flexible and simple-to-use mechanism for this for this using _w1, w2, w3....w10_ to indicate the _relative width_ you'd like to use. It is best explained by looking at this tutorial form: [https://grid.enketo.org/webform](https://grid.enketo.org/webform). The XLSForm source is available [here](https://docs.google.com/spreadsheet/ccc?key=0Al3Mw5sknZoPdDhSVmhJX2NvOG44X1RadTA2RVRzSHc&usp=sharing#gid=0).

![XLSForm Grid markup](../files/2014/04/XLSForm-w-markup.png "XLSForm Grid markup")

The extra _w1, w2....w10_ markup is placed in the 'appearance' column of an XLSForm. If you decide to switch back to the default 'formhub' theme just remove 'theme-grid'. The grid markup will simply be ignored in other themes.

Note that the version of XLSForm currently hosted on http://opendatakit.org is an old version that does not yet support the style column. 

### Technology

This theme makes use of a cutting edge technology (called 'flexboxes') that allows the forms to be rendered flexibly and fast. Speed should improve further over time when this browser technology matures. As a result of living on the edge, only the __latest version__ of the popular browsers are supported (Chrome, Firefox, Internet Explorer, Opera, Safari).


### Acknowledgement

The development of this theme was funded by the good folks at the [Santa Fe Institute](http://www.santafe.edu) as part of a [collaboration](http://www.santafe.edu/news/item/gates-slums-announce/) between the Santa Fe Institute and [Shack/Slum Dwellers International](http://www.sdinet.org/) through a grant by the [Bill and Melinda Gates Foundation](http://www.gatesfoundation.org/).

Special thanks go to [Kumail Hunaid](http://kumailht.com/), the author of the wonderful ['GridForms' project](http://kumailht.com/gridforms/). Much of his amazing graphic design ideas were used in Enketo's Grid Theme (not the library itself).

### Feedback

As usual, we'd love to get your feedback. Send an [email](mailto:support@enketo.org), post a message in the [Enketo](https://groups.google.com/forum/#!forum/enketo-users), [Formhub](https://groups.google.com/forum/#!forum/formhub-users), [Open Data Kit](https://groups.google.com/forum/#!forum/opendatakit) fora, or comment on this blog post. I'm sure many in the OpenRosa community would be very interested in seeing the amazing forms you create with this theme and perhaps we can even showcase them on the enketo.org front page.
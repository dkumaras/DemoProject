---
title: About
omit_header_text: false
description: We'd love to hear from you
type: page
menu: main
---

# Introduction

## What does it do?

It provides a **TCEform** wizard for adding industry standard dummy text
to selected form fields in **TYPO3**. The dummy content is the classic
\"*Lorem ipsum dolor sit amet\...\"* taken from the website
\" [www.lipsum.org](http://www.lipsum.org/) \". It also provides a
selection of 40 dummy pictures.

## Screenshots

The extension will add wizard icons to all *header*, *bodytext*,
*caption*, *description*, *keyword*, *title* and so on.

### Fields of Content Elements and Pages:

![image alt text](/FC1.jpg)
<img class="special-img-class" src="/FC1.jpg" />

-   By clicking the icons dummy text is put into the associated form
    field.

-   Clicking images in the image matrix will add the image to the image
    list and attached to the record when saved. Images are found in 7
    different aspect ratios.

## Wizard Configuration

The basic configuration of the wizard in the \"*wizards*\" array of a
**TCA** field configuration is like this:

// Create wizard configuration:

\$wizConfig = array(

\'type\' =\> \'userFunc\',

\'userFunc\' =\>
\'EXT:lorem_ipsum/class.tx_loremipsum_wiz.php:tx_loremipsum_wiz-\>main\',

\'params\' =\> array()

);

![image alt text](/FC2.jpg)
<img class="special-img-class" src="/FC2.jpg" />

The \"*params*\" key has these key/value options:

### type

Key

### type

Data Type

### string (keyword)

Description

Type of Lorem Ipsum text to add. Keywords are:

-   **title** : Adds a small amount (\<25) characters of dummy text -
    > fitting page titles.

-   **header** : Adds a medium amount of dummy text fitting headers for
    > such as content elements (\<60 chars)

-   **description** : Adds a large amount of dummy text, fitting
    > descriptions, image captions etc.

-   **word** : Adds a single word of dummy text

-   **paragraph** : Adds a paragraph of dummy text. The paragraph is a
    > handful of \"description\" length sentences.

-   **loremipsum** : Adds specifically \"Lorem ipsum dolor sit amet\"

-   **images** : (Only for \"group\" fields with \"file\" internal type)
    > Creates a matrix with 42 dummy images to select.

### endSequence

Key

### endSequence

Data Type

### comma list of integers

Description

What sequence of characters to end each dummy string with. That could be
\"46,32\" for period and space. Or \"10\" for line break.

### add

Key

### add

Data Type

### boolean

Description

If true, the a click on the wizard button will *append* the dummy text
to the field. (Default behavior is to substitute all field content with
dummy text.

### count

Key

### count

Data Type

### integer

Description

-   Number of dummy content samples to cycle through.

-   Continuously clicking the wizard icon will select other dummy text
    composites and this number points to the amount of options there
    are. Default is 10.

# Manual

## Inserting \"Lorem Ipsum\...\"

In records for pages, content elements and page overlay records you
simply click the \"Lipsum\" button to the right of input fields where
Lorem Ipsum applies. See screenshot above.

# Dummy content for localized websites

If you are developing localized websites it can be practical to insert
dummy content that is visually different from the default language. It
makes it easy for you to see if your application works correctly if you
use russian or asian characters as dummy data. It will even help to
expose places where you do not handle characters sets correctly.

You configure other types of dummy content than the default \"Lorem
Ipsum\" kind (which is totally ASCII based) in the System Language
records. All records that refer to this system language as their
language definition will now use that type of dummy content instead.

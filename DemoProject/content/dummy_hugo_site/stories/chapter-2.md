---
date: 2017-04-09T10:58:08-04:00
description: "All About Tables"
featured_image: "/images/Pope-Edouard-de-Beaumont-1844.jpg"
tags: ["scene"]
title: "Chapter II: All About Tables"
---

# Tables

The template comes with a table component that can be used to style
tables with a few standard presets.

## Example

  **First Name**   **Last Name**   **Email**             **Actions**
  ---------------- --------------- --------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Jane             Doe             sample\@example.org   [[View]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Edit]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Delete]{.ul}](https://www.sample.iastate.edu/docs/tables/)
  Jane             Doe             sample\@example.org   [[View]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Edit]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Delete]{.ul}](https://www.sample.iastate.edu/docs/tables/)
  Jane             Doe             sample\@example.org   [[View]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Edit]{.ul}](https://www.sample.iastate.edu/docs/tables/) - [[Delete]{.ul}](https://www.sample.iastate.edu/docs/tables/)

  : Table One

#### iOS Bug

There is a bug in iOS that breaks the default tap status bar to scroll
to top behavior when using .wd-u-OverflowScroll.

> \<div class=\"wd-u-OverflowScroll\"\>
>
> \<table class=\"wd-Table\--bordered\"\>
>
> \...
>
> \</table\>
>
> \</div\>

## Overview

Included in the package are the following files:

iastate-theme/

\|\-- css/

\| \`\-- base.css

\|\-- img/

\| \`\-- sprite.png

\|\-- favicon.ico

\`\-- hompage.html

## Responsive

The sample html includes the responsive design by default. In order to
disable that you must do the following:

1.  Remove the .responsive class from the \<body\> tag (Line 14)

2.  Remove the **viewport** \<meta\> tag (Line 8)

3.  Remove the **Responsive design** \<script\> tag (Line 168)

4.  Remove all elements with the .responsive-toggles class (Line 21, 75)

## Sidebar

The sample html includes the left sidebar by default. In order to remove
the sidebar do the following:

1.  Remove the .wd-show-sidebar class from the \<body\> tag (Line 14)

2.  Remove the .isu-sidebar element (Line 73)

## Archive

-   [iastate-theme-1.4.67.zip](https://www.sample.iastate.edu/download/html/dist/iastate-theme-1.4.67.zip) (v1.4.67,
    2016-11-04, 70KiB)

    -   Font Awesome to 4.6.1

    -   Fixed NavBar

    -   Fixed TopStripMenu Event Handling

```{=html}
<!-- -->
```
-   [iastate-theme-1.4.44.zip](https://www.sample.iastate.edu/download/html/dist/iastate-theme-1.4.44.zip) (v1.4.44,
    2016-01-11, 68KiB)

    -   Added \"shim\" components for compatability with Bootstrap.

    -   Updated FontAwesome to 4.5.0.

    -   Changed sidebar menu chevrons to FontAwesome glyphs that can be
        styled.

```{=html}
<!-- -->
```
-   [iastate-theme-1.4.42.zip](https://www.sample.iastate.edu/download/html/dist/iastate-theme-1.4.42.zip) (v1.4.42,
    2015-09-09, 67KiB)

    -   Changed search url to from http:// to //

```{=html}
<!-- -->
```
-   [iastate-theme-1.4.39.zip](https://www.sample.iastate.edu/download/html/dist/iastate-theme-1.4.39.zip) (v1.4.39,
    2015-09-08, 67KiB)

    -   Fixed responsive sidebar hidden overflow

```{=html}
<!-- -->
```
-   [iastate-theme-1.4.36.zip](https://www.sample.iastate.edu/download/html/dist/iastate-theme-1.4.36.zip) (v1.4.36,
    2015-09-08, 66KiB)

    -   Changed Outlook link in header
        from exchange.iastate.edu to outlook.iastate.edu

    -   Rounded corner for active chevron on sub-nav links

    -   Removed overflow-scroll on paginator table container

    -   Fixed margin for buttons in chrome

    -   Updated font-awesome version

    -   Linked footer to org-url

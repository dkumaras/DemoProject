---
date: 2017-04-14T11:25:05-04:00
description: "Posts Lists"
tags: []
title: "Chapter VII: Posts Lists"
disable_share: false
---

-   [[https://loremflickr.com/320/240]{.ul}](https://loremflickr.com/320/240)

-   A random picture of **320 x 240 pixels**. If not supplying any
    keyword, you\'ll get a picture matching the keyword **kitten**.

-   [[https://loremflickr.com/320/240/dog]{.ul}](https://loremflickr.com/320/240/dog)

-   A random picture matching the keyword **dog**, of 320 x 240 pixels.

-   [[https://loremflickr.com/g/320/240/paris]{.ul}](https://loremflickr.com/g/320/240/paris)

-   A random picture **in gray** matching the keyword paris, of 320 x
    240 pixels. Besides **g**, you can
    try **p**, **red**, **green** and **blue**.

-   [[https://loremflickr.com/320/240/brazil,rio]{.ul}](https://loremflickr.com/320/240/brazil,rio)

-   A random picture matching the keywords brazil **or** rio, of 320 x
    240 pixels.

-   [[https://loremflickr.com/320/240/paris,girl/all]{.ul}](https://loremflickr.com/320/240/paris,girl/all)

-   A random picture matching the keywords paris **and** girl, of 320 x
    240 pixels.

-   [[https://loremflickr.com/g/320/240/paris,girl/all]{.ul}](https://loremflickr.com/g/320/240/paris,girl/all)

-   A random picture in grey matching the keywords paris and girl, of
    320 x 240 pixels.

-   If no matching photos are found, [[a photo of
    Tomboli]{.ul}](https://www.flickr.com/photos/mastababa/31544397892/) is
    returned.

Lock it, lock it real good

Take some control of the image that\'s displayed. Include a lock query
string parameter and give it a value that\'s a positive integer. While
our cache is not updated, and sometimes for longer, the same image will
be returned by our server.

-   \<**img** src=\"https://loremflickr.com/320/240?lock=1\" /\>

-   \<**img** src=\"https://loremflickr.com/320/240?lock=212\" /\>

-   \<**img** src=\"https://loremflickr.com/320/240?lock=30976\" /\>

Multiple images on the same page

Your browser might cache the images when you request the same URL
multiple times on the same page. You can resolve this by adding a
meaningless querystring to the URL. So, for example\...

-   \<**img** src=\"https://loremflickr.com/320/240?random=1\" /\>

-   \<**img** src=\"https://loremflickr.com/320/240?random=2\" /\>

-   \<**img** src=\"https://loremflickr.com/320/240?random=3\" /\>

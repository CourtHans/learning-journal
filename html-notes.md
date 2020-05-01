[Return to Table of Contents](README.md)

# Class 4: HTML Notes

***Key words:***
* *semantic HTML* - the use of a markup language such as HTML to convey information about the meaning of each element in a document
* *tags, opening and closing* - tags indicate the beginngs and ends of sections
  * opening - `<h>` is a header opening
  * closing - `/h>` is a header closing 
* *self-closing tag* - "in XML and XHTML, a self-closing tag is a shorthand notation for an opening and closing tag in one. It’s used to communicate lack of content in between the opening and closing tags. So, rather than typing `<p></p>` (with no space at all in between), you’d be able write `<p/>`."
* *attributes* - attributes provide additional information about the contents of elements. They are made up of two parts: a **name** and a **value/id**, seperated by an equals sign. It will be a keyword inside the tag...

## Process and Design

When desiging your (or your client's) site, consider the following: 
* **WHO** is the site for?
* **WHY** would people visit your website?
* **WHAT** are your visitors tring to achieve?
* **WHAT** information do your visitors need?
* **HOW OFTEN** will people visit your site?

As with all products/solutions, it's helpful to put yourself in your customers'/users' shoes (what problem(s) are you trying to solve?). One way to do that is to construct some Muses. 

*Example:*

Name  | Ryan  | Sally | Aowyn |  Kyle  |
------| ----- | ----- | ----- | -----  |
Gender | M | F | F | M
Location | Seattle | Phoenix | Orlando | Montreal
Occupation | programmer | Event Manager | Domestic Engineer | Consultant
Income | $100,000 | $75,000 | $0 | $120,000
Web use | daily | daily | 3-4x/week | 4-5x/week

If you can put yourself in the mindset of the end user (not aways your actual client) you can think through and anticipate what information is needed from the site and how the user is likely to interact with your site.

#### Card Sorting
When building out your site, a useful exercise is **card sorting**. It helps you group the information on your site in a logical manner.

#### Wireframe

A wireframe is a simple sketch of the key info that needs to go on each page. It's helpful to show this "sketch" (of sorts) to your client to check functionality before laying in design, as your client may get distracted with design questions and needed functionality could be missed at this point.

> Remember: The primary aim of any kind of visual deisn is to communicate, so *think about who you're targeting and what information you're trying to convey.

## HTML 5 Layout

HTML 5 introduces a new set of elements that allow you to divide up parts of a page. It's still evolving. Some tags to note:

```
<header>
<footer>
<nav>
<article>
<aside>
<section>
<hgroup>
<figure> <figcaption>
<div>
```

## Extra Markup

Since the web was created, several versions of HTML have come forth, each designed to be an improvement upon its predecessors. 

>Because there have been several versions, each web page should begin with a DOCTYPE declaration to tell a browser which version of code is being used. To hide a comment like this (only visible in the document source), you can use the following command to make a comment like this `<!DOCTYPE html>`

Comment on your code - it helps you remember and helps others navigate complex code. You can do so like this:
`<!-- {YOUR COMMENT GOES HERE} -->` To use a shortcut, use the keys `COMMAND /`

The `<div>` element allows you to group a set of elements together in one block-level box.

The `<iframe>` element  allows you to cut a little "window" into your page to see another page. A common use is to pull in a Google Map.

The `<meta>` element "lives inside the `<head>` element and contains information about the web page. It is not visible to users but is used for other purposes like telling search engines about your page. It is an empty element, so does not have a closing tag. 

[Previous - Class 3 Stretch](lab03-stretch.md)
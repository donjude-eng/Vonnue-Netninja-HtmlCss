# Vonnue-Netninja-HtmlCss

---Net Ninja---

# HTML & CSS Crash Course Tutorial #1 - Introduction
Total Time- 19:59
**Total Line of code : 2360**
**Completion time: 30 Minutes**


* HTML used to structure content on the web page 
(Images,text,forms etc)
* Structure content using HTML tags


 ```
 <p>content</p>==Paragraph Tag [Time 3:22]
 <a> link </a> ==anchor Tag
 <img> == Image Tag (No closing tag)
 <head> tag -- This is for page information like Title.
 <title> tag -- List in the top
 <body> tag --  This is for visible page conten
 ```

* Add a local development server foe live refresh==Add extension [15:40]
* Inspect the page [17:45]


# HTML & CSS Crash Course Tutorial #2 - HTML Basics
Total Time- 19:51
**Completion time: 40 Minutes**

Tags
```
<strong> </strong> ==Make the letter bold. [2:20]
<em> </em> (empasise)== Make the content italics.
<small> </small> == Make the letter small.
<h1> </h1> == Heading tag (There are six diffrent types
<ul> </ul == Unordered list (Put bullet points in list) [4:50]
**** <li> </li> == single list item.
<ol> </ol> == Ordered list. (Put numbers infront of list)
**** <li> </li> == single list
<br> Break the line (No closing Tag)
<hr> Horizonal tag (No closing tag)
<span> </span> This tag will apply style in inline emlement.

Tags and Attributes.

<img (Tag) src (attribute) alt (attribute-- No visual effect) [10:51]
   *eg ; <img src="image.png" alt="a picture">
<a (Tag) href (attribute)> </a> (anchor tag)--Adding Link
   *eg ; <a href="www.sample.website.com> samplewebsite </a>
<blockquote (Tag) cite (attribute) --Quote the line from a link.
   *eg ; <blockquote cite="Website"> Line here </blockquote>
<p style="organge"> Line </p>
```

# HTML & CSS Crash Course Tutorial #3 - HTML Forms
Total time-31:54
**Completion time: 1 hour 30 Minutes**

**Tag and Attributes.**
```
<form (Tag) action (attribute)--Not important now.
<input (Tag) type = "text" id = "username"> (Username, search etc)
<label> (Tag)
```
**Notes:**
 ```
 <input> tag contains "type "attribute type of input field. eg (text,email,password)
 "id" attribute will identify the individual tag
  1.eg; <label for="lbl-name"> Enter the name </label>
        <input type="text" id="lbl-name" placeholder="Enter your name">
 ```
 **radio button**
``` eg; <input type= "radio" id="rad-age" name="gender1" value="0-25"> If it is name not need to give the "value" attribute.
    <label for="rad-age"> 0-25 </label>
```
**Notes:** 
* Input is a tag inside form tag
* Case should be same
* If we write two forms the it will separate the space
* The name attribute is important when using radio type because it helps group radio inputs

# HTML & CSS Crash Course Tutorial #4 - CSS Basics
Total Time- 42:38
**Completion time: 1 hour 50 Minutes**

**Important usage**
```
link -a link between a document and an external resource
usage -link rel="stylesheet" href="style.css" /
rel - specify the relationship between the two documents.
href - href attribute specifies the URL of the page the link goes to.
units in css - px,em,%,cm,ex,in,am,pc,pt etc..
text-decoration - values(underline,none,line-through)
font family
text align
line height
letter spacing
column-count
border
border-width: px;
border-color: ;
border-style: ;
```

# HTML & CSS Crash Course Tutorial #5 - CSS Classes & Selectors
Total Time- 26:27
**Completion time: 40 Minutes**

**Notes**
* Class = We can add same class to diffrent element in a page.
   (We can make text color font etc)
*: class 1 : class="success">
  : Multiple classes : class="success.feedback"
* inner selector - div p{we can style here for p element that inside a div}
* attribute selector - a[href]{we can style here for a tag have href attribute}
* text-transform - for text transforming
* a[href*="google"] {we can style here for an a tag its href value include text 'google'}
* HTML element can inherit CSS properties thar are applied to thier parent property.


# HTML & CSS Crash Course Tutorial #6 - HTML 5 Semantics
Total Time- 14:14
**Completion time: 1 hour 20 Minutes**

**Semantic Tag**
 ```
 <Main> For the main content of a webpage , unique to that page.
<section> Defines a certain section of a webpage (eg. bloglist, contact info)
<article> Defines a bit of content which makes up an article (eg . ablog post)
<aside> Defines some content relates to something else (eg .similar blogs)
<header> For the header of a website - contains the nav, title etc
<footer> For the footer of a website.
<li> Images or icon or list of links.
```


# HTML & CSS Crash Course Tutorial #7 - Chrome Dev Tools
Total Time- 11:49
**Completion time: 30 Minutes**

**Notes**
1.  Go to element in inspect >> Right-click in tag >> Copy the selector >> Paste it in console
( This is for to make rules)
2.  If we want to make a quick change ---- Go to edit as Html -- can add the details
3.  scroll into views ( tO  view the item)
4.  Can edit.
5.  Can add the attribute.
6. The top-left icon will select the different items on the page.
7.  Do the reverse engineering in inspect.
8.  "source" page will show the source.
9.  To save the changes from inspects tool > sources >>filesystem >> Add folder workspace.

* inner selector - div p{we can style here for p element that inside a div}
* attribute selector - a[href]{we can style here for a tag have href attribute}
* text-transform - for text transforming
* a[href*="google"] {we can style here for an a tag its href value include text 'google'


# HTML & CSS Crash Course Tutorial #8 - CSS Layout & Position
Total Time- 39:21
**Completion time: 5 hours 40 Minutes**

**Notes**
1.  Relative- We can shift the element around the page to the original position on the page.
   eg :{
        position:relative;    
    left:20px;
    bottom:20px;

2. Fixed - Position fixed (The box will be fixed on the page if we dropdown)
3. Absolute- Absolute position is relative to its closing parent. Position of the parent element to the child element.
   eg: {
    position:absolute;
    left:20px;
    bottom;20px
    **absolute relative to the parent which has the relative property.**
4. Static - Mixture of static and fixed.

* section-index -> Bring the property in front of the page.
* white space: now drop (will display in a straight line.
* border-radius - helps to change border shape.
* margin:0: auto -auto keyword automatically adjusted spaces.


# HTML & CSS Crash Course Tutorial #9 - Pseudo Classes & Elements
Total Time- 16:47
**Completion time: 1 hour 35 Minutes**

1. Pseudoclass
Style emements used for making a particular style.
hover selector,focus,first child of a parent element.
```  
eg : <ul> parent
	<li> child element
    nav li a:hover
```
2.Psedo elements.
   ```article p::first-line```
    

# HTML & CSS Crash Course Tutorial #10 - Intro to Media Queries
Total Time- 22:36
**Completion time: 30 Minutes**

*Tell the browser how to style an element at a particular view dimension*



Total Time- 3:24
**Completion time: 20 Minutes**
## HTML & CSS Crash Course Tutorial #11 - Next Steps

## CSS FLEXBOX BASICS

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes).

A flex container expands items to fill available free space or shrinks them to prevent overflow.

main axis – The main axis of a flex container is the primary axis along which flex items are laid out. it is not necessarily horizontal; it depends on the flex-direction property

cross axis – The axis perpendicular to the main axis is called the cross axis. Its direction depends on the main axis direction.

Properties for the Parent(flex container)

# Display
This defines a flex container; inline or block depending on the given value.
It enables a flex context for all its direct children.
flex-direction
This establishes the main-axis, thus defining the direction flex items are placed in the flex container.
Flexbox is (aside from optional wrapping) a single-direction layout concept.
Think of flex items as primarily laying out either in horizontal rows or vertical columns
row (default): left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top

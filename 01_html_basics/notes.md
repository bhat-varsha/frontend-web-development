===========================================================
HTML5 & CSS BASICS
===========================================================

HTML (HyperText Markup Language) is used to create the structure of a web page.

CSS (Cascading Style Sheets) is used to style and design the web page.

HTML defines WHAT appears on the page.

CSS defines HOW it looks.

===========================================================

HTML5 DOCUMENT STRUCTURE

<!DOCTYPE html> Tells the browser that the document is written using HTML5.

<html>  Root element that contains the entire webpage.

<head>  Contains metadata that is not directly displayed on the page.

Examples
- Page title
- CSS files
- JavaScript files
- Character encoding
- Viewport settings

<body>  Contains all visible webpage content.

Examples

- Headings
- Paragraphs
- Images
- Tables
- Forms
- Videos

===========================================================

COMMON HTML TAGS

Heading

<h1> ... <h6>

Used to create headings.

<h1> is the largest.

<h6> is the smallest.

--------------------------------------

Paragraph

<p>

Used to display text.

--------------------------------------

Hyperlink

<a href="url">

Creates a clickable link.

Example

<a href="https://www.ncbi.nlm.nih.gov">
Visit NCBI
</a>

--------------------------------------

Image

<img>

Displays an image.

Example

<img src="bioinformatics.jpg"
     alt="Bioinformatics"
     width="300">

Important Attributes

src

Image location.

alt

Alternative text if image cannot load.

width

Image width.

height

Image height.

--------------------------------------

Lists

Unordered List

<ul>

Uses bullets.

Ordered List

<ol>

Uses numbering.

List Item

<li>

Represents one item inside a list.

--------------------------------------

Table

<table>

Used to display tabular data.

<tr>

Table Row

<th>

Table Header

<td>

Table Data

Example

<table>

<tr>
<th>Name</th>
<th>Age</th>
</tr>

<tr>
<td>Varsha</td>
<td>23</td>
</tr>

</table>

--------------------------------------

Forms

<form>

Collects user input.

Common Input Types

text
email
password
number
date
radio
checkbox
submit
reset
select
textarea

===========================================================

MEDIA TAGS

<img> Image

<audio> Audio

<video> Video

===========================================================

USEFUL HTML TAGS

<br> Line break

<hr> Horizontal line

<strong> Important bold text

<em> Emphasized (italic) text

<b> Bold text (visual only)

<i> Italic text (visual only)

<u> Underline text

===========================================================

SEMANTIC HTML TAGS

Semantic tags describe the meaning of the content.

<header> Top section
<nav> Navigation menu
<main> Main content
<section>Section of related content
<article> Independent content
<aside> Sidebar
<footer> Bottom section

Semantic HTML improves
• Readability
• Accessibility
• SEO

===========================================================

HTML COMMENTS

<!-- Comment -->

Used to explain code.

Ignored by the browser.

===========================================================

CSS

CSS controls the appearance of HTML elements.

===========================================================

CSS SELECTORS

1. Tag Selector

Applies style to every element of that tag.

Example

h1{

color:blue;

}

Used when styling all headings.

--------------------------------------

2. Class Selector

Starts with

.

Example

.title{

color:red;

}

Used when multiple elements share the same style.

Example

<p class="title">

<h2 class="title">

------------------------------------------------

3. ID Selector

Starts with

#

Example

#gene{

color:green;

}

Used for one unique element.

One page should not contain multiple elements with the same ID.

===========================================================

DIV

<div>

Used to group related elements together.

Helps organize layouts and apply CSS to multiple elements.

===========================================================

COMMON CSS PROPERTIES

Font

font-family

font-size

font-weight

font-style

--------------------------------------

Text

text-align

text-decoration

text-transform

letter-spacing

word-spacing

line-height

--------------------------------------

Spacing

margin

padding

--------------------------------------

Size

width

height

--------------------------------------

Colors

color

background-color

--------------------------------------

Borders

border

border-radius

--------------------------------------

Images

opacity

object-fit

===========================================================

TABLE STYLING

Modern HTML keeps presentation inside CSS.

Instead of

<table border="1">

use

table{

border-collapse:collapse;

}

table,
th,
td{

border:1px solid black;

}

text-align:center;

===========================================================

LIST STYLING

Lists can be customized using

list-style-type

Examples

disc

circle

square

decimal

upper-alpha

none

===========================================================

DISPLAY PROPERTY

display:block

display:inline

display:inline-block

display:flex

display:grid

display:none

===========================================================

POSITION PROPERTY

position:static

position:relative

position:absolute

position:fixed

position:sticky

===========================================================

LAYOUT METHODS

Flexbox

Used for arranging items in one dimension.

(Row OR Column)

Grid

Used for arranging items in two dimensions.

(Rows AND Columns)

===========================================================

BEST PRACTICES

✓ Keep HTML for structure.

✓ Keep CSS for styling.

✓ Use semantic HTML whenever possible.

✓ Use class selectors for reusable styles.

✓ Use ID selectors only for unique elements.

✓ Avoid inline CSS whenever possible.

✓ Organize CSS into separate files.

===========================================================

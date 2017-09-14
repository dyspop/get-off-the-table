# Get Off The Table
![cat sleeping on a table](http://blog.gorebel.com/content/images/2017/08/GetOffTheTable-1.jpg)

Building HTML emails without &lt;tables&gt;

I'm trying to create an email template using a number of common style components, but without the use of any layout tables.

* 600px centered container
* Heading tags
* Paragraph tags
* Images
* Nested section with different width and background
* Multi column layout
* Ordered and Unordered lists
* Divider line
* CTA button
* Additional container outside of the main container

The main issue here is that Outlook doesn't render HTML or CSS correctly as it uses Microsoft Word as a rendering engine.  The goal of this project is to create a cross-email-client compatible `<div>`-based layout using `mso-` code.

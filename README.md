<div align="center">

## A Beginner's Guide to HTML Part II: \(a brief reference\)


</div>

### Description



You can't get too far in ASP without an intimate knowledge of HTML, so this tutorial will take a newbie through the ABC's of HTML...one step at a time. It's also a great reference for pros who forget how to use little known tags! By pubs@ncsa.uiuc.edu
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the World Wide Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-world-wide-web.md)
**Level**          |Beginner
**User Rating**    |4.3 (34 globes from 8 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-world-wide-web-a-beginner-s-guide-to-html-part-ii-a-brief-reference__4-6157/archive/master.zip)





### Source Code


<p><font face="Verdana"><b>URLs</b></font></p>
<p><font face="Verdana">The World Wide Web uses Uniform Resource Locators (URLs)
to specify the<br>
location of files on other servers. A URL includes the type of resource<br>
being accessed (e.g., Web, gopher, WAIS), the address of the server, and the<br>
location of the file. The syntax is:</font></p>
<p><font face="Verdana">scheme://host.domain [:port]/path/ filename</font></p>
<p><font face="Verdana">where scheme is one of</font></p>
<p><font face="Verdana">file<br>
&nbsp;&nbsp;&nbsp;&nbsp; a file on your local system<br>
ftp&nbsp; a file on an anonymous FTP server<br>
http<br>
&nbsp;&nbsp;&nbsp;&nbsp; a file on a World Wide Web server<br>
gopher<br>
&nbsp;&nbsp;&nbsp;&nbsp; a file on a Gopher server<br>
WAIS<br>
&nbsp;&nbsp;&nbsp;&nbsp; a file on a WAIS server<br>
news<br>
&nbsp;&nbsp;&nbsp;&nbsp; a Usenet newsgroup<br>
telnet<br>
&nbsp;&nbsp;&nbsp;&nbsp; a connection to a Telnet-based service</font></p>
<p><font face="Verdana">The port number can generally be omitted. (That means
unless someone tells<br>
you otherwise, leave it out.)</font></p>
<p><font face="Verdana">For example, to include a link to this primer in your
document, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;<a href="http://www.ncsa.uiuc.edu/General/Internet/WWW/HTMLPrimer.html">http://www.ncsa.uiuc.edu/General/Internet/WWW/HTMLPrimer.html</a>&quot;&gt;<br>
&nbsp;&nbsp;&nbsp; NCSA's Beginner's Guide to HTML&lt;/A&gt;</font></p>
<p><font face="Verdana">This entry makes the text NCSA's Beginner's Guide to
HTML a hyperlink to<br>
this document.</font></p>
<p><font face="Verdana">For more information on URLs, refer to:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * WWW Names and Addresses, URIs, URLs, URNs<br>
&nbsp;&nbsp; * A Beginner's Guide to URLs</font></p>
<p><font face="Verdana"><b>Links to Specific Sections</b></font></p>
<p><font face="Verdana">Anchors can also be used to move a reader to a
particular section in a<br>
document (either the same or a different document) rather than to the top,<br>
which is the default. This type of an anchor is commonly called a named<br>
anchor because to create the links, you insert HTML names within the<br>
document.</font></p>
<p><font face="Verdana">This guide is a good example of using named anchors in
one document. The<br>
guide is constructed as one document to make printing easier. But as one<br>
(long) document, it can be time-consuming to move through when all you<br>
really want to know about is one bit of information about HTML. Internal<br>
hyperlinks are used to create a &quot;table of contents&quot; at the top of this<br>
document. These hyperlinks move you from one location in the document to<br>
another location in the same document. (Go to the top of this document and<br>
then click on the Links to Specific Sections hyperlink in the table of<br>
contents. You will wind up back here.)</font></p>
<p><font face="Verdana">You can also link to a specific section in another
document. That<br>
information is presented first because understanding that helps you<br>
understand linking within one document.</font></p>
<p><font face="Verdana"><b>Links Between Sections of Different Documents</b></font></p>
<p><font face="Verdana">Suppose you want to set a link from document A (documentA.html)
to a<br>
specific section in another document (MaineStats.html).</font></p>
<p><font face="Verdana">Enter the HTML coding for a link to a named anchor:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; documentA.html:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; In addition to the many state
parks, Maine is also home to<br>
&nbsp;&nbsp;&nbsp;&nbsp; &lt;a href=&quot;MaineStats.html#ANP&quot;&gt;Acadia
National Park&lt;/a&gt;.</font></p>
<p><font face="Verdana">Think of the characters after the hash (#) mark as a tab
within the<br>
MaineStats.html file. This tab tells your browser what should be displayed<br>
at the top of the window when the link is activated. In other words, the<br>
first line in your browser window should be the Acadia National Park<br>
heading.</font></p>
<p><font face="Verdana">Next, create the named anchor (in this example &quot;ANP&quot;)
in MaineStats.html:</font></p>
<font face="Verdana">tml:</font>
<p>&nbsp;</p>
<font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;H2&gt;&lt;A NAME=&quot;ANP&quot;&gt;Acadia
National Park&lt;/a&gt;&lt;/H2&gt;</font>
<p>&nbsp;</p>
<p><font face="Verdana">With both of these elements in place, you can bring a
reader directly to the<br>
Acadia reference in MaineStats.html.</font></p>
<p><font face="Verdana">NOTE: You cannot make links to specific sections within
a different document<br>
unless either you have write permission to the coded source of that document<br>
or that document already contains in-document named anchors. For example,<br>
you could include named anchors to this primer in a document you are writing<br>
because there are named anchors in this guide (use View Source in your<br>
browser to see the coding). But if this document did not have named anchors,<br>
you could not make a link to a specific section because you cannot edit the<br>
original file on NCSA's server.</font></p>
<p><font face="Verdana">Links to Specific Sections within the Current Document</font></p>
<p><font face="Verdana">The technique is the same except the filename is
omitted.</font></p>
<p><font face="Verdana">For example, to link to the ANP anchor from within
MaineStats, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; ...More information about &lt;A HREF=&quot;#ANP&quot;&gt;Acadia
National Park&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp; is available elsewhere in this document.</font></p>
<font face="Verdana"><br>
</font>
<p><font face="Verdana">Be sure to include the &lt;A NAME=&gt; tag at the place
in your document where you<br>
want the link to jump to (&lt;H2&gt;&lt;A NAME=&quot;ANP&quot;&gt;Acadia
National Park&lt;/a&gt;&lt;/H2&gt;).</font></p>
<p><font face="Verdana">Named anchors are particularly useful when you think
readers will print a<br>
document in its entirety or when you have a lot of short information you<br>
want to place online in one file.</font></p>
<p><font face="Verdana"><b>Mailto</b></font></p>
<p><font face="Verdana">You can make it easy for a reader to send electronic
mail to a specific<br>
person or mail alias by including the mailto attribute in a hyperlink. The<br>
format is:</font></p>
<p><font face="Verdana">&lt;A HREF=&quot;<a href="mailto:emailinfo@host">mailto:emailinfo@host</a>&quot;&gt;Name&lt;/a&gt;</font></p>
<p><font face="Verdana">For example, enter:</font></p>
<p><font face="Verdana">&lt;A HREF=&quot;<a href="mailto:pubs@ncsa.uiuc.edu">mailto:pubs@ncsa.uiuc.edu</a>&quot;&gt;NCSA
Publications Group&lt;/a&gt;</font></p>
<p><font face="Verdana">to create a mail window that is already configured to
open a mail window for<br>
the NCSA Publications Group alias. (You, of course, will enter another mail<br>
address!)</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp; Inline Images</b></font></p>
<p><font face="Verdana">Most Web browsers can display inline images (that is,
images next to text)<br>
that are in X Bitmap (XBM), GIF, or JPEG format. Other image formats are<br>
being incorporated into Web browsers [e.g., the Portable Network Graphic<br>
(PNG) format]. Each image takes time to process and slows down the initial<br>
display of a document. Carefully select your images and the number of images<br>
in a document.</font></p>
<p><font face="Verdana">To include an inline image, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;IMG SRC=ImageName&gt;</font></p>
<p><font face="Verdana">where ImageName is the URL of the image file.</font></p>
<p><font face="Verdana">The syntax for &lt;IMG SRC&gt; URLs is identical to that
used in an anchor HREF.<br>
If the image file is a GIF file, then the filename part of ImageName must<br>
end with .gif. Filenames of X Bitmap images must end with .xbm; JPEG image<br>
files must end with .jpg or .jpeg; and Portable Network Graphic files must<br>
end with .png.</font></p>
<p><font face="Verdana"><b>Image Size Attributes</b></font></p>
<p><font face="Verdana">You should include two other attributes on &lt;IMG&gt;
tags to tell your browser<br>
the size of the images it is downloading with the text. The HEIGHT and WIDTH<br>
attributes let your browser set aside the appropriate space (in pixels) for<br>
the images as it downloads the rest of the file. (Get the pixel size from<br>
your image-processing software, such as Adobe Photoshop.)</font></p>
<p><font face="Verdana">For example, to include a self portrait image in a file
along with the<br>
portrait's dimensions, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;IMG SRC=SelfPortrait.gif
HEIGHT=100 WIDTH=65&gt;</font></p>
<p><font face="Verdana">NOTE: Some browsers use the HEIGHT and WIDTH attributes
to stretch or shrink<br>
an image to fit into the allotted space when the image does not exactly<br>
match the attribute numbers. Not all browser developers think<br>
stretching/shrinking is a good idea. So don't plan on your readers having<br>
access to this feature. Check your dimensions and use the correct ones.</font></p>
<p><font face="Verdana"><b>Aligning Images</b></font></p>
<p><font face="Verdana">You have some flexibility when displaying images. You
can have images<br>
separated from text and aligned to the left or right or centered. Or you can<br>
have an image aligned with text. Try several possibilities to see how your<br>
information looks best.</font></p>
<p><font face="Verdana"><b>Aligning Text with an Image</b><br>
&nbsp;&nbsp; By default the bottom of an image is aligned with the following
text, as<br>
shown in this paragraph. You can align images to the top or center of a<br>
paragraph using the ALIGN= attributes TOP and CENTER.</font></p>
<p><font face="Verdana">&nbsp;&nbsp; This text is aligned with the top of the
image (&lt;IMG SRC =<br>
&quot;BarHotlist.gif&quot; ALIGN=TOP&gt;). Notice how the browser aligns only
one line<br>
and then jumps to the bottom of the image for the rest of the text.</font></p>
<p><font face="Verdana">&nbsp;&nbsp; And this text is centered on the image
(&lt;IMG SRC = &quot;BarHotlist.gif&quot;<br>
ALIGN=CENTER&gt;). Again, only one line of text is centered; the rest is below<br>
the image.</font></p>
<p><font face="Verdana"><b>Images without Text</b><br>
To display an image without any associated text (e.g., your organization's<br>
logo), make it a separate paragraph. Use the paragraph ALIGN= attribute to<br>
center the image or adjust it to the right side of the window as shown<br>
below:</font></p>
<p><font face="Verdana">&lt;p ALIGN=CENTER&gt;<br>
&lt;IMG SRC = &quot;BarHotlist.gif&quot;&gt;<br>
&lt;/p&gt;</font></p>
<p><font face="Verdana">which results in:</font></p>
<p>&nbsp;
<p><font face="Verdana">The image is centered; this paragraph starts below it
and left justified.</font></p>
<p><font face="Verdana"><b>Alternate Text for Images</b></font></p>
<p><font face="Verdana">Some World Wide Web browsers--primarily those that run
on VT100<br>
terminals--cannot display images. Some users turn off image loading even if<br>
their software can display images (especially if they are using a modem or<br>
have a slow connection). HTML provides a mechanism to tell readers what they<br>
are missing on your pages.</font></p>
<p><font face="Verdana">The ALT attribute lets you specify text to be displayed
instead of an image.<br>
For example:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;IMG SRC=&quot;UpArrow.gif&quot;
ALT=&quot;Up&quot;&gt;</font></p>
<p><font face="Verdana">where UpArrow.gif is the picture of an upward pointing
arrow. With<br>
graphics-capable viewers that have image-loading turned on, you see the up<br>
arrow graphic. With a VT100 browser or if image-loading is turned off, the<br>
word Up is shown in your window.</font></p>
<p><font face="Verdana">You should try to include alternate text for each image
you use in your<br>
document, which is a courtesy for your readers.</font></p>
<p><font face="Verdana"><b>Background Graphics</b></font></p>
<p><font face="Verdana">Newer versions of Web browsers can load an image and use
it as a background<br>
when displaying a page. Some people like background images and some don't.<br>
In general, if you want to include a background, make sure your text can be<br>
read easily when displayed on top of the image.</font></p>
<p><font face="Verdana">Background images can be a texture (linen finished
paper, for example) or an<br>
image of an object (a logo possibly). You create the background image as you<br>
do any image.</font></p>
<p><font face="Verdana">However you only have to create a small piece of the
image. Using a feature<br>
called tiling, a browser takes the image and repeats it across and down to<br>
fill your browser window. In sum you generate one image, and the browser<br>
replicates it enough times to fill your window. This action is automatic<br>
when you use the background tag shown below.</font></p>
<p><font face="Verdana">The tag to include a background image is included in the
&lt;BODY&gt; statement as<br>
an attribute:</font></p>
<p><font face="Verdana">&lt;BODY BACKGROUND=&quot;filename.gif&quot;&gt;</font></p>
<p><font face="Verdana"><b>Background Color</b></font></p>
<p><font face="Verdana">By default browsers display text in black on a gray
background. However, you<br>
can change both elements if you want. Some HTML authors select a background<br>
color and coordinate it with a change in the color of the text.</font></p>
<p><font face="Verdana">Always preview changes like this to make sure your pages
are readable. (For<br>
example, many people find red text on a black background difficult to read!)</font></p>
<p><font face="Verdana">You change the color of text, links, visited links, and
active links using<br>
attributes of the &lt;BODY&gt; tag. For example, enter:</font></p>
<p><font face="Verdana">&lt;BODY BGCOLOR=&quot;#000000&quot; TEXT=&quot;#FFFFFF&quot;
LINK=&quot;#9690CC&quot;&gt;</font></p>
<p><font face="Verdana">This creates a window with a black background (BGCOLOR),
white text (TEXT),<br>
and silvery hyperlinks (LINK).</font></p>
<p><font face="Verdana">The six-digit number and letter combinations represent
colors by giving<br>
their RGB (red, green, blue) value. The six digits are actually three<br>
two-digit numbers in sequence, representing the amount of red, green, or<br>
blue as a hexadecimal value in the range 00-FF. For example, 000000 is black<br>
(no color at all), FF0000 is bright red, and FFFFFF is white (fully<br>
saturated with all three colors). These number and letter combinations are<br>
cryptic. Fortunately an online resource is available to help you track down<br>
the combinations that map to specific colors:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * ColorPro Web server</font></p>
<p><font face="Verdana"><b>External Images, Sounds, and Animations</b></font></p>
<p><font face="Verdana">You may want to have an image open as a separate
document when a user<br>
activates a link on either a word or a smaller, inline version of the image<br>
included in your document. This is called an external image, and it is<br>
useful if you do not wish to slow down the loading of the main document with<br>
large inline images.</font></p>
<p><font face="Verdana">To include a reference to an external image, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;MyImage.gif&quot;&gt;link
anchor&lt;/A&gt;</font></p>
<p><font face="Verdana">You can also use a smaller image as a link to a larger
image. Enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;LargerImage.gif&quot;&gt;&lt;IMG
SRC=&quot;SmallImage.gif&quot;&gt;&lt;/A&gt;</font></p>
<p><font face="Verdana">The reader sees the SmallImage.gif image and clicks on
it to open the<br>
LargerImage.gif file.</font></p>
<p><font face="Verdana">Use the same syntax for links to external animations and
sounds. The only<br>
difference is the file extension of the linked file. For example,</font></p>
<p><font face="Verdana">&lt;A HREF=&quot;AdamsRib.mov&quot;&gt;link
anchor&lt;/A&gt;</font></p>
<p><font face="Verdana">specifies a link to a QuickTime movie. Some common file
types and their<br>
extensions are:</font></p>
<p><font face="Verdana">File Type&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Extension<br>
plain text&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .txt<br>
HTML document&nbsp;&nbsp; .html<br>
GIF image&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .gif<br>
TIFF image&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .tiff<br>
X Bitmap image&nbsp; .xbm<br>
JPEG image&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .jpg or .jpeg<br>
PostScript file .ps<br>
AIFF sound file .aiff<br>
AU sound file&nbsp;&nbsp; .au<br>
WAV sound file&nbsp; .wav<br>
QuickTime movie .mov<br>
MPEG movie&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .mpeg or .mpg</font></p>
<p><font face="Verdana">Keep in mind your intended audience and their access to
software. Most UNIX<br>
workstations, for instance, cannot view QuickTime movies.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Tables</b></font></p>
<p><font face="Verdana">Before HTML tags for tables were finalized, authors had
to carefully format<br>
their tabular information within &lt;PRE&gt; tags, counting spaces and
previewing<br>
their output. Tables are very useful for presentation of tabular information<br>
as well as a boon to creative HTML authors who use the table tags to present<br>
their regular Web pages. (Check out the NCSA Relativity Group's pages for an<br>
excellent, award-winning example.)</font></p>
<p><font face="Verdana">Think of your tabular information in light of the coding
explained below. A<br>
table has heads where you explain what the columns/rows include, rows for<br>
information, cells for each item. In the following table, the first column<br>
contains the header information, each row explains an HTML table tag, and<br>
each cell contains a paired tag or an explanation of the tag's function.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Table Elements</b></font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; Element&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Description<br>
&lt;TABLE&gt; ...&nbsp;&nbsp;&nbsp; defines a table in HTML. If the BORDER
attribute is<br>
&lt;/TABLE&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; present, your browser
displays the table with a border.<br>
&lt;CAPTION&gt; ...&nbsp; defines the caption for the title of the table. The
default<br>
&lt;/CAPTION&gt;&nbsp;&nbsp;&nbsp;&nbsp; position of the title is centered at
the top of the table.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
The attribute ALIGN=BOTTOM can be used to position the<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
caption below the table.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
NOTE: Any kind of markup tag can be used in the caption.<br>
&lt;TR&gt; ... &lt;/TR&gt; specifies a table row within a table. You may define<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
default attributes for the entire row: ALIGN (LEFT, CENTER,<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
RIGHT) and/or VALIGN (TOP, MIDDLE, BOTTOM). See Table<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Attributes at the end of this table for more information.<br>
&lt;TH&gt; ... &lt;/TH&gt; defines a table header cell. By default the text in
this<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
cell is bold and centered. Table header cells may contain<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
other attributes to determine the characteristics of the<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
cell and/or its contents. See Table Attributes at the end<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
of this table for more information.<br>
&lt;TD&gt; ... &lt;/TD&gt; defines a table data cell. By default the text in
this cell<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
is aligned left and centered vertically. Table data cells<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
may contain other attributes to determine the<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
characteristics of the cell and/or its contents. See Table<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Attributes at the end of this table for more information.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp;&nbsp; Table Attributes</b></font></p>
<p><font face="Verdana">NOTE: Attributes defined within &lt;TH&gt; ... &lt;/TH&gt;
or &lt;TD&gt; ... &lt;/TD&gt; cells<br>
override the default alignment set in a &lt;TR&gt; ... &lt;/TR&gt;.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Attribute<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Description<br>
&nbsp;&nbsp;&nbsp; * ALIGN (LEFT, CENTER, RIGHT)</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; * VALIGN (TOP, MIDDLE, BOTTOM)</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; * COLSPAN=n</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; * ROWSPAN=n</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; * NOWRAP<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
* Horizontal alignment of a cell.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
* Vertical alignment of a cell.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
* The number (n) of columns a cell spans.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
* The number (n) of rows a cell spans.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
* Turn off word wrapping within a cell.</font></p>
<p><font face="Verdana">General Table Format</font></p>
<p><font face="Verdana">The general format of a table looks like this:</font></p>
<p><font face="Verdana">&lt;TABLE&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== start of table definition</font></p>
<p><font face="Verdana">&lt;CAPTION&gt; caption contents &lt;/CAPTION&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== caption definition</font></p>
<p><font face="Verdana">&lt;TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== start of first row definition<br>
&lt;TH&gt; cell contents &lt;/TH&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== first cell in row 1 (a head)</font></p>
<p><font face="Verdana">&lt;TH&gt; cell contents &lt;/TH&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== last cell in row 1 (a head)<br>
&lt;/TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== end of first row definition</font></p>
<p><font face="Verdana">&lt;TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== start of second row definition<br>
&lt;TD&gt; cell contents &lt;/TD&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== first cell in row 2</font></p>
<p><font face="Verdana">&lt;TD&gt; cell contents &lt;/TD&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== last cell in row 2<br>
&lt;/TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== end of second row definition</font></p>
<p><font face="Verdana">&lt;TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== start of last row definition<br>
&lt;TD&gt; cell contents &lt;/TD&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== first cell in last row<br>
...<br>
&lt;TD&gt; cell contents &lt;/TD&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== last cell in last row<br>
&lt;/TR&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== end of last row definition</font></p>
<p><font face="Verdana">&lt;/TABLE&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;== end of table definition</font></p>
<p><font face="Verdana">The &lt;TABLE&gt; and &lt;/TABLE&gt; tags must surround
the entire table definition. The<br>
first item inside the table is the CAPTION, which is optional. Then you can<br>
have any number of rows defined by the &lt;TR&gt; and &lt;/TR&gt; tags. Within a
row you<br>
can have any number of cells defined by the &lt;TD&gt;...&lt;/TD&gt; or &lt;TH&gt;...&lt;/TH&gt;<br>
tags. Each row of a table is, essentially, formatted independently of the<br>
rows above and below it. This lets you easily display tables like the one<br>
above with a single cell, such as Table Attributes, spanning columns of the<br>
table.</font></p>
<p><font face="Verdana"><b>Tables for Nontabular Information</b></font></p>
<p><font face="Verdana">Some HTML authors use tables to present nontabular
information. For example,<br>
because links can be included in table cells, some authors use a table with<br>
no borders to create &quot;one&quot; image from separate images. Browsers that
can<br>
display tables properly show the various images seamlessly, making the<br>
created image seem like an image map (one image with hyperlinked quadrants).</font></p>
<p><font face="Verdana">Using table borders with images can create an impressive
display as well.<br>
Experiment and see what you like.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp;&nbsp;&nbsp; Fill-out Forms</b></font></p>
<p><font face="Verdana">Web forms let a reader return information to a Web
server for some action.<br>
For example, suppose you collect names and email addresses so you can email<br>
some information to people who request it. For each person who enters his or<br>
her name and address, you need some information to be sent and the<br>
respondent's particulars added to a data base.</font></p>
<p><font face="Verdana">This processing of incoming data is usually handled by a
script or program<br>
written in Perl or another language that manipulates text, files, and<br>
information. If you cannot write a program or script for your incoming<br>
information, you need to find someone who can do this for you.</font></p>
<p><font face="Verdana">The forms themselves are not hard to code. They follow
the same constructs<br>
as other HTML tags. What could be difficult is the program or script that<br>
takes the information submitted in a form and processes it. Because of the<br>
need for specialized scripts to handle the incoming form information,<br>
fill-out forms are not discussed in this primer. Check the Additional Online<br>
Reference section for more information.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp; Troubleshooting</b></font></p>
<p><font face="Verdana">Avoid Overlapping Tags</font></p>
<p><font face="Verdana">Consider this example of HTML:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;B&gt;This is an example of &lt;DFN&gt;overlapping&lt;/B&gt;
HTML tags.&lt;/DFN&gt;</font></p>
<p><font face="Verdana">The word overlapping is contained within both the
&lt;B&gt; and &lt;DFN&gt; tags. A<br>
browser might be confused by this coding and might not display it the way<br>
you intend. The only way to know is to check each popular browser (which is<br>
time-consuming and impractical).</font></p>
<p><font face="Verdana">In general, avoid overlapping tags. Look at your tags
and try pairing them<br>
up. Tags (with the obvious exceptions of elements whose end tags may be<br>
omitted, such as paragraphs) should be paired without an intervening tag in<br>
between. Look again at the example above. You cannot pair the bold tags<br>
without another tag in the middle (the first definition tag). Try matching<br>
your coding up like this to see if you have any problem areas that should be<br>
fixed before your release your files to a server.</font></p>
<p><font face="Verdana">Embed Only Anchors and Character Tags</font></p>
<p><font face="Verdana">HTML protocol allows you to embed links within other
HTML tags:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;H1&gt;&lt;A HREF=&quot;Destination.html&quot;&gt;My
heading&lt;/A&gt;&lt;/H1&gt;</font></p>
<p><font face="Verdana">Do not embed HTML tags within an anchor:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;Destination.html&quot;&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;H1&gt;My heading&lt;/H1&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/A&gt;</font></p>
<p><font face="Verdana">Although most browsers currently handle this second
example, the official<br>
HTML specifications do not support this construct and your file will<br>
probably not work with future browsers. Remember that browsers can be<br>
forgiving when displaying improperly coded files. But that forgiveness may<br>
not last to the next version of the software! When in doubt, code your files<br>
according to the HTML specifications (see For More Information below).</font></p>
<p><font face="Verdana">Character tags modify the appearance of the text within
other elements:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt;&lt;B&gt;A bold list item&lt;/B&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt;&lt;I&gt;An italic list item&lt;/I&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/UL&gt;</font></p>
<p><font face="Verdana">Avoid embedding other types of HTML element tags. For
example, you might be<br>
tempted to embed a heading within a list in order to make the font size<br>
larger:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt;&lt;H1&gt;A large heading&lt;/H1&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt;&lt;H2&gt;Something slightly smaller&lt;/H2&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/UL&gt;</font></p>
<p><font face="Verdana">Although some browsers handle this quite nicely,
formatting of such coding<br>
is unpredictable (because it is undefined). For compatibility with all<br>
browsers, avoid these kinds of constructs. (The Netscape &lt;FONT&gt; tag, which<br>
lets you specify how large individual characters will be displayed in your<br>
window, is not currently part of the official HTML specifications.)</font></p>
<p><font face="Verdana">What's the difference between embedding a &lt;B&gt;
within a &lt;LI&gt; tag as opposed<br>
to embedding a &lt;H1&gt; within a &lt;LI&gt;? Within HTML the semantic meaning
of &lt;H1&gt;<br>
is that it's the main heading of a document and that it should be followed<br>
by the content of the document. Therefore it doesn't make sense to find a<br>
&lt;H1&gt; within a list.</font></p>
<p><font face="Verdana">Character formatting tags also are generally not
additive. For example, you<br>
might expect that:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;B&gt;&lt;I&gt;some
text&lt;/I&gt;&lt;/B&gt;</font></p>
<p><font face="Verdana">would produce bold-italic text. On some browsers it
does; other browsers<br>
interpret only the innermost tag.</font></p>
<p><font face="Verdana">Do the Final Steps</font></p>
<p><font face="Verdana"><b>Validate Your Code</b></font></p>
<p><font face="Verdana">When you put a document on a Web server, be sure to
check the formatting and<br>
each link (including named anchors). Ideally you will have someone else read<br>
through and comment on your file(s) before you consider a document finished.</font></p>
<p><font face="Verdana">You can run your coded files through an HTML validation
service that will<br>
tell you if your code conforms to accepted HTML. If you are not sure your<br>
coding conforms to HTML specifications, this can be a useful teaching tool.<br>
Fortunately the service lets you select the level of conformance you want<br>
for your files (i.e., strict, level 2, level 3). If you want to use some<br>
codes that are not officially part of the HTML specifications, this latitude<br>
is helpful.</font></p>
<p><font face="Verdana"><b>Dummy Images</b></font></p>
<p><font face="Verdana">When an &lt;IMG SRC&gt; tag points to an image that does
not exist, a dummy image<br>
is substituted by your browser software. When this happens during your final<br>
review of your files, make sure that the referenced image does in fact<br>
exist, that the hyperlink has the correct information in the URL, and that<br>
the file permission is set appropriately (world-readable). Then check online<br>
again!</font></p>
<p><font face="Verdana"><b>Update Your Files</b></font></p>
<p><font face="Verdana">If the contents of a file are static (such as a
biography of George<br>
Washington), no updating is probably needed. But for documents that are time<br>
sensitive or covering a field that changes frequently, remember to update<br>
your documents!</font></p>
<p><font face="Verdana">Updating is particularly important when the file
contains information such<br>
as a weekly schedule or a deadline for a program funding announcement.<br>
Remove out-of-date files or note why something that appears dated is still<br>
on a server (e.g., the program requirements will remain the same for the<br>
next cycle so the file is still available as an interim reference).</font></p>
<p><font face="Verdana"><b>Browsers Differ</b></font></p>
<p><font face="Verdana">Web browsers display HTML elements differently. Remember
that not all codes<br>
used in HTML files are interpreted by all browsers. Any code a browser does<br>
not understand is usually ignored though.</font></p>
<p><font face="Verdana">You could spend a lot of time making your file
&quot;look perfect&quot; using your<br>
current browser. If you check that file using another browser, it will<br>
likely display (a little or a lot) differently. Hence these words of advice:<br>
code your files using correct HTML. Leave the interpreting to the browsers<br>
and hope for the best.</font></p>
<p><font face="Verdana"><b>Commenting Your Files</b></font></p>
<p><font face="Verdana">You might want to include comments in your HTML files.
Comments in HTML are<br>
like comments in a computer program--the text you enter is not used by the<br>
browser in any formatting and is not directly viewable by the reader just as<br>
computer program comments are not used and are not viewable. The comments<br>
are accessible if a reader views the source file, however.</font></p>
<p><font face="Verdana">Comments such as the name of the person updating a file,
the software and<br>
version used in creating a file, or the date that a minor edit was made are<br>
the norm.</font></p>
<p><font face="Verdana">To include a comment, enter:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;!-- your comments here --&gt;</font></p>
<p><font face="Verdana">You must include the exclamation mark and the hyphens as
shown.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>For More Information</b></font></p>
<p><font face="Verdana">This guide is only an introduction to HTML, not a
comprehensive reference.<br>
Below are additional online sources of information. Remember to check a<br>
bookstore near you for Web and HTML books.</font></p>
<p><font face="Verdana"><b>Style Guides</b></font></p>
<p><font face="Verdana">The following offer advice on how to write
&quot;good&quot; HTML:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * Composing Good HTML<br>
&nbsp;&nbsp; * W3C's style guide for online hypertext</font></p>


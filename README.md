# Where-to-Place-Images-in-Your-Code

Where an image is placed 
in the code will affect how it 
is displayed. Here are three 
examples of image placement 
that produce different results:

1: before a paragraph
The paragraph starts on a new 
line after the image.
2: inside the start of a 
paragraph
The first row of text aligns with 
the bottom of the image.
3: in the middle of a 
paragraph
The image is placed between the 
words of the paragraph that it 
appears in.

<img src="images/bird.gif" alt="Bird" width="100" 
 height="100" />
<p>There are around 10,000 living species of birds 
 that inhabit different ecosystems from the 
 Arctic to the Antarctic. Many species undertake 
 long distance annual migrations, and many more 
 perform shorter irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" />There are around 10,000 living 
 species of birds that inhabit different 
 ecosystems from the Arctic to the Antarctic. Many 
 species undertake long distance annual 
 migrations, and many more perform shorter 
 irregular journeys.</p>
<hr />
<p>There are around 10,000 living species of birds 
 that inhabit different ecosystems from the 
 Arctic to the Antarctic.<img 
src="images/bird.gif" alt="Bird" width="100" 
height="100" />Many species undertake long 
 distance annual migrations, and many more perform 
 shorter irregular journeys.</p>



 Where you place the image in 
the code is important because 
browsers show HTML elements 
in one of two ways:
Block elements always appear 
on a new line. Examples of block 
elements include the <h1> and 
<p> elements.
If the <img> is followed by a 
block level element (such as a 
paragraph) then the block level 
element will sit on a new line 
after the imageas shown in the 
first example on this page.
Inline elements sit within a 
block level element and do not 
start on a new line. Examples of 
inline elements include the <b>, 
<em>, and <img> elements.
If the <img> element is inside a 
block level element, any text or 
other inline elements will flow 
around the image as shown in 
the second and third examples 
on this page.

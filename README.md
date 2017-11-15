# textToImage
Convert text to an image &amp; extract text from an image with Tesseract OCR

 MessageBlur takes a text from a text area and 
    turns it into an image. It then paints lines, circles, rectangles or "pen"
    style lines over the text. 
    
    This makes it hard or impossible for optical character recognition to figure out
    what a user wrote.
    
    Abasic extraction feture using Tesseract OCR is integrated to test how 
    resistant the obfuscation is against standard smart optical charcacter
    recongition.
    
    Once a desired level of obscurity has been reached, the user can save the image
    as a file and transfer is like any other file.
	
	What's new:
	-----------
	This is a full re-write of the original utility to improve perfomance and
	simplify the javascript.
	
	New features:
	------------
	1) Pencil tool
	In "random lines mode", this adds letters/symbols/numbers randomly to the image.
	In "free hand mode", it works just like a normal free-hand drawing pencil.
	2) Manual letters/characters directly into the image
	Simply click anywhere, and start typing. A good way to add nonsense text.
	Note there is no blinking cursor, nor are there backspace or delete functions.
 	
	Make sure to try out the "Peel" feature. It splits the image into two, making
    them look as if strips had been "peeled off".	

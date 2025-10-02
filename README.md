# DEBUGGING RESULTS:

## W3C HTML Validator corrections:

1. From line 1, column 16; to line 2, column 6; "This document appears to be written in English. Consider adding lang="en" (or variant) to the html start tag."
<!-- <html> -->
<html lang="en">

2. From line 5, column 5; to line 5, column 10; "Element meta is missing one or more of the following attributes: charset, content, http-equiv, itemprop, name, property."
    <!-- <meta> -->
    <meta charset="UTF-8">

3. From line 6, column 5; to line 6, column 76; "Trailing slash on void elements has no effect and interacts badly with unquoted attribute values."
    <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0" /> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

4. From line 19, column 7; to line 19, column 46; "An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images."
      <!-- <img src="easter-bunny-150-profile.png"> -->
      <img src="easter-bunny-150-profile.png" alt="Easter Bunny">

5. From line 60, column 13; to line 60, column 15; "Element p not allowed as child of element h3 in this context. (Suppressing further errors from this subtree.)"
          <h3>Enough Content
            <!-- <p>You need enough content to thoroghly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p> -->
          <p>You need enough content to thoroghly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p>

6. From line 61, column 9; to line 61, column 18; "End tag article seen, but there were open elements." AND 7. From line 59, column 11; to line 59, column 14; "Unclosed element h3."
        <article>
          <!-- <h3>Enough Content -->
          <h3>Enough Content</h3>



## W3C CSS Validator corrections:

1. 33 	footer   ; "Value Error : color #B2 is not a valid color 3 or 6 hexadecimals numbers : #B2 "
	/* color: #B2; */
	color: #B2D732;

2. 43 	h1 	; "Value Error : font-size Too many values or values are not recognized : 5 vw "
	/* font-size: 5 vw; */
	font-size: 5vw;

3. 66 	p 	; "Value Error : line-height Unknown dimension 1.35me "
	/* line-height: 1.35me; */
	line-height: 1.35em;

4. 85 	.error 	; "Value Error : color #FE27122 is not a valid color 3 or 6 hexadecimals numbers : #FE27122 "
	/* color: #FE27122; */
	color: #FE2712;

5. 94 	a:hover 	; "Value Error : text-decoration all is not a text-decoration value : all "
	/* text-decoration: all; */
	text-decoration: none;

## Contrast Checker corrections:
1. 

## Other corrections:


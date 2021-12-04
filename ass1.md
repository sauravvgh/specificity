Assignment 1: List all the pseudo Elements with their usages

A css pseudo element is used to style specified parts of an element

For example , it can be used to:
- Style the first letter, or line, of an element
-insert the content before, or after the content of an element

Syntaxes of Pseudo elements:

selector::pseudo-element{
    property: value
}

* the ::first-line Pseudo-element can only be applied to block level elements
The following property applies to the ::first-line pseudo-element:

.Font properties
.color properties
.background properties
.word-spacing
.letter-spacing
.text-decoration
.vertical-align
.text-transform
.line-height
.clear

*Notice the double colon notation- ::first-line versus :first-line

The double colon replaced the single-colon notation for pseudo-elements in css3.

*The ::first-letter pseudo element

the ::first-letter pseudo-element is used to add a special style to the first letter of a text

The following example formats the first letter of the text in all <p> elements

example:
p:: first-letter{
    color: #ff0000;
    font-size: xx-lThe following properties apply to the ::first-letter pseudo- element: 

-font properties
-color properties 
-background properties
-margin properties
-padding properties
-border properties
-text-decoration
-vertical-align (only if "float" is "none")
-text-transform
-line-height
-float
-cleararge;
}
note: the ::first-letter pseudo-element can only be applied to the block-level elements.

ALL CSS PSEUDO ELEMENTS:

Selector	    Example	                    Example description

::after	        p::after	                Insert something after the content of each <p> element
::before	    p::before	                Insert something before the content of each <p> element
::first-letter	p::first-letter	            Selects the first letter of each <p> element
::first-line	p::first-line	            Selects the first line of each <p> element
::marker	    ::marker	                Selects the markers of list items
::selection	    p::selection	            Selects the portion of an element that is selected by a user


Assignment-2 : all css pseudo classes with their usages.
All CSS Pseudo Classes
Selector	            Example	                        Example description

:active	                a:active	                    Selects the active link
:checked	            input:checked	                Selects every checked <input> element
:disabled	            input:disabled	                Selects every disabled <input> element
:empty	                p:empty	                        Selects every<p> element that has no children
:enabled	            input:enabled	                Selects every enabled <input> element
:first-child	        p:first-child	                Selects every <p> elements that is the first child of its parent
:first-of-type	        p:first-of-type	Selects every   <p> element that is the first <p> element of its parent
:focus	                input:focus	                    Selects the <input> element that has focus
:hover	                a:hover	                        Selects links on mouse over
:in-range	            input:in-range	                Selects <input> elements with a value within a specified range
:invalid	            input:invalid	                Selects all <input> elements with an invalid value
:lang(language)	        p:lang(it)	                    Selects every <p> element with a lang attribute value starting with "it"
:last-child	            p:last-child	                Selects every <p> elements that is the last child of its parent
:last-of-type	        p:last-of-type	                Selects every <p> element that is the last <p> element of its parent
:link	                a:link  	                    Selects all unvisited links
:not(selector)	        :not(p)	                        Selects every element that is not a <p> element
:nth-child(n)	        p:nth-child(2)	                Selects every <p> element that is the second child of its parent
:nth-last-child(n)	    p:nth-last-child(2)	            Selects every <p> element that is the second child of its parent,                       counting from the last child       
:nth-last-of-type(n)	p:nth-last-of-type(2)	        Selects every <p> element that is the second <p> element of its parent, counting from the last child
:nth-of-type(n)	        p:nth-of-type(2)	            Selects every <p> element that is the second <p> element of its parent
:only-of-type	        p:only-of-type	                Selects every <p> element that is the only <p> element of its parent
:only-child	            p:only-child	                Selects every <p> element that is the only child of its parent
:optional	            input:optional              	Selects <input> elements with no "required" attribute
:out-of-range	        input:out-of-range	            Selects <input> elements with a value outside a specified range
:read-only	            input:read-only	                Selects <input> elements with a "readonly" attribute specified
:read-write	            input:read-write	            Selects <input> elements with no "readonly" attribute
:required	            input:required	                Selects <input> elements with a "required" attribute specified
:root	                root	                        Selects the document's root element
:target	                #news:target	                Selects the current active #news element (clicked on a URL containing that anchor name)
:valid	                input:valid	                    Selects all <input> elements with a valid value
:visited	            a:visited	                    Selects all visited links

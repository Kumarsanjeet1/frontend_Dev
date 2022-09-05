# we can provide CSS in three ways-

*  Embedded Stylesheets
*  External Stylesheets
*  Inline Stylesheets

<hr>

* External Stylesheets - It allows me to define Styles for a particular HTML document. (Works ? - Where we create a CSS document file and creating some attributes for whole HTML element and link it into the head section of html).


for example - link the CSS file in the html document.

<p> &lt head &gt </p>
<p> &lt link rel="stylesheet" href="styles.css" /&gt </p>
</head>



<hr>


*   Embedded Stylesheets - It allows me to define style for html elements. (Works ? - It will define in the head section of the html document).
for example-

<p>
 &lt head &gt
 &lt style &gt 
 p{
 color:orange;}
 &lt /style &gt
&lt /head &gt 

<hr>


*  Inline Stylesheets - Inline stylesheets used to style for a particular html element. (Works ? - It wiil define in the html element section).

for example-


<p>&ltbody&gt</p> <p> &lt p style= "color:blue;" &gt This is Inline Stylesheets &lt /p &gt </p>
&lt/body&gt


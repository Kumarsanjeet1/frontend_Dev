# Differnt ways to select element for styling purposes!
<h3> Basic Selector </h3>

*   Type

*   Id 

*   Class

*   Attributes

<hr>

*  <h4> Type Selector - </h4> The CSS Type Selector matches elements by node names. ( it means, type selector select all the element by its types).

    <p>for example -  <br> element can be paragraph type <br> &lt;p&gt; &rarr;<br>
                                                                   p{ <br>
                                                                     color:orange; <br>
                                                                     };
           
    <br>element can be heading type  <br> &lt;h1&gt; &rarr; <br>
                                                    h{ <br>
                                                         margin:3px; <br>
                                                       };
    
    
    
    
    <br> element can be hyperlink type  <br> &lt;a&gt; &rarr; <br>
                                                    a{ <br>
                                                         margin:3px; <br>
                                                       };
    
    <br>  element can be body tag <br> &lt;body&gt; &rarr; <br>
                                                    a{ <br>
                                                         margin:3px; <br>
                                                       }; 





</p>
    
    
    
 <hr>
 
*   <h4> ID Selector - </h4> 
*   Through Id element we will select element through `unique id`, which is define in Id. 
*   The ID should be unique for particular element.
*   To select ID's element in CSS through `# (pound sign)`
<br> For example- 
<br> `#(Id's_name)` <br> `{` <br> `color:blue;`<br>`}`





<hr>

*  <h4> Class Selector -</h4>
*  With same class can contain multiple elements.
*  To select class elements in CSS through `. (fullstop)`
<br> For example- 
<br> `.(class_name)` <br> `{` <br> `color:green;`<br>`}`



<hr>

*  <h4> Attribute Selector -</h4>
*  Through Attribute selector, we select the element with specified attribute.
*  Value should be anything from Attribute.
*  To select the attribute element in css through `[ attribute value ]`.
*  Attribute value means- any value, the element and elements have contained.

  For Example - <br>
   a[href="www.google.com"] <br> { <br> color:orange;<br>}<br> - `the value should be exact, then the attribute will select.`<br>
   <br>
   a[href*="google"] <br> { <br> color:orange;<br>}<br> - `value matched a bit, then the attribute will select.`<br>
   <br>
   a[href^="www"] <br> { <br> color:orange;<br>}<br> - `the value should be start from value,then the attribute will select.` <br>
   <br>
   a[href="com"] <br> { <br> color:orange;<br>}<br> - `the value should be end with value, then the attribute will select.`<br>
   <br>

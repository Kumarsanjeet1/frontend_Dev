# 📓 Table element
➡️ HTML table element allow web-developer to arrange the data into rows and columns.

🟣 Attributes -

➡️Syntax:

      <table>
      ....
      ....
      </table>
<br>
🔵tr

➡️ tr (table row) (creates table rows)

        Syntax:
          <table>
               <tr>
               ....
               ....
               </tr>
          </table>
<br>
🔵th 

➡️ th (table head) (creates table rows and you can add table heading with this element!)

        Syntax:
          <table>
               <tr>
                 <th> table heading 1 </th>
                 <th> table heading 2</th>
                 <th> table heading 3</th>
               </tr>
          </table>
 <h2>:Output</h2> 
     <table>
               <tr>
                 <th> table heading 1 </th>
                 <th> table heading 2</th>
                 <th> table heading 3</th>
               </tr>
          </table>

<br>
🔵 td 

➡️ td (table data) (creates table rows and you can add table data with this element!)

        Syntax:
          <table>
               <tr>
                 <td> Add table data in row formate</td>
                 <td> Add table data in row formate</td>
                 <td> Add table data in row formate</td>
                 <td> Add table data in row formate</td>
               </tr>
          </table>
<h2>Output:</h2>
<table> 
               <tr>
                 <th> table heading 1 </th>
                 <th> table heading 2</th>
                 <th> table heading 3</th>
               </tr>
               <tr>
                 <td> Add table data in row formate</td>
                 <td> Add table data in row formate</td>
                 <td> Add table data in row formate</td>
               </tr>
</table>
<br>

🔵 Caption tag 

➡️ caption tags insert the table caption.

      <table> 
              <caption>Student Information</caption>
               <tr>
                 <th>Enrollment Number</th>
                 <th> Name</th>
                 <th> City</th>
               </tr>
               <tr>
                 <td> 0188CS201082 </td>
                 <td> Kumar Sanjeet </td>
                 <td> Lakhisarai </td>
               </tr>
      </table>
      
<h2>Output:</h2>
<table> 
              <caption>Student Information</caption>
               <tr>
                 <th>Enrollment Number</th>
                 <th> Name</th>
                 <th> City</th>
               </tr>
               <tr>
                 <td> 0188CS201082 </td>
                 <td> Kumar Sanjeet </td>
                 <td> Lakhisarai </td>
               </tr>
      </table>


<br>

🔵 Colgroup 

➡️ colgroup specifies a group of columns in a table for fomatting and it is useful for apply styles in entire columns, instead for repeating styles for each columns again and again.

🟦 Attribute:
align: It is used to align the text or content in the group of columns. The value of the aligned property is left, right, center, justify, char.

char: It is used to align the character in a column group and the value of these attributes is the character.

charoff: It is used to sets the number of characters that will be aligned from the character specified by the char attribute. The value of these attributes is in numeric form.

span: It is used to specify the number of columns that have colgroup tag. The values are in numeric form.

valign: It specifies the vertical alignment of content in a colgroup. It’s values are the top, middle, bottom, baseline.

width: It defines the width of a column group. It’s values are pixels, %, relative_length.





            Syntax:
            
         <table> 
              <caption>Student Information</caption>

              <colgroup>
                  < col span="2" style="background-color: green; color: white" />
              </colgroup>

                  
              <colgroup>
                  <col style="background-color: orange" />
              </colgroup>


               <tr>
                 <th>Enrollment Number</th>
                 <th> Name</th>
                 <th> City</th>
               </tr>
               <tr>
                 <td> 0188CS201082 </td>
                 <td> Kumar Sanjeet </td>
                 <td> Lakhisarai </td>
               </tr>
               <tr>
                 <td> 0188CS201105 </td>
                 <td> Vijay Saini </td>
                 <td> Sujalpur </td>
               </tr>
           </table>



<h2>Output:</h2>
<table> 
  <caption>Student Information</caption>

      
  <colgroup>
   <col span="1" style="background-color: green; color: white" /> 
  </colgroup>

                  
 
  <tr>
    <th>Enrollment Number</th>
    <th> Name</th>
    <th> City</th> 
  </tr>
  <tr>
    <td> 0188CS201082 </td>
    <td> Kumar Sanjeet </td>
    <td> Lakhisarai </td>
  </tr>
  <tr>
    <td> 0188CS201105 </td>
    <td> Vijay Saini </td>
    <td> Sujalpur </td>
  </tr>
</table>

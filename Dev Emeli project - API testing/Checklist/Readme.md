
  Platform: PC<br>
  OS: Windows<br> 
  OS Version: 10 x64<br>
  Tester: Nikolay Ursalov<br>

<table>
  <tr>
    <th colspan="2"><h3>Name of the verify</h3></th>
    <th colspan="2"><h3>Description of the verify</h3></th>
    <th><h3>Status</h3></th>
    <th colspan="2"><h3>Bug link</h3></th>
  </tr>

  <tr>
    <td colspan="2"><b>Creating of a product card <br>POST /api/v1/orders<b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">Status 201</td>
    <td></td>
    <td colspan="2"></td>
  </tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card creating with main fields</td>
    <td>Passed</td>
    <td colspan="2">Ссылка на баг-репорт ссылка на баг-репорт<a href="https://docs.google.com/spreadsheets/d/1meeA4eLDlrvXyTQUmsVTSgXwGKC_EpaXH5ZwLcABQ_E/edit#gid=0">Ссылка на баг-репорт</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card creating with empty fields</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card fields are filled with default values</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Reusing the name of an existing product</td>
    <td>Passed</td>
    <td></td>
</tr>
      
<tr>
    <td colspan="2"></td>
    <td colspan="2">Empty JSON</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Product creation date</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Changing of “read-only” properties</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1s-HLKK0Ug2x-P5IL_dIPtLnXzWMwV52jxRlorZncO5Y/edit#gid=0">Bug report 08</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">“Dimensions” field has only one parameter</td>
    <td>Passed</td>
    <td></td>

</tr>


<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is less than a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is equal to a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Name is more than 100 letters</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1ixMNOZafzP_OlzMEGBeDBFSbIhklWbzp1mwOaAp3gvA/edit#gid=0">Bug report 01</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Description is more than 600 letters</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1ifrCms__vEzXN4rIkwy7FWlK4t_Unt23hyPhRKl7FCA/edit#gid=0">Bug report 02</a></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is equal to a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Status 400</td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Fields validation (invalid data)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2"></td>
    <td></td>
    <td></td>
</tr>


<tr>
    <td colspan="2"><b>Retrieve and view a specific product by ID: <br>GET <b></b>/wp-json/wc/v3/products/<id><b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Status 200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting of the created product card (valid product id)</td>
    <td>Passed</td>
    <td colspan="2">Ссылка на баг-репорт ссылка на баг-репорт<a href="https://docs.google.com/spreadsheets/d/1meeA4eLDlrvXyTQUmsVTSgXwGKC_EpaXH5ZwLcABQ_E/edit#gid=0">Ссылка на баг-репорт</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sending GET request twice (idempotency)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PUT request</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PATCH request</td>
    <td>Passed</td>
    <td></td>
</tr>
      
<tr>
    <td colspan="2"></td>
    <td colspan="2">404</td>
    <td></td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product using invalid ID (inappropriate data type)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a not existing product (valid ID)</td>
    <td>Passed</td>
    <td></td>
</tr>


<tr>
    <td colspan="2"><b>Retrieve and view a list of products<br>GET <b></b>/wp-json/wc/v3/products/<b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Status 200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting the list of last added 20 product cards by default</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a list with a limited number of products (max)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a list with a limited number of products (min)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Paging through results using offset (valid value)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the descending order</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the ascending order</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Limiting results to matching a string</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Limiting results to matching a status</td>
    <td>Passed</td>
    <td></td>
</tr>  
<tr>
    <td colspan="2"></td>
    <td colspan="2">Exclude one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Exclude more than one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Include one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Include more than one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>

      
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the ascending order</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Using the combination of parameters</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Status 400</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Paging through results using offset (invalid value)</td>
    <td>Passed</td>
    <td></td>
</tr>




</table>



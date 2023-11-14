



  Platform: PC<br>
  OS: Windows<br> 
  OS Version: 10 x64<br>
  Tester: Nikolay Ursalov<br>



<table>

<tr>
  <th colspan="2"><h3>Checking</h3></th>
  <th><h3>Status</h3></th>
  <th><h3>Bug / Comments</h3></th>
</tr>

<tr>
  <td colspan="2"><h3>1. /set_phone</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2"><b>Sending one valid phone number</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.1. Phone number with amount of digits on the range 9-15</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.2. With "+" character in the start</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.3. With 00 number in the start</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.4. With 0 in the start</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2"><b>Send one invalid phone number</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.5. Phone number with 8 and 16 digits</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.6. Phone number with special characters: ()-</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.7. Using Latin, Cyrillic alphabet</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.8. Phone number with a space inside</td>
  <td>Passed</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><b>Send more than one phone number (positive scenario)</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.9. Send two phone numbers separated by a comma</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.10. Send three phone numbers separated by a comma</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2"><b>Send more than one phone number (negative scenario)</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.11. Send one valid and one invalid phone numbers</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.12. Send two phone numbers separated by a space</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.13. Send two phone numbers with different combinations of input</td>
  <td>Passed</td>
  <td></td>
</tr>






<tr>
  <td colspan="2"><h3>2. /set_email</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2"><b>Send a valid email address</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.1. Email address with numbers in the username part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.2. Email address with -_ characters in the username part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2"><b>Send an invalid email address</b></td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.3. Email address without @ character</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.4. Email address without dot in the domain name part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.5. Email address without the domain name part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.6. Email address without the username part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.7. Email address with special characters (except _ and - characters)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.8. Email address with numbers in the domain name part</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.9. Email address in CamelCase format</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.10. Email address with a space inside</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.11. Email address with one of the following characters at the beginning: @.-_</td>
  <td>Passed</td>
  <td></td>
</tr>


<tr>
  <td colspan="2"><h3> /invite_group_new </td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">Send a valid data</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">Check a received invite link</td>
  <td>Skipped</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">Send an invalid data (inappropriate data types)</td>
  <td>Failed</td>
  <td><a href="https://docs.google.com/spreadsheets/d/1uOoqdZPZafw1FRrFuZ5T7Wd3EeA6_8nPSSRIfzM31yk/edit#gid=0">Bug report 12</a></td>
</tr>
</tr>
    <tr>
  <td colspan="2">Send an empty field</td>
  <td>Passed</td>
  <td></td>
</tr>


<tr>
  <td colspan="2"><h3> /certificate </td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">Send a valid id of a generated certificate</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">Send an invalid id (inappropriate data types)</td>
  <td>Failed</td>
  <td><a href="https://docs.google.com/spreadsheets/d/1bXGWtN_nC8rS-nqif5d7xvoF2fzvuHbQT6AbdUL1oWo/edit#gid=0">Bug report 13</a></td>
</tr>
    <tr>
  <td colspan="2">id number of certificate that doesn’t exist</td>
  <td>Passed</td>
  <td></td>
</tr>
    <tr>
  <td colspan="2">Send an empty field</td>
  <td>Passed</td>
  <td></td>
</tr>


    
<tr>
  <td colspan="2">Send an invalid data (inappropriate data types)</td>
  <td>Failed</td>
  <td><a href="https://docs.google.com/spreadsheets/d/1uOoqdZPZafw1FRrFuZ5T7Wd3EeA6_8nPSSRIfzM31yk/edit#gid=0">Bug report 12</a></td>
</tr>

   


</table>


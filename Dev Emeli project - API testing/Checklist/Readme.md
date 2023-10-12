
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
    <td colspan="2">Changing of the “Read-only” properties</td>
    <td>Passed</td>
    <td></td>
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
    <td colspan="2">Short_description is more than 250 letters</td>
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
  <td colspan="2">4.2. Constructor of the level</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.3. Navigation between mini games</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.4. Mini games modes</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.5. Guide-line before starting the game </td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.6. Guide-line after the game is finished</td>
  <td>Pass</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><h3>5. Game process</h3></td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.1. Guide-line for a first time experience</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.2. The custom format of the creating a mini game</td>
  <td>Failed</td>
  <td>Bug Report 001. The object model that creates enemies models is set up outside the game area <a href="https://docs.google.com/spreadsheets/d/1AkTl4XcBWRuirASFcQn99zarTem1yJeD/edit?usp=drive_link">Link to Bug Report 001</a></td>
</tr>

<tr>
  <td colspan="2">5.3. Gameplay flow including starting and completing the level</td>
  <td>Failed</td>
  <td>Bug Report 002. The timer of the game round isn’t stopped after the game is collapsed
  <a href="https://docs.google.com/spreadsheets/d/1MWLGoraF_eIUYwD_x6T1-P8UT2ttqVMi/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 002</a>
  </td>
</tr>
<tr>
  <td colspan="2">5.4. Character control </td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5. Saving scores</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.1. During the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.2. After the each mini game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.3. After the relaunching of the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.6. Increasing the score during the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.7. Pause</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.8. Mini game timer</td>
  <td>Failed</td>
  <td>Bug Report 003. The timer of the game round isn’t stopped after the game is collapsed   
  <a href="https://docs.google.com/spreadsheets/d/1dYIw_f5Ee45g1lpl0jiZws-KVrvgtIQU/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 003</a></td>
</tr>



<tr>
  <td colspan="2">5.9. Menu options</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.10. Mini games' animation</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.11. Appearance of the main model characters</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.12. Appearance of the additional model characters (map, game objects)</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13. Background Music and Sounds</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.1. On the each stage of the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.2. Сompletely off the sound</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.3. Sound down</td>
  <td>Pass</td>
  <td></td>
</tr>
                                         
<tr>
  <td colspan="2">5.14. Game loading indicator</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15. Exit</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15.1. Via menu options</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15.2. Via cross icon</td>
  <td>Pass</td>
  <td></td>
</tr>


</table>



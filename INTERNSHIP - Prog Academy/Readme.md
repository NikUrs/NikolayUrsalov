<h3>Internship - Test Documentation</h3>
Testing of the project, which consists of<br>
- “Invite” page<br>
- “Registration” page<br>
- “Success” page<br>
- “Certificate” page<br>
- Сhatbot commands<br><br>

<h4>User / Admin (manager) rights</h4>

-- “Invite” page
User can enter an invite code, which he got from a manager or another student. After that, he got access to the “Prog Academy” school website's feature functionality.

-- “Registration” page
On this page user sends the registration form, which is filled with his personal information, to the server. After sending that form the user gets the email with the link to the chatbot “Prog Julia” in Telegram. <br>

-- “Success” page
User can go to the chatbot “Prog Julia” by clicking on the button. <br>
Also, the link to the chatbot “Prog Julia” is sent to user's email address. <br>

-- Chatbot commands
For managers, chatbot commands help to automate their work. <br>
Students can get the necessary information without managers' help.

<h4>Admin (manager) rights</h4>
-- “Certificate” page<br>
Managers can generate a certificate of any course for one student or for one group.  <br>

<h4>A set of chatbot commands:</h4>
/set_email: set email(s) to user<br>
/certificate: Command to generate and send certificates to students.<br>
/invite_group_new: create an invite code to join the group of users<br>
/help: List all commands<br>
/group_list: list all groups<br>
/users_list: show a list of all users<br>
/set_phone: set phone(s) to user<br>
/user_find: find the user by phone or e-mail<br>
/group_new: create a new group of users<br>
/broadcast: broadcast message to users<br><br>

Successfully message: "Command execution finished successfully!"<br><br>

<h3>Testing types</h3>
<h4><strong>Functional</strong> testing <a href="https://github.com/NikUrs/NikolayUrsalov/blob/main/INTERNSHIP%20-%20Prog%20Academy/Functional/Readme.md">click to the link</a></h4> 
- <strong>Features</strong> (including Mobile site version)<br>
- <strong>API</strong> testing<br>
- <strong>Chatbot commands testing</strong><br>
<h4><strong>GUI</strong> (including Mobile site version) <a href="https://github.com/NikUrs/NikolayUrsalov/blob/main/INTERNSHIP%20-%20Prog%20Academy/GUI/Check%20list%20%2B%20Bug%20reports.md">click to the link</a></h4>
<h4><strong>Cross Browser</strong> testing</h4>
1. Opera 100.0.4815.21<br>
2. Google Chrome 114.0.5735.133<br>
3. Mozilla Firefox 116.0.2<br>
4. Safari 16.5.2<br><br>

<strong>Security</strong> testing
1. Block user’s ip on 1 hour (improvement).<br>
2. Cookies don’t store invite code.<br><br>


<a href="https://docs.google.com/spreadsheets/d/1RLyIneYOWRytbx3LyRzOx9SPPTmG_Q41-LPbeXGAhew/edit?usp=drive_link">Bug Report 001 [Back-end-01]. The success page is shown after sending the registration form with the reused email address.</a>

<a href="https://docs.google.com/spreadsheets/d/1Fn7lGfk7Sxg4w7P8sfubcdUS0Z6yhLiAXcfR8-r9ZE4/edit?usp=drive_link">Bug Report 002 [Back-end-02]. After sending the reused invite code the registration page is opened.</a>

<a href="https://docs.google.com/spreadsheets/d/1K18xAxBUOHqcjI4q2lWE5ApOid_nMb4KOtb_z22IVS0/edit?usp=drive_link">Bug Report 003 [Front-end-01]. After clicking on the "Surname" label the "Fist name" field is got the focus state.</a>

<a href="https://docs.google.com/spreadsheets/d/1N_7oR7md5W4-cm_o_eM-f7l1znAkgDw-XhvdIkCfEE0/edit?usp=drive_link">Bug Report 004 [Front-end-02]. After sending the filled form with an unavailable network connection, the status code 500 is shown when this network connection is restored.</a>

<a href="https://docs.google.com/spreadsheets/d/1aQeag_YBwVyuJ-0ZhFgzSdkAQBQXZ_0IsHVEopMRlsE/edit?usp=drive_link">Bug Report 005 [Front-end-03]. After sending the filled form with an unavailable network connection, the status code 500 is shown when this network connection is restored.</a>

<a href="https://docs.google.com/spreadsheets/d/12KEEJFddZtl741j8TxCts92ghMKKscoNiEowJAWGCqc/edit?usp=drive_link">Bug Report 006 [Front-end-04]. The registration form fields are shifted in relation to each other on mobile screens with a width range of 575-360.</a>

<a href="https://docs.google.com/spreadsheets/d/1L49IR-pGNUU1iiRUX3gF39JA6HDmMazQv_KX39uTFUw/edit?usp=drive_link">Bug Report 007 [Front-end-05]. The text of label elements is cut on different mobile screens with the width in the range 1300-576.</a>

<a href="https://docs.google.com/spreadsheets/d/1hCuAofR_FKh1qOyVsavH9sQf0ecu8mzi1zQr31RIumw/edit?usp=drive_link">Bug Report 008 [Front-end-06]. Cyrillic symbols in the domain name of the email address are shown in the "Email" field without a validation error message.</a>

<a href="https://docs.google.com/spreadsheets/d/1yyTTQz5-Sj18Bj5u6iT-W3JxO7q80B_doJE2B71GNdA/edit?usp=drive_link">Bug Report 009 [Back-end-03]. JSON data in the response body isn't matched with the technical task after sending the argument with an invalid value for the "name" key.</a>

<a href="https://docs.google.com/spreadsheets/d/1naco2jsyGZx9750tzzymmdFa2raWN0kwfsmNIvClzOY/edit?usp=drive_link">Bug Report 010 [Back-end-04]. JSON data in the response body isn't matched with the technical task after sending invalid data in the "inviteCode" key.</a>

<a href="https://docs.google.com/spreadsheets/d/1GUh7iq5HOQi4Y1UEAvH2Tiz7EjniMKI_TgmAdWLBZxA/edit?usp=drive_link">Bug Report 011 [Back-end-05]. JSON data in the response body isn't matched with the technical task after when one invite code is used more than 5 times.</a>

<a href="https://docs.google.com/spreadsheets/d/1k1Ho59dMCFbFvGevWtq7IEgSbBQ7ae9TdQ2aKOYOh6w/edit?usp=drive_link">Test case 001. Entering valid data in the "Email" field.</a>

<a href="https://docs.google.com/spreadsheets/d/1hnf9GQcA1bh_rulY5DjwS9RoPrIlOp5Z/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Test case 002. Entering the invalid data in the "Email" field.</a>

<a href="https://docs.google.com/spreadsheets/d/1NYSdLCJyl7ICzIMEK1sHL3pvW-ngJJg5/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Test case 004. Sending request with an invalid data for the name key.</a>











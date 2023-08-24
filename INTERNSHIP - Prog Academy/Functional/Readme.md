<h3>Functional testing</h3>

- Features
- <a name="Chatbot">Chatbot commands</a>

<h3>Features</h3>

Test-cases<br>
- <a href="https://docs.google.com/spreadsheets/d/1k1Ho59dMCFbFvGevWtq7IEgSbBQ7ae9TdQ2aKOYOh6w/edit?usp=drive_link">Entering valid data in the "Email" field</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1hnf9GQcA1bh_rulY5DjwS9RoPrIlOp5Z/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Entering the invalid data in the "Email" field</a><br><br>

Bug-reports<br>
- <a href="https://docs.google.com/spreadsheets/d/1tNagMIF4eYjgD_BL5_GjFs7X_ddDJYSbpO9NZRbFwHs/edit?usp=drive_link">The invalid symbols characters are shown after typing in the "Name" field without any validation error message.</a>
- <a href="https://docs.google.com/spreadsheets/d/1N_7oR7md5W4-cm_o_eM-f7l1znAkgDw-XhvdIkCfEE0/edit#gid=0">The valid data is shown in the "Email" field with the validation error message.</a> 

<h3>Chatbot commands testing</h3>(#Chatbot)

1- /set_phone<br>
	- send one valid phone number<br>
		- phone number with amount of digits on the range 9-15<br>
		- with "+" character in the start<br>
		- with 00 number in the start<br>
		- with 0 in the start<br>
		- without "+" in the start<br>
	- send one invalid phone number<br>
		- phone number with 8 and 16 digits<br>
		- phone number with special characters: ()-<br>
		- using Latin, Cyrillic alphabet<br>
		- phone number with a space inside<br>
	- send more than one phone number (positive scenario)<br>
		- send two phone numbers, that are separeted by a comma<br>
		- send three phone numbers, that are separeted by a comma<br>
	- send more than one phone number (negative scenario)	<br>
		- send one valid and one invalid phone numbers<br>
		- send two phone numbers, that are separeted by a space<br>
		- send two phone numbers with different combinations of format <br><br>

2- /set_email<br>
	- send valid email address<br>
	- email address with numbers in username part<br>
	- email address with _- characters in the username part<br>
	- send invalid email address<br>
		- email address without @ character<br>
		- email address without dot in the domain name part<br>
		- email address without domain name part<br>
		- email address without username<br>
		- email address with special characters (except -_)<br>
		- email address with numbers in domain name part	<br>
		- email address with CamelCase<br>
		- email address with a space inside<br>
		- email address with one of the follow characters in the start: @.-_  <br><br>

3- /group_list<br>
	- check the existing groups<br>
	- check a group which was created in current “session” <br>
	- check the successfully message<br>
	- check the error message <br><br>

4- /invite_group_new<br>
	- send a valid data<br>
	- check a received invite link	<br>
	- send an invalid data (inappropriate data types)<br><br>

5- /help<br>
	- check the list of commands<br>
	- launching of each command from the list<br><br>

6- /broadcast<br>
	- check a message transfer with a valid data<br>
	- check a message transfer with an invalid data<br><br>

7- /group_new<br>
	- ввод валидного значения (позитивный сценарий)<br>
	- ввод невалидных значений<br><br>

8- /user_find<br>
	- send a valid id<br>
	- send an invalid id<br>
		- if user's id was removed<br>
		- use inappropriate data types<br><br>

9- /certificate<br>
	- send valid existing id of generated certificate<br>
	- send invalid id of generated certificate<br>
		- id number that doesn’t exist<br>
		- inappropriate data types<br>
		- id is empty	 <br><br>

10- /users_list<br>
	- check the existing list of users<br>
	- checking the created group during one "session"<br><br>

Test-cases<br>
- <a href="https://docs.google.com/spreadsheets/d/18hdKZYyNR6_YuQIqBOobO_dhKbYjztsd/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Checking of using the "set_phone" command.</a><br><br>

Bug-reports<br>
- <a href="https://docs.google.com/spreadsheets/d/1bXGWtN_nC8rS-nqif5d7xvoF2fzvuHbQT6AbdUL1oWo/edit?usp=drive_link">The validation error message isn’t shown after sending an invalid data when using the /certificate command.</a>
- <a href="https://docs.google.com/spreadsheets/d/1-PsMUQ-eoBH3yQ_-2lPkC6U99ULIt5nGg-VgJOunlzc/edit?usp=drive_link">The error message is shown after sending a phone number without “plus” character.</a>

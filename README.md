# Postman-API

This includes the answers for following questions.

01. Create a workspace “WE”.
02. Create a collection using your SID.
03. Create “GET” and “POST” folders inside your collection with the type of “No Auth”.
04. Create one GET and POST request inside each folder.
------------------------------------------------------------------------------------------------------------------------------------------------
Method Request Response Body
GET https://reqres.in/api/unknown/2 200
{
 "data": {
 "id": 2,
 "name": 
"fuchsia rose",
 "year": 2001,
 "color": 
"#C74375",
 "pantone_value": 
"17-2031"
 },
 "support": {
 "url": 
"https://reqres.in/#sup
port-heading",
 "text": "To 
keep ReqRes free, 
contributions towards 
server costs are 
appreciated!"
 }
}
2
POST https://reqres.in/api/login 200
{
 "token": 
"QpwL5tke4Pnpja7X4"
}
{
 "email":
"eve.holt@reqres.in",
 "password":
"cityslicka"
}
05. Create at least 03 collection level variables for POST requests and refer them correctly. 
06. Create two environments.
i. ENV_TRUE - With true values
ii. ENV_FALSE – with false vales
07. Write Scripts to GET and SET local variables and global variables as follows.
Method Local Global
Variable Values Variable Values
SET emp_id Em_001 bank_name BOC
emp_dept IT Branch_name Nawala
GET emp_dept IT Branch_name Nawala
---------------------------------------------------------------------------------------------------------------------------------------------------------------
08. Add external data set (CSV or JSON) to run the collection. 

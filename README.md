# Tugas-Final-Project-12-API

HERMAN KIANA
url repo github

1. Methode POST.
- Create new object repository "Methode POST"
- Input Url http://reqress.in/api/users
- Masukan Json body:
	{
		"name": "alex",
		"job": "leader"
					}
- Create Test case Methode POST
- Add keyword Send Request
	- Object "Create User using Method POST"
	- Output "Response"
- Add Verify Element Property value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "name"
	- Input param name "value" Param type "Object" Value Type "string" Value "alex"
- Add Verify Element Property value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "job"
	- Input param name "value" Param type "Object" Value Type "string" Value "leader"

2. Methode GET.
- Create new object repository "Get Singgle User" Metod GET
- Input Url http://reqress.in/api/users/2					}
- Create Test case Get Singgle User
- Add keyword Send Request
	- Object "Get Singgle User"
	- Output "Response"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "data.email"
	- Input param name "value" Param type "Object" Value Type "string" Value "janet.weaver@reqres.in"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "data.first_name"
	- Input param name "value" Param type "Object" Value Type "string" Value "janet"
- Add Verify Element Proprty value
	- Input param name "response" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "locator" Param type "string" Value Type "string" Value "data.last_name"
	- Input param name "value" Param type "Object" Value Type "string" Value "weaver"

3. Delete User
- Create new object repository "Delete User" Metod DELETE
- Input Url http://reqress.in/api/users/2
- Create Test case Delete User
- Add keyword Send Request
	- Object "Delete User"
	- Output "Response"
- Add Verify Element Proprty value
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "204"
	- Input param name "flowControl" Param type "FailureHandling" Value Type "Property" Value "STOP_ON_FAILURE"

4. Methode PUT
- Create new object repository "Methode PUT"
- Input Url http://reqress.in/api/users/2
- Create Test case Methode PUT
- Add keyword Send Request
	- Object "Methode PUT"
	- Output "Response"
- Add Verify Element Proprty value
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "200"
	- Input param name "flowControl" Param type "FailureHandling" Value Type "Property" Value "STOP_ON_FAILURE"
  
  5. Methode PATCH
- Create new object repository "Methode PATCH"
- Input Url http://reqress.in/api/users/2
- Create Test case Methode PATCH
- Add keyword Send Request
	- Object "Methode PATCH"
	- Output "Response"
- Add Verify Element Proprty value
	- Input param name "responseObject" Param type "ResponseObject" Value Type "Variable" Value "Response"
	- Input param name "expectedStatusCode" Param type "integer" Value Type "number" Value "200"
	- Input param name "flowControl" Param type "FailureHandling" Value Type "Property" Value "STOP_ON_FAILURE"


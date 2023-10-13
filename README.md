# testAPI
How to start:
<br>
```1. Save repository files```<br>
```2. Export to postman```<br>
```3. Done```

API testing with swagger at
https://send-request.me/
<p></p>
Below are examples of queries in Postman:

1. For ease of testing, JSON schemas are pre-written here.
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/1.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>
<h3>2. Here we see the end point check. I send a GET request with query parameters to get a list of companies.
Below is a visualization of the response body.</h3>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/3.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>3. The user has been successfully created here. The check passed because the response matches the JSON schema.</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/4.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>4. We change our Scrooge to Pascal using the PUT method.</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/5.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>5. Deleting a user. The response does not match the JSON schema.</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/6.png?raw=true
" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>6. An example of tests for checking single quotes.</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/8.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>7. Example of tests checking the length of the "company_id" value.</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/8.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>

<h3>8. Collection run report from Newman and allure .</h3>>
<img align="center" alt="Coding" src="https://github.com/sonyfrid/image/blob/main/8.png?raw=true" style="width: 100%; display: inline-block;" data-target="animated-image.originalImage"><br>





# Cristiano-Ronaldo

Some Statistics for the Futbol Player ' Cristiano Ronaldo' SINCE 2009 onwards.

these are the steps to get some analytics by players:

Using: 
Get URL from chrome 
Postman - to get the request code
Atom IDE to mimic the request from the website, and create the DB
Python Pandas - To analyze the data ad get some visuals
Python in Atom IDE - To analyze and get some visuals

1. Get database from www.whoscored.com.
I will get the DB from Cristiano Ronaldo by scraping the website
Link to webpage:
https://www.whoscored.com/Players/5583/Show/Cristiano-Ronaldo

2. Get the DB url from the website:
inspect -> Network -> XHR and 'copy as cURL (bash)' the Name that starts with 'GetPlayerstat...'

3. Get the python request code:
Enter to Postman (www.postman.com), download and create an account, then import:
Import -> raw text -> copy the cURL -> CodeSnippet -> Python-Requests
Copy the Python request

4.  Mimic the request in your IDE
Copy the python request in your IDE (I use Atom), and run to create the DB in CSV format
--> CHECK FILE: GetRequestCR7.py

5. Work the DB
Use Jupyter IDE and Pandas to create some visualization of the DB created.
--> CHECK FILE: CR7.ipynb

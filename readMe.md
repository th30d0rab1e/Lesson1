Source I used to follow Hello World Display: https://www.sitepoint.com/get-started-coldfusion/

Install CFMX localhost server: http://www.adobe.com/products/coldfusion-family.html

How to start and stop your server on a Mac: http://tv.adobe.com/watch/getting-ready-develop-coldfusion/starting-and-stopping-the-coldfusion-server-mac/

Installing ColdFusion has a complicated process, it isnt free but i used a 30 day trail and registered as a student.

1. to start the server go to this Terminal directory:
cd /Applications/ColdFusion2016/cfusion/bin  

2. ./coldfusion start

3. Create a folder in wwwRoot inside /Applications/ColdFusion2016/cfusion/wwwroot/ I called mine Lesson1

4. Create a file in the folder, i called mine index.CFM

5. To set a variable use <CFSET> tags. '<CFSET MyWorld = 'Hello World'>'

6. To display the variable or text use <CFOUTPUT> tags. '<CFOUTPUT>#MyWorld# the date is #DateFormat(Now(), 'MM/DD/YYYY')#.</CFOUTPUT>'

7. to view 'Hello World use this localhost address: http://127.0.0.1:8500/Lesson1/INDEX.CFM

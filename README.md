# Selenium-Framework
<html>
 <head>
 </head>
 <body>
  <p>-------------------------------------Run ----------------------------------------</p>
  <p>pytest -v -s --alluredir =  .\Tests\EndtoEndTest.py</p>
  <p>pytest .\EndtoEndTest.py</p>

  <p>-------------------------------Allure Report Run----------------------------</p>
  <p>Step : Open Cmd</p>
  <p>allure serve C:\Users\Lenovo\PycharmProjects\Calidad\=</p>

<p>-------------------------------------Jenkins ------------------------</p>
<p>Step 1: - Download File</p>
<p>https://www.jenkins.io/download/</p>
<p>0f67901625fe48c886fd4d39af0c4f0b</p>

<p>Step 2: - Open Cmd Run Command</p>
<p>java -jar C:\Users\Lenovo\Downloads\jenkins.war</p>

<p>Step 3: OPen Chrome</p>
<p>http://localhost:8080</p>
<p>Login</p>

<p>Step 4: Add Windows Batch Command</p>
<p>call ./venv/Scripts/activate.bat</p>
<p>pytest -v -s --alluredir=reports Tests/EndtoEndTest.py</p>

<p>-----------------------------------Make Xpath----------------------------</p>
<p>Step :- Use Text</p>
<p>//div//a//span[contains(text(),'Home')]</p>

<p>step :- Use Attributes</p>
<p>//div//a[@class='top']</p>
 
 </body>
 </html>


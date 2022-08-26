# Selenium-Framework
-------------------------------------Run ----------------------------------------
pytest -v -s --alluredir =  .\Tests\EndtoEndTest.py
pytest .\EndtoEndTest.py

 -------------------------------Allure Report Run----------------------------
 Step : Open Cmd
 allure serve C:\Users\Lenovo\PycharmProjects\Calidad\=

-------------------------------------Jenkins ------------------------
Step 1: - Download File
https://www.jenkins.io/download/
0f67901625fe48c886fd4d39af0c4f0b

Step 2: - Open Cmd Run Command
java -jar C:\Users\Lenovo\Downloads\jenkins.war

Step 3: OPen Chrome
http://localhost:8080
Login

Step 4: Add Windows Batch Command
call ./venv/Scripts/activate.bat
pytest -v -s --alluredir=reports Tests/EndtoEndTest.py

-----------------------------------Make Xpath----------------------------
Step :- Use Text
//div//a//span[contains(text(),'Home')]

step :- Use Attributes
//div//a[@class='top']


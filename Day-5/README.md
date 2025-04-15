Day 5:


Session 1: Virtual Environment, Git Workflow, and Selenium


1.	Virtual Environment


Explained about the need of using virtual environments in Python.


Demonstrated how to create and activate a virtual environment:


python -m venv myenv myenv\Scripts\activate # Windows




2.	Git Workflow


Discussed the essential Git commands: git init, git add, git commit and git push.


Discussed about Branching concepts and merging workflows

Demonstrated how to push a project into GitHub and how to manage the repositories.
 
3.	Selenium Automation with Python


Installed Selenium and Chrome WebDriver.


from selenium import webdriver

driver = webdriver.Chrome() driver.get("https://qxf2.com/selenium-tutorial-main") name = driver.find_element(by="id", value="name") name.send_keys("Qxf2")


Session 2: API Testing with Postman



1.	API Testing Using Postman Introduced API testing fundamentals.
Demonstrated sending GET and POST requests and validating responses


2.	API Testing with Python Requests Library

Explained API testing using Python’s requests module.



Conclusion


Today's session provided a hands-on introduction to automation and API testing. We covered setting up virtual environments, managing version control with Git, automating web interactions with Selenium, and testing APIs using Postman and Python’s requests library.

**For Operating System Lab**
- Project title is (Online Course)
- this is an old project for Django backend course. so it uses (MVT) Django for backend and sqllite for for database and native html/css for templates
- dependancies has been collected using pip freeze

***How to build using Docker***
- the project already has a Dockerfile,
- build an image using docker build -t operating-system-lab
- then you can run the project using docker run -p 8000:8000 from existing Dockerfile. 
- in the browser enter localhost:8000 
- exit the terminal or press Ctrl + C to stop django server. 


**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)


I built this Flask server as part of my Skills Network Lab exercise on deploying containerized applications. The goal was to understand how a simple Python web app can be packaged into a Docker image and deployed to a cloud platform.

What I Learned
Through this lab, I gained hands‑on experience with:

Structuring a Python Flask project for deployment

Writing a functional Dockerfile to containerize the app

Managing dependencies using requirements.txt

Testing the app locally before pushing it to IBM Code Engine

Understanding how Docker and Flask integrate in a cloud workflow

Project Structure
danum-pythonflaskserver/

app.py: Main Flask application

Dockerfile: Instructions for building the container image

requirements.txt: Python dependencies

README.md: Project documentation (this file)

LICENSE: License information

.gitignore: Files to exclude from version control

How I Deployed It

Built the Docker image locally using:
docker build -t danum-pythonflaskserver .

Pushed the image to IBM Cloud Container Registry

Deployed it on IBM Code Engine

Verified the live endpoint:
https://helloworld.29qb5sqpffd9.us-south.codeengine.appdomain.cloud

Reflection
This project helped me connect theory to practice — moving from writing Python code to deploying a real, cloud‑hosted service. It strengthened my understanding of containerization, cloud automation, and DevOps fundamentals.

Portfolio Links


Live Deployment: https://helloworld.29qb5sqpffd9.us-south.codeengine.appdomain.cloud

I’m proud of this lab because it demonstrates my ability to design, containerize, and deploy a Python Flask application in a professional cloud environment.

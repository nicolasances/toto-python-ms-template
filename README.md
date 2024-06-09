# Template for Toto Python Microservices

This is a template project that will allow you to create, build and deploy a Toto Microservice. <br>
It supports two types of Runtime Environments: 
* AWS on ECS
* GCP on Cloud Run

This documentation will guide you through the process of using this template to create, build and deploy your new Toto Microservice.

## 1. Clone this Repo and Detach
The first thing to do is to clone this repo. <br>
You should change the name of the target folder with the following command: 
```
git clone https://github.com/nicolasances/toto-python-ms-template toto-ms-<your-ms-name>
```

After cloning, you need to detach from the template repo. You can do this by using the following command: 
```
git remote rm origin
```

## 2. Create the Microservice
Use Toto API Controller to create your microservice skeleton. <br>
Follow the instructions in this repo: https://github.com/nicolasances/py-toto-api-controller.

Remember, before doing anything, to **create a Python Virtual Environment**!
```
python3 -m venv .venv 
source .venv/bin/activate.
```
Always run `which python` to make sure you're now using the version of python in the venv.

## 3. Deploy the Microservice
* [Guide to Deploy on AWS ECS](./docs/aws/aws-ecs-guide.md)
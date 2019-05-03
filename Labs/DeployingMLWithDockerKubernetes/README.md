![GitHub Logo](https://github.com/SQLShark/MachineLearningFromModelToProduction/blob/master/Images/Header1.png)

# Machine Learning: From model to production using the cloud, Containers and DevOps
Hello and welcome to this full day workshop on deploying machine learning models in Azure. You could use any cloud provider for what we are looking. There is lots in this course that is directly transferable to AWS or Google. You can also run this on-premises, however that misses a lot of what we are trying to create with the cloud. 

# DevOps for Machine learning blog series
I have been writing an ongoing blog series about the content in this blog. I will add more to it based on the content in this session. You can find it all here: 
- [Terry McCann - DevOps for Data Science](https://www.advancinganalytics.co.uk/dataops-deploying-models-faster)

# Today's Abstract
Pick up a book on Machine learning and it will explain the process for machine learning, many citing CRISP-DM as the ideal process. CRISP-DM is an iterative approach to Data Mining. It starts with business understanding the flows to data understanding, data preparation, modelling, evaluation, then either loops back around or is deployed.

How it is deployed, well no one ever tells you that! Well, I want to talk about it!

In this full-day session we will build a series of basic models and promote them into production. This will be an interactive session, make sure you have your laptop with you. As we go through the day we will talk about the following:

Developing a Machine Learning Engineering environment
Develop multiple basic machine learning models
Deploy multiple basic machine learning models
Develop an architecture capable of supporting and deploying any machine learning language
Sounds awesome right? My intention is to show you a method for deploying machine learning models.

We will do this by looking at the following tech stack:

- Microsoft Azure – A Cloud environment to deploy to. (All the tech we are using will work on a platform of your choice)
- Python – To build our models
- Docker – A container to run our models
- Kubernetes – A Container runtime environment to handle the load balancing of our models.
- Azure Service Bus – A stream service for our models
- PowerBI – A reporting tool to visualise the usage of our models.
- We will use a composition of other languages as we go. 

All the scripts we will use will be available to GitHub for you to follow along.

At the end of the day we will have built a simple model and deployed it. You will take away a tried and tested architecture for deploying a model in to production. I will demo a method for deploying changes to your model using DevOps.

## Labs
This session is designed to be a hands on workshop. You will get a mixture of Theory and real world solutions.
To back this up we have a series of labs. 
- Lab 1 - Creating a Python Model
- Lab 2 - The basics of serialisation in Python
- Lab 3 - Adding Flask to our model to expose an API
- Lab 4 - Hello World! in Docker
- Lab 5 - Deploying a web app in to Docker
- Lab 6 - Deploying our model in to Docker
- Lab 7 - Deploying Azure Container Reg
- Lab 8 - Deploying our model in Kubernetes
 
## Tools required for today
These labs require tools most Azure developers have on their development machines. They do need to be the latest edition for some of the new features to work. 

As a minimum delegates should have:  
- A laptop.
- An Azure subscription with available credit. https://azure.microsoft.com/en-gb/offers/ms-azr-0044p/
- A modern internet browser.
 
For delegates to get the most out of the day and get involved in advanced areas, we also recommend having the following tools installed:
1.  Docker for your OS - https://www.docker.com/
2.	Python (Anaconda preferred) - https://www.anaconda.com/download/
3.	Azure CLI - https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest
4.	Kubectl - https://docs.microsoft.com/en-us/cli/azure/aks/kubernetes?view=azure-cli-latest

That should be enough to follow along with all the demos or to take the labs home to do in your own time. 
 
## About the speakers
There are business cards for all speakers on the desk at the front. 

### Terry McCann | Principal Consultant - Advancing Analytics [Data Platform MVP]
Microsoft MVP. Principal Consultant and Owner of Advancing Analytics Limited, an Advanced Analytics consultancy in the UK. Advancing Analytics helps businesses advance their analytical capabilities. Our focus is on Data Science, Data Engineering, DataOps and applied AI. Terry holds a Master's degree in Data Science - with a focus on DataOps for Machine Learning. Organiser of the Data Science Exeter user group, frequent speaker at conferences across the world and the host of the Data Science in Production Podcast. 

You can contact Terry here: terry@advancinganalytics.co.uk or via [@SQLShark](https://twitter.com/SQLShark) on Twitter

## Links mentioned during the talk. 

As we talk about interesting links and examples we will collect these here for future reference. 

- [Azure Model Management](https://azuremarketplace.microsoft.com/fi/marketplace/apps/Microsoft.MachineLearningModelManagement?tab=Overview) - Now marked for retirement  

- [API First development](http://engineering.pivotal.io/post/api-first-for-data-science/)

- [Scalable REST API with Deep Learning](https://medium.com/idealo-tech-blog/falcon-vs-flask-which-one-to-pick-to-create-a-scalable-deep-learning-rest-api-adef647ebdec)
- http://clipper.ai

- http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf

- https://ai.google/research/pubs/pub43146

- [Modern Data Engineering](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a)

- [Cookiecutter project](https://github.com/manifoldai/docker-cookiecutter-data-science/blob/master/README.md)

- [Birdging that gap from Data Science to Production](https://www.inovex.de/de/content-pool/vortraege/bridging-the-gap-from-data-science-to-production/)


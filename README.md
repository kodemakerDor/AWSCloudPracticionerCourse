# AWSCloudPracticionerCourse

This Repository will have all the notes and pertinent code in order to fully understand and achieve the AWS Certified Cloud Practitioner Basics.
This repository was originally developed by [Fabián Camp](https://fabshub.net). It is highly recomended to have your personal account in AWS in 
order to fully understand the course and to take the course directly from AWS training.

## Table of Contents

1. [ Module 1: Introduction to Amazon Web Services ](#module-1)
    1. [ Client-server model ](#client-server-model)
    2. [ Cloud computing ](#cloud-computing)
        1. [ Deployment models for cloud computing ](#cloud-computing-models)
            1. [ Cloud based deployment ](#cloud-based)
            2. [ On-premises deployment ](#on-premises)
            3. [ Hybrid deployment ](#hybrid)
        2. [ Benefits of cloud computing ](#cloud-computing-benefits)
2. [ Module 2: Compute in the Cloud ](#module-2)

<a name="module-1"></a>

## Module 1: Introduction to Amazon Web Services

<a name="client-server-model"></a>

### 1. Client-server model

A **client** can be a web browser or desktop application that a person interacts with to make requests to computer servers. In the other hand,
a **server** can be services such as Amazon Elastic Compute Cloud (Amazon EC2) that is a type of virtual server.

An example of this is the following, you make a request for a particular photo that you are interested in then, the server will
evaluate the details of that request, if that evaluation fulfills the server needs then it will return the photo you ask for.

![ Client Server Model ](Images/ClientServer.png)

<a name="cloud-computing"></a>

### 2. Cloud computing

When we talk about cloud computing first it is important to understand what is cloud computing for AWS, this is:

> **Cloud computing** is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.

**On-demand delivery** on AWS indicates that AWS has the resources you need, when you need them. If you suddenly need 300 virtual servers
only a few click and you got them, this also applies for storage. You don't need to tell AWS in advance that you're going to need that resources.

This kind of flexibility is just not possible when you're managing your own data centers.

Another important definition to have in mind is what AWS call the **undifferentiated heavy lifting of IT**. This is, tasks that are common,
often repetitive and ultimately time-consuming; these are the tasks AWS wants to help you with. So you can focus on what makes you unique.

Finally, with **pay-as-you-go pricing**, AWS points out an example of a coffee shop. You don't staff a shop with employees 24
hours a day at the same levels you do during peak hours. In fact, some hours, you might not even staff them at all.

<a name="cloud-computing-models"></a>

#### Deployment models for cloud computing

When selecting a cloud strategy, a company must consider factors such as required cloud application components, preferred resource management
tools, and any legacy IT infrastructure requirements.

There are three cloud computing deployment models are cloud-based, on-premises, and hybrid.

<a name="cloud-based"></a>

##### Cloud-based deployment

- Run all parts of the application in the cloud.
- Migrate existing applications to the cloud.
- Design and build new applications in the cloud.

In this model you can migrate existing applications to the cloud, or you can design and build them in the cloud. You can build those
applications on low-level infrastructure or on a high-level services that reduce the management, architecting, and scaling requirements of
the core infrastructure.

In other words, you don't need to think in your infrastructure because all the deployment is completely in the cloud.

<a name="on-premises"></a>

##### On-premises deployment (Private Cloud)

- Deploy resources by using virtualization and resource management tools.
- Increase resource utilization by using application management and virtualization and resource management tools.

It is also known as _private cloud_ deployment. In this model, resources are deployment on premises by using virtualization
and resource management tools.

This model its usefull when you have an infrastructure that is located on your data center. AWS has tools that allows you to deploy cloud services
on your infrastructure, this is called on-premise.

<a name="hybrid"></a>

##### Hybrid deployment

- Connect cloud-based resources to on-premises infrastructure.
- Integrate cloud-based resources with legacy IT applications.

In Hybrid deployment, cloud-based resources are connected to on-premises infrastructure. You might want to use this approach in a number of situations.
For example, you have legacy applications that are better maintained on premises, or government regulations require your business to keep certain
records on premises.

In other words, this kind of deployment is used when you have strict regulations (like government stuff). So an example of this let's say we have the
Red Hat servers on-premise (in our infrastructure) but we are using DynamoDB (AWS cloud service for database) we can connect our infrastructure with
DynamoDB. This example is what AWS call Hybrid deployment.

<a name="cloud-computing-benefits"></a>

#### Benefits of cloud computing

Some of the benefits we can find when we talk about cloud computing are the following ones:

Benefit | Description
------- | -----------
Trade upfront expense for variable expense | **Upfront expense** refers to data centers, physical servers, and other resources that you would need to invest **variable expense** refers to the cloud computing approach, implement innovative solutions while saving on costs.
Stop spending money to run and mantain data centers | A benefit of the cloud computing is the ability to focus less on these tasks and more on your applications and customers.
Stop guessing capacity | With cloud computing, you don’t have to predict how much infrastructure capacity you will need before deploying an application.
Benefit from massive economies of scale | By using cloud computing, you can achieve a lower variable cost than you can get on your own.
Increase speed and agility | The flexibility of cloud computing makes it easier for you to develop and deploy applications.
Go global in minutes | AWS Cloud enables you to deploy applications to customers around the world quickly, while providing them with low latency.

<a name="module-2"></a>

## Module 2: Compute in the cloud


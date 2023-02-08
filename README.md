# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Gila Kohanbash
- Karla Vasquez

## Lab Question Answers


*Question 1: Why are RESTful APIs scalable?*

RESTful APIs are scalable because they allow for a speration between the client and the server. The whole idea of RESTful APIs is to make data migration from one server to another easier. The interactions between the client and server are optimimized by Representational State Transfer (REST) which has several unique attributes, specifically being statelessness. Statelessness removes server load since the server does not have to worry or keep any information from previous client requests.


*Question 2: According to the definition of “resources” provided in the AWS article above, What are the resources the mail server is providing to clients?*

The article defines resources as "the information that different applications provide to their clients." Examples of this would include any type of data such as images, video and texts. The resources the mail server provides the clients with is a list of all the mail entries, inbox of the sender and recipient of each mail and whether a mail has been deleted. 


*Question 3: What is one common REST Method not used in our mail server? How could we extend our mail server to use this method?*

We did not include the PUT method in our server. This method allows clients to update an existing resource (like an already sent email) on the server. We can extend our mail server to use this method in order to change the location of one mail to another (for example from inbox to unread).


*Question 4: Why are API keys used for many RESTful APIs? What purpose do they serve? Make sure to cite any online resources you use to answer this question!*

With API keys, the server assigns a uniqe generated value token to a first-time client. After that, whenever the same client tries to access any resouces, the API key will need to verify itself for authentification. This is useful because it allows you to charge for your service (only give the client the key to do certain operations).

Online resource - AWS Link on Lab 3: https://aws.amazon.com/what-is/restful-api/









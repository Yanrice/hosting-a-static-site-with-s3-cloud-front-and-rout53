# Host a secure static school information website

![](Images/aws%20project%202.jpeg)


### Team Members: 
* Yannick Kalukuta	[yanowen](https://github.com/Yanrice)

## Project Objective: 
A client needs you to host his school website (meaning the information is hard coded) 
He has added the following requirements to his document.
* It has to be accessible with a domain name
* He needs it to be available globally
* He needs the website to load fast
* He wants a cost effective but efficient solution
* He also needs the website to be secured with https

## Tips
Here are some tips to help you out with the project
You’ll create an **Amazon S3 bucket** to hold your static website files and an **Amazon CloudFront** distribution to serve your website globally. **Amazon Route 53** will manage your domain name, and **AWS Certificate Manager** will provide a valid **SSL/TLS** certificate.
Services to be used

* Amazon S3
* Amazon CloudFront
* amazon Route 53
* AWS Certificate Manager 

## Prerequisites 
You’ll need a few things to get started with this project:
Static school website made up of `HTML`, `CSS`, `JavaScript`, etc.
files You can download the code from here:
https://github.com/tatahnoellimnyuy/schoolstatic/archive/refs/heads/main.zip
You will also need to create an account on freenom to register your free domain name
Other materials
here is the link to the website: https://school-website.ga/
here is the link to the documentation:
 https://docs.google.com/presentation/d/1e2NmUCauuiA1Ez70D67fLWWXeBs69AAiRKUW2GhGf9I/edit?usp=sharing
 
 ## How to proceed
* Create S3 bucket
* Upload web files to S3 bucket
* Secure S3 bucket through IAM policies
* Serve content from S3 bucket with CloudFront
* Create domain name on freenom
* Link domain name to Route53
* Direct traffic from route53 to cloudfront and set security (`https`)

Here is a powerpoint with step-by-step direction: 
https://docs.google.com/presentation/d/1e2NmUCauuiA1Ez70D67fLWWXeBs69AAiRKUW2GhGf9I/edit#slide=id.gb61e145030_0_5

 

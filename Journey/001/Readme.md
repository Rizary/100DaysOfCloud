<!-- This template removes the micro tutorial for a quicker post and removes images for a full template check out the 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

![placeholder image](day1.jpg)

# New Year on a New Journey With DynamoDB (1/100)

## Introduction

I want to create a personal website by following [cloud resume challenge](https://cloudresumechallenge.dev/instructions/) instructions, which one of the instructions used DynamoDB. I have already build a static website, but when I look into the challenge, I think it will be good if I can make a personal website (following the instructions) using WebAssembly.

## Use Case

- According to the challenge, we have to create a visitor counter database that can be called in the website. DynamoDB comes as suggestion in this regard.
- I have to provisioned DynamoDB table using Infrastructure as Code with AWS Serverless Application Model (SAM) and deploy it using SAM CLI.

## Cloud Research

I could not researched or doing trial and errors because I have family matters today. However, I have put some note while I am studying DynamoDB using Amazon DynamoDB Deep Dive course with Mark Richman, as follows:

- The feature of NoSQL - in this case DynamoDB - are: 1) optimized for compute; 2) instantiated views; 3) scale horizontally; and 4) uild for OLTP at scale

- There are four NoSQL Engine types, such as key-value, document-oriented, column-oriented, and graph. DynamoDB uses key-value and document oriented.

- DDB has 2 performance model, on-demand and provisioned capacity. On-demand more pricey because it can scales infinitely (with 40,000 RCU and WCU max). Provisioned cheaper but can cause throttle lock.

## Social Proof

[Twitter](https://twitter.com/Rizary_Andika/status/1345049353015099394)

[LinkedIn](https://www.linkedin.com/posts/andika-riyandi_rizary100daysofcloud-activity-6750815208043900928-MqWJ)

[Blog](https://dev.to/rizary/day-1-100-new-year-on-a-new-journey-with-dynamodb-1no4)

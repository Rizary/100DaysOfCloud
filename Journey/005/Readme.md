<!-- This template removes the micro tutorial for a quicker post and removes images for a full template check out the 000-DAY-ARTICLE-LONG-TEMPLATE.MD-->

**Add a cover photo like:**
![day5](day5.jpg)

# Identity and Access Management (IAM) - Part II

## Introduction

I want to continue studying IAM because I think this is important for the AWS exam. Moreover, last time I study, I have not covered topic like Active Directory, IAM Policies, and ARN.

## Use Case

User wants to connect to AWS with on-premise Active Directory or other third party account. In addition, there is possibility to resource sharing between account.

## Cloud Research

- ARN begin with: `arn:partition:service:region:account_id`
- Using AWS Active Directory, user can connect into AWS resources with on-premises Microsoft Active Directory
- Active Directory trust is used to extend existing AD inside AWS into on-premise
- Simple Active Directory doesn't support trusts. You can connect it using AD Connector.
- To have resource sharing between accounts, we can use RAM - Resource Access Manager
- Cognito user pools is managed user directory for SaaS applications.

## Social Proof

[Twitter](https://twitter.com/Rizary_Andika/status/1346722523623243778)
[LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6750340365867454464?commentUrn=urn%3Ali%3Acomment%3A%28activity%3A6750340365867454464%2C6752488504883843072%29)

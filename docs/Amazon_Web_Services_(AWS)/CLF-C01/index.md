# Introduction

This section contains notes created following the [Fundamental Cloud Concepts for AWS Pluralsight Course](https://app.pluralsight.com/library/courses/fundamental-cloud-concepts-aws/table-of-contents).

Although I don't intend to take the AWS Certified Cloud Practitioner exam, I think it'd be useful to study the content ahead of the SAA content, so that I have the basics of AWS covered.

## Understanding Cloud Computing

Traditional Data Centres have disadvantages that Cloud architecture can address, such as:

- Large Upfront Cost. You either have to build or share a data centre.
- Forecasting demand for the DC is tricky.
- There is intertia in deploying new data centres and servers. It takes time!
- Maintaining the data centre is included in the TCO of the service.
- You own all the security and compliance burden.

Cloud computing overs several ways of countering such issues:

- You trade capital expense for variable expense (PAYG).
- You benefit from the economies of scale.
- You don't need to guess capacity, and you can easily scale.
- You have increased speed of delivery, and therefore agility.
- You don't have to maintain the DC.
- You can 'Go global in minutes'

## Key Terms

Cloud Computing is on-demand delivery of compute power, database storage, applications, and other IT resources through a cloud service platform via the internet, with pay-as-you-go pricing.

*Elasticity* - Aquire resources when you need them and release them when you no longer require them.

*Reliability* - Consistently provide functionality to users when it's needed

*Agility* - Provides opportunities for the business to try new ideas and business processes with minimal outlay.

## Cloud Models

```
IaaS <------------------PaaS---------------------> SaaS
Max Control                             Minimum Control
```

### Public Cloud
Deployed onto something like AWS. Someone else's servers.

### On-Prem Private Cloud
Cloud-like platform in a private data centre that you own.

### Hybrid
Public Cloud applications connected to a private DC.

# Cloud Economics

Cloud infrastructure allows businesses to manage their expenditure outlays in different ways to how building a traditional data centre would require.

* **Capitalised Expenditure (CapEx)**: The upfront costs for building a service.

* **Operating Expenditure (OpEx)**: Day-to-day, ongoing costs of running a service.

### On Premises vs Cloud

When building out a data centre, you'd have a large Capitalised Expenditure just to get started. This would then be followed by a regular Operational Expenditure to run the infrastructure. Over time, you may want to increase capacity of your infrastructure. In doing so, you'd have another large capitalised expenditure outlay, and likely a higher regular operational expenditure.

With Cloud, you have next to no Capitalised Expenditure, and instead you have an Operational Expenditure that grows with your demand.

## AWS Cost Explorer

AWS Cost Explorer is a User Interface for exploring AWS Costs. You can see breakdowns:

* By Service
* By Cost Tag

It also provides predictions for the next three motnhs, and gives recommendations for cost optimisation. This data is available via an API so can be accessed programatically.

## AWS Budgets

AWS Budgets uses data from AWS Cost Explorer to plan and track usage across services. It can track cost per service, service utilisation, reserved instance util. and coverage, and Savings Plans utilisation and coverage.

## Planning Costs

AWS offers several tools for planning and understanding costs associated with using its cloud infrastructure.

### Pricing Calculator

Allows a user to get in-depth analysis of the costs of using multiple AWS services for cloud-based workloads. You can use it to compare infrastructure designs and find the most cost-effective.

### Migration Hub

Provides recommendations and a business case for transitioning workloads to the cloud.

### Resource Tags

Resource tags are metadata assigned to specific AWS resources. You could use them to group resources by departments, environments, or projects. You can then use these tags to see costs at a tag-level.

Tags can be used within AWS Cost Explorer.

### AWS Organisations

Allows organisations to manage multiple AWS acounts under a single master account.

AWS Organisations also allows you to make use of Consolidated Billing.

You can also benefit from centralised logging and auditing.




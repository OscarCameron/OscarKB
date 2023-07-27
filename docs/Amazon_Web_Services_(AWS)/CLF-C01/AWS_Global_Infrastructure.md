# AWS Global Infrastructure

## Regions and Availability Zones

Each region is in a specific geographic location :earth_americas:.

An Availability Zone consists of one or more data centres (for redundancy). Multiple Availability Zones make up one AWS Region. Each AZ has redundant power, networking, and connectivity.

![Availability Zones vs Regions](https://cdn.ttgtmedia.com/rms/onlineimages/aws_availability_zones_vs_regions-f_mobile.png)

Regions and Availability Zones are named in the following pattern: `Area-Subarea-Number AZ`.
Us-east-2 is therefore a *Region* name.
Us-east-2a is an *Availability Zone* name.

## Local and Wavelength Zones

Local Zones are extensions of AWS Regions. They place compute, storage, database, and other services closer to end-users to reduce latency.

Similarly, Wavelength Zones are AWS Infrastructure Deployments that embed AWS compute and storage services within the 5G network, so traffic from 5G devices reaches app servers running in Wavelength Zones without having to leave the 5G network.

## AWS Edge Locations

AWS Edge Locations, unlike Local Zones, exist outside of AWS Regions. They are located in or near populated areas, and specific AWS services use them to deliver content to end users as quickly as possible. Regional Edge Caches also achieve the same thing.

Edge Locations form a CDN (Content Delivery Network), used by CloudFront and Route 53.
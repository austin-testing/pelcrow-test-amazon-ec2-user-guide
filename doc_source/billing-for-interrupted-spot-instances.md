---
title: "Billing for interrupted Spot Instances"
owner: "Austin Rappa"
type: "concept"
journeyStage: "Plan"
useCases: ["Cost Planning","Architecture Design"]
audience: ["Finance/Operations"]
platform: ["EC2"]
---

# Billing for interrupted Spot Instances<a name="billing-for-interrupted-spot-instances"></a>

When a Spot Instance is interrupted, you’re charged for instance and EBS volume usage as follows\.

## Instance usage<a name="billing-for-interrupted-spot-instances-instance-usage"></a>

[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/billing-for-interrupted-spot-instances.html)

## EBS volume usage<a name="billing-for-interrupted-spot-instances-ebs-usage"></a>

While an interrupted Spot Instance is stopped, you are charged only for the EBS volumes, which are preserved\.

With EC2 Fleet and Spot Fleet, if you have many stopped instances, you can exceed the limit on the number of EBS volumes for your account\. 
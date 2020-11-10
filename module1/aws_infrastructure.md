# AWS Infrastructure Notes


The AWS Cloud infrastructure is built around Regions and Availability Zones. AWS Regions provide multiple, physically separated, and isolated Availability Zones that are connected with low latency, high throughput, and highly redundant networking.

As of the time of publication, the AWS Cloud spans 55 Availability Zones within 18 geographic Regions and 1 Local Region around the world. There are announced plans for 15 more Availability Zones and five more Regions in Bahrain, Hong Kong SAR, Sweden, and South Africa; and a second AWS GovCloud Region in the US.

There is a Local Region in Osaka, Japan (**Osaka-Local**). An AWS Local Region is a single data center that is designed to complement an existing AWS Region. It is available to select AWS customers who request access. Customers who want to use the Asia Pacific (Osaka) Local Region should speak with their sales representative. Like all AWS Regions, AWS Local Regions are completely isolated from other AWS Regions.

[Click here](https://aws.amazon.com/about-aws/global-infrastructure/) for the most current information.

Each AWS Region has multiple, isolated locations that are known as Availability Zones. Amazon Relational Database Service (Amazon RDS) provides you with the ability to place resources (such as instances) and data in multiple locations. Resources aren't replicated across AWS Regions unless you do so specifically.

Detailed information about Availability Zones can be found [here](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html).


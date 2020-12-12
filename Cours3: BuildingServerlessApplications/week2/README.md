## Week 2 Readings/Resources

------

### **Amazon API Gateway**

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. With a few clicks in the AWS Management Console, you can create an API that acts as a “front door” for applications to access data, business logic, or functionality from your back-end services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, or any web application. 

### **Mock Integrations in API Gateway**

Amazon API Gateway supports mock integrations for API methods. This feature enables API developers to generate API responses from API Gateway directly, without the need for an integration backend. As an API developer, you can use this feature to unblock dependent teams that need to work with an API before the project development is complete. You can also use this feature to provision a landing page for your API, which can provide an overview of and navigation to your API. For an example of such a landing page, see the integration request and response of the GET method on the root resource of the example API discussed in [Build an API Gateway API from an Example](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-create-api-from-example.html).

### **Pricing**

With Amazon API Gateway, you only pay when your APIs are in use. There are no minimum fees or upfront commitments. For HTTP/REST APIs, you pay only for the API calls you receive and the amount of data transferred out. Amazon API Gateway is [Free Tier](https://aws.amazon.com/free/) eligable and The Amazon API Gateway free tier includes one million API calls received for HTTP/REST APIs, and one million messages and 750,000 connection minutes for WebSocket APIs per month for up to 12 months.  See the [Amazon API Gateway](https://aws.amazon.com/api-gateway/pricing/) pricing page for details.  **Amazon CloudFront**

[Amazon CloudFront](https://aws.amazon.com/cloudfront/) is is a global content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to your viewers with low latency and high transfer speeds. CloudFront is integrated with AWS – including physical locations that are directly connected to the AWS global infrastructure, as well as software that works seamlessly with services including [AWS Shield](https://aws.amazon.com/shield/) for DDoS mitigation, [Amazon S3](https://aws.amazon.com/s3/), [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) or Amazon [EC2](https://aws.amazon.com/ec2) as origins for your applications, and [Lambda@Edge](https://aws.amazon.com/lambda/edge/) to run custom code close to your viewers.  [The cost to use CloudFront](https://aws.amazon.com/cloudfront/pricing/) is based upon data transfer costs as well as requests and includes a free usage tier.

**Cloudfront Edge Locations as of March 2019**:To deliver content to end users with lower latency, Amazon CloudFront, uses a global network of  166 Points of Presence (155 Edge Locations and 11 Regional Edge Caches) in 65 cities across 29 countries. For current information about Edge Locations, [see this page](https://aws.amazon.com/cloudfront/features/).

### **Origin Access Identity (OAI)**

[Origin Access Identity](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html) provides a method to restrict access to S3 content to only a CloudFront Distribution.

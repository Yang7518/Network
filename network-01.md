## AWS OpsWorks 
- AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet.
- OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed, and managed across your Amazon EC2 instances or on-premises compute environments.

## AWS CLI
- The dry-run flag checks whether you have the required permissions for the action, without actually making the request, and provides an error response. If you have the required permissions, the error response is DryRun-Operation. Otherwise, it is UnauthorizedOperation. 

## AWS CloudFormation
- The intrinsic function Fn::Cidr returns an array of CIDR address blocks.
  - The number of CIDR blocks returned is dependent on the count parameter. 
  - The syntax is like so - !Cidr [ ipBlock, count, cidrBits ].
  - For example, the YAML code !Cidr [ "192.168.0.0/24", 6, 5 ] creates 6 CIDRs with a subnet mask "/27" inside from a CIDR with a mask of "/24". 

## AWS Global Accelerator
- AWS Global Accelerator is a networking service that helps you improve the availability and performance of the applications that you offer to your global users. 
- It provides static IP addresses that provide a fixed entry point to your applications and eliminate the complexity of managing specific IP addresses for different AWS Regions and Availability Zones.
- As your application architecture grows, so does the complexity, with longer user-facing IP lists and more nuanced traffic routing logic. AWS Global Accelerator solves for this by providing you with two static IPs that are anycast from our globally distributed edge locations, giving you a single entry point to your application, regardless of how many AWS Regions it’s deployed in.
![](./network-01/AWS%20Global%20Accelerator%2001.PNG)
- For a gaming use case, AWS Global Accelerator enhances your end users' online experience by routing user traffic via the private AWS global network, reducing in-game latency, jitter, and packet loss.
![](./network-01/AWS%20Global%20Accelerator%2002.PNG)

## CloudFront

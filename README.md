## STATIC WEBSITE HOSTING USING CLOUDFRONT

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing

**Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations. When a user requests content that you're serving with CloudFront, the user is routed to the edge location that provides the lowest latency (time delay), so that content is delivered with the best possible performance.

**If the content is already in the edge location with the lowest latency, CloudFront delivers it immediately.

**If the content is not in that edge location, CloudFront retrieves it from an origin that you've defined—such as an Amazon S3 bucket, a MediaPackage channel, or an HTTP server (for example, a web server) that you have identified as the source for the definitive version of your content.

## Prerequisite
 - AWS Account
 
 
## STEPS
  - create a S3 bucket
  - configure the bucket for website hosting
  - and secure it using IAM policies
  - upload the website files to your bucket 
  - speed up content delivery using AWS’s content distribution network service, CloudFront
      -Specify origin servers, like an Amazon S3 bucket or your own HTTP server, from which CloudFront gets your files which will then be distributed from CloudFront edge locations all over the world.
  - access your website in a browser using CFN endpoint URL
  
  
## REFERENCE DOCUMENTATION :
* [Use Cases](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/IntroductionUseCases.html)
* [CloudFront AWS Docs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)


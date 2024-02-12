# Regional Services
AWS scopes their AWS Managment COnsole on a selected Region. This will determine where an AWS service will be launched nad what will be seen within an AWS Service's console. You genrrally don't explicitly set the Region for a server at the time of creation

# Global Services
Some AWS Services operate across multiple regions and the region will be fixed to "Global" E.g Amazon S3, CloudFront, Route 53, IAM

For global services at the time of creation
- There is no concept of region (eg IAM user)
- A single region must be explicitly chosen (S3 Bucket)
- A group of regions are chosen (CloudFront Distribution)

#global-infrastructure 
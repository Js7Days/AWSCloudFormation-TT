# Web Server EC2 Instance Deployment
## Description: 
This package contains a CloudFormation template (CFormationTemp-0-Network.yaml, CFormationTemp-1-Security.yaml and CFormationTemp-2-EC2.yaml ) to deploy a web server EC2 instance on AWS. The template provisions an EC2 instance with Apache web server pre-installed, configured, and serving a basic webpage.

## How to Run the Containerized Application
### Prerequisites
* AWS CLI installed and configured with appropriate IAM permissions.
* Docker installed (optional, for running locally).

### Steps to Deploy the Web Server EC2 Instance
1. Clone this repository to your local machine:
git clone https://github.com/Js7Days/AWSCloudFormation-TT.git
2. Navigate to the repository directory:
cd AWSCloudFormation-TT
3. Open YAML Sript:
  * CFormationTemp-0-Network.yaml
  * CFormationTemp-1-Security.yaml 
  * CFormationTemp-2-EC2.yaml
4. Deploy the CloudFormation stack using the CloudFormation console:
   https://console.aws.amazon.com/cloudformation/ 
5. Click on "Create Stack" -> Choose "Upload a template file" and select the template file.
6. Specify your stack name and parameters.
7. Configure stack options tags, permissions stack 
8. Review and Create -> Next -> Click Submit

## About me
Name: Thong Thao
Student ID: 
TAFE Student

# Web Server EC2 Instance Deployment
## Description: 
This package contains a CloudFormation template (CFormationTemp-0-Network.yaml, CFormationTemp-1-Security.yaml and CFormationTemp-2-EC2.yaml ) to deploy a web server EC2 instance on AWS.

## How to Run the Containerized Application
### Prerequisites
* AWS CLI installed and configured with appropriate IAM permissions.
* Docker installed (optional, for running locally).

### Steps to Download the YML Sript.
1. Clone this repository to your local machine:
wget or git clone https://github.com/Js7Days/AWSCloudFormation-TT.git
2. Navigate to the repository directory:
cd AWSCloudFormation-TT
3. There are 3 YAML Sript:
  * CFormationTemp-0-Network.yaml
  * CFormationTemp-1-Security.yaml 
  * CFormationTemp-2-EC2.yaml
  #### For Microsoft Windows
Copy and paste this link to browser:  https://github.com/Js7Days/AWSCloudFormation-TT/archive/refs/heads/main.zip
### Steps to Deploy on CloudFormation console.
1. Deploy the CloudFormation stack using the CloudFormation console:
   https://console.aws.amazon.com/cloudformation/ 
2. Click on "Create Stack" -> Choose "Upload a template file" and select the template file.
3. Specify your stack name and parameters.
4. Configure stack options tags, permissions stack 
5. Review and Create -> Next -> Click Submit

## About me
Name: Thong Thao <br>
Student ID:  <br>
TAFE Student

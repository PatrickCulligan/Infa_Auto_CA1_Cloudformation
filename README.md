"# Infa_Auto_CA1_Cloudformation" 

1. Download security credentials, the key pair named abuser in .ppk format and PuTTY through the AWS Details.

2. Download and unzip the Git repository.
   
       https://github.com/PatrickCulligan/Infa_Auto_CA1_Cloudformation.git

3. Create an EC2 instance through CloudFormation on the AWS console. Import the below yaml file

      Prod_CloudFormation/Prod_CloudFomation.yaml
   
4. SSH access rule already added to default security group.

6. Connect to the EC2 instance through PuTTY.

7.  Confirm AWS, Ansible and Terraform CLI access.
   
   ansible --version && terraform --version
   
8. Proceed to terraform read

    Infa_Auto_CA1_Terraform

9. Each must be complete for each environment Test, QA, Prod.

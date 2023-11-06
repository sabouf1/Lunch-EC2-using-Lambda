# AWS Terraform Lambda Project

This repository contains the Terraform configuration files used to set up an AWS Lambda function that provisions an EC2 instance upon triggering. The setup process includes tasks like signing in to the AWS Management Console, configuring Visual Studio Code, creating variable files, and applying Terraform configurations.

## Prerequisites

- AWS Account
- Visual Studio Code installed
- Terraform installed

## Getting Started

1. **Sign in to AWS Management Console**
   - Use the provided credentials in the Lab Console to sign in.
   - Set the default AWS Region as US East (N. Virginia) us-east-1.

2. **Setup Visual Studio Code**
   - Open Visual Studio Code and navigate to the Desktop to create a new folder for the project.

3. **Create a variable file**
   - Declare global variables in `variables.tf` and set default values in `terraform.tfvars`.

4. **Create a Lambda Function**
   - Define the AWS provider and Lambda resource in `main.tf`.

5. **Create an Output file**
   - Extract the ARN of the Lambda function in `output.tf`.

6. **Confirm Terraform Installation**
   - Verify that Terraform is installed by checking its version in the terminal.

7. **Apply Terraform Configurations**
   - Initialize Terraform and apply the configurations to create the AWS resources.

8. **Check Resources in AWS Console**
   - Verify the creation of the Lambda function in the AWS Console.

9. **Test the Lambda Function**
   - Test the Lambda function and confirm the provisioning of the EC2 instance.

10. **Check EC2 Instance Creation**
    - Verify the EC2 instance is running in the AWS Console.

11. **Validation Test**
    - Perform a validation test to confirm the successful completion of the lab.

12. **Delete AWS Resources**
    - Remove all the resources created by Terraform to avoid incurring unnecessary charges.

## Usage

To use this project, follow the detailed instructions in each task to set up the environment, create necessary files, and execute Terraform commands.

## Cleanup

Run `terraform destroy` to delete all resources once you're done to ensure you're not charged for any unused services.

## Support

For support, please refer to the official AWS and Terraform documentation or the contact information provided in this lab guide.

## License

[Insert License Here]

## Author

Said B.

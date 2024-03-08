# Static Website with Terraform and AWS S3

## Project Overview

This project is a personal learning journey into the world of cloud infrastructure, specifically using Terraform and AWS S3 to deploy a static website. The goal of this project was to gain hands-on experience with Terraform as an infrastructure as code (IaC) tool and to understand the capabilities of AWS, particularly with S3 buckets for hosting static website content.

### Technologies Used

- **Terraform**: Used to provision and manage AWS resources in a declarative manner through code.
- **AWS S3**: Serves as the hosting solution for the static website, providing a scalable and reliable platform.
- **AWS**: General cloud infrastructure to explore and learn the various services offered.

## Project Status

Currently, the website is in its initial stages, with the primary focus being on the backend infrastructure setup rather than the frontend design. The static website is deployed and not been styled yet. Future updates will include CSS styling to improve the visual appeal and user experience of the website and then I will deploy the website.

## Learning Outcomes

Through this project, I have begun to understand the power and flexibility of using Terraform to manage cloud resources. Here are some key learning points:

- **Infrastructure as Code (IaC)**: Learned the importance and efficiency of managing infrastructure through code, allowing for easy tracking, updating, and versioning of cloud resources.
- **AWS S3 Basics**: Gained practical experience in using S3 buckets for hosting static content, including configuration for public access and website hosting settings.
- **Terraform Workflow**: Developed a workflow for using Terraform, including writing configurations, planning changes, and applying those changes to provision resources in AWS.

## Future Plans

- **Styling the Website**: The next step is to add CSS styling to the website to enhance its look and feel. This will also serve as an opportunity to learn more about web development best practices.
- **Exploring More AWS Services**: Continue learning about AWS by integrating other services with the website, such as AWS CloudFront for content delivery and AWS Route 53 for domain management.
- **Advanced Terraform Usage**: Delve deeper into Terraform's capabilities by exploring modules, backends, and more complex infrastructure setups.

## How to Use

To replicate this project or to deploy your version of the static website, you will need to have Terraform installed and an AWS account set up. Follow these steps:

1. Clone this repository.
2. Navigate to the project directory and initialize Terraform with `terraform init`.
3. Apply the Terraform configuration with `terraform apply`. Ensure you review the plan before applying.
4. Once applied, Terraform will output the URL of the S3 bucket where your static site is hosted.

## Contributions

Feedback and contributions are welcome! If you have suggestions or want to contribute to the project, feel free to create an issue or submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

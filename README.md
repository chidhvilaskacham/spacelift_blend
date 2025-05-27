# spacelift_blend

This project demonstrates how to blend Terraform and Ansible in a unified pipeline using Spacelift. It showcases an Infrastructure as Code (IaC) workflow where Spacelift provisions infrastructure with Terraform and then seamlessly hands over to Ansible for post-provisioning configuration. Ideal for teams looking to integrate declarative and procedural tooling in a cloud-agnostic, automated CI/CD environment.



# Overview
The spacelift_blend project showcases how to:

Provision infrastructure using Terraform.

Configure provisioned resources using Ansible.

Leverage Spacelift to orchestrate the entire workflow seamlessly.

This approach ensures a cohesive Infrastructure as Code (IaC) pipeline, enhancing automation and reducing manual intervention.
GitHub

# Repository Structure
1. tf-ansible-stack/: Contains the main stack configuration integrating Terraform and Ansible.
2. README.md: Provides an overview and guidance on setting up and using the project.

# Prerequisites
Before getting started, ensure you have the following:

1. A Spacelift account with necessary permissions.
2. Terraform installed locally for testing purposes.
3. Ansible installed locally for testing purposes.
4. Access to the infrastructure you intend to manage (e.g., AWS, Azure).

# Getting Started
Clone the Repository:
```sh
git clone https://github.com/chidhvilaskacham/spacelift_blend.git
cd spacelift_blend
```
# Set Up Spacelift Stack:
1. Log in to your Spacelift account.
2. Create a new stack and connect it to your forked repository.
3. Configure environment variables and backend settings as required.

# Configure Terraform and Ansible:

1. Navigate to the tf-ansible-stack/ directory.
2. Review and modify Terraform configurations to match your infrastructure needs.
3. Update Ansible playbooks and inventory files as necessary.

# Trigger a Run:

1. Push changes to the repository to trigger a Spacelift run.
2. Monitor the run's progress and review logs for any issues.

# AKS on Azure Local Documentation

Welcome to the AKS on Azure Local Documentation project. This repository provides comprehensive guidance on sizing, best practices, and operational management for deploying Azure Kubernetes Service (AKS) enabled by Azure Arc on Azure Local environments.

Azure Kubernetes Service (AKS) on Azure Local is an enterprise-grade Kubernetes container platform. It includes Microsoft-supported core Kubernetes, a purpose-built Windows container host, and a Microsoft-supported Linux container host, with a simple deployment and lifecycle management experience.

## Project Structure

The documentation is organized into several key sections:

- **Sizing**: Detailed information on how to size your Kubernetes cluster effectively, including:
  - Understanding the application workload
  - Infrastructure considerations
  - High availability and resilience requirements
  - Cost and licensing aspects
  - Operational overhead and management
  - Azure integration and services
  - Concrete sizing calculations
  - Practical sizing examples

- **Tools**: Practical tools to assist in planning and managing your deployment:
  - [PowerShell Sizing Calculator](./src/tools/AzureLocalK8sCalculator.ps1): An interactive script that guides you through the process of properly sizing your Azure Local Kubernetes environment based on your specific workload requirements
  - Storage performance recommendations
  - Capacity planning worksheets
  - Sizing examples for various applications
  - Monitoring strategies post-deployment

- **Best Practices**: Guidelines for optimizing your Azure Local Kubernetes setup, covering:
  - Network configuration
  - Storage configuration
  - Node placement strategies
  - Resource governance practices

- **Tools**: A section dedicated to resource calculation tools that assist in precise sizing calculations.

- **Images**: A directory for storing any relevant images that complement the documentation.

- **SUMMARY.md**: A summary or table of contents linking to the various markdown files for easy navigation.

## Getting Started

To get started with the Azure Local Kubernetes Documentation:

1. Clone the repository to your local machine.
2. Navigate to the `src` directory to explore the various markdown files.
3. Use the `SUMMARY.md` file as a guide to navigate through the documentation.

## Contribution

Contributions to improve the documentation are welcome! Please feel free to submit issues or pull requests for any enhancements or corrections.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

For any questions or feedback, please reach out to the maintainers of this project. Happy documenting!
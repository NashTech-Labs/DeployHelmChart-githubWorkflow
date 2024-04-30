# Deploy Web Application Deployment Template

This repository provides a template for deploying a web application on a Kubernetes cluster using a Helm chart and GitHub Actions for CI/CD.

## Usage

1. **Clone the repository**:

    Clone the repository to your local machine.

    ```bash
    git clone https://github.com/NashTech-Labs/DeployHelmChart-githubWorkflow.git
    cd DeployHelmChart-githubWorkflow
    ```

2. **Update the Helm chart**:

    - Customize the Helm chart in the `my-web-app` directory according to your application's needs.
    - Edit the `values.yaml` file to configure the application settings.

3. **Set up GitHub Actions secrets**:

    - Add any required secrets (e.g., Kubernetes cluster credentials) to your GitHub repository's secrets for the CI/CD workflows.

4. **Push your changes**:

    Commit and push your changes to the repository.

    ```bash
    git add .
    git commit -m "Update Helm chart and workflows"
    git push origin main
    ```

5. **Monitor the workflows**:

    Monitor the GitHub Actions CI/CD workflows in the Actions tab of your repository to ensure successful execution.

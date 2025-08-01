# Coder
Coder provides development environments in your public and private clouds. Environments are defined with Terraform, connected through a secure high-speed tunnel, and automatically shut down when not in use to save on costs. Coder gives engineering teams the flexibility to use the cloud for workloads that are most beneficial to them.

Developers can connect to Coder workspaces using the tools and IDEs they know and love including VS Code Remote, JetBrains Gateway, SSH as well as web IDEs such as JupyterLab, code-server, RStudio, and web terminals.
## Highlights
- Onboard developers in seconds instead of days
- Define development environments in Terraform (EC2 VMs, Kubernetes Pods, Docker Containers, etc.)
- Keep source code within your infrastructure, and use RBAC with existing authentication systems
- Automatically shutdown idle resources to save on costs
## Prerequisites
Review the Coder Kubernetes [installation instructions](https://coder.com/docs/install/kubernetes) for required prerequisites. 
## Parameters
Review options for the [values.yaml](https://github.com/coder/coder/blob/main/helm/coder/values.yaml) used by the Pack.
## Upgrade
To upgrade a Coder deployment, review Helm [upgrade steps](https://coder.com/docs/install/kubernetes#upgrading-coder-via-helm) and redeploy the latest release of the Pack.
## Usage
After a successful initial deployment, review the following [post install steps](https://coder.com/docs/install/kubernetes#5-log-in-to-coder-) to finalize or update your Coder configuration.
## Resources
- [Coder Documentation](https://coder.com/docs)
- [Coder Quickstart Guide](https://coder.com/docs/tutorials/quickstart)
- [Discord Community](https://discord.gg/coder)

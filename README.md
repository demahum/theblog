# The Blog

For now, the blog only has a welcome with no functionalities, stay tuned.

# Access the blog

The content of this repository is deployed to https://theblog.muhamed.link/

## Deployments

At the moment, Ubuntu node has been created, with nginx installed on it (manually). Additionally, static IP address has been associated to it, in addition to domain name associated to it (also manual).

Other than that all of the deployment is continous and automatic. There exists GitHub Action that deploys the new content (currently only html) to the mentioned location, making it available to the world as soon as it is ready. It is possible to trigger the Action manually, in addition to the fact that any content merged to production branch is automatically deployed.

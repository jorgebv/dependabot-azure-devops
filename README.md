# Fork Differences

This repository forks tinglesoftware/dependabot-azure-devops in order to hard-code some settings that are difficult or inconvenient to configure in the parent repository. The hard-coded settings focus on personal use and the use-case of running the Docker image in an Azure DevOps pipeline. The extension is not a concern for this fork.

The differences between this repository and the parent are:

- Hard coded commit convention of prefixing commits with "chore" and including the scope

# Releases

Docker images are available at jorgebvergara/dependabot-azure-devops on Docker Hub. No support is offered as these images are intended for my private consumption. Use them at your own risk. The image tags mirror the parent repository versions. That is to say: tag 0.9 of jorgebvergara/dependabot-azure-devops should be the same as tag 0.9 of tinglesoftware/dependabot-azure-devops with the patches described in the preceding section. If there is a letter after the tag, the latest letter alphabetically is the one with the most bugfixes and the one that should be used.

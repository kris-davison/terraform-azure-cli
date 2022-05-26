Fork of https://hub.docker.com/r/zenika/terraform-azure-cli / https://github.com/zenika-open-source/terraform-azure-cli

Changes to allow it to run as root user for running builds in this container in azure devops pipeline

Git Repo here - https://github.com/kris-davison/terraform-azure-cli
Docker Hub Image here - https://hub.docker.com/r/krisdavison/terraform-azure-cli


Docker tag format is the following - <T[TerraformVersion]-A[AzureCliVersion]> e.g. T0.14.11-A2.33.1

This matches the Dockerfile found in the repo with a similar name (dots replaced with underscore) e.g - T0_14_11-A2_33_1-Dockerfile
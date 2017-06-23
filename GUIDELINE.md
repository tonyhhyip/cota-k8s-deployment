# Guideline

## Deployment with Kubernetes Config
- Create a directory for the deployment
- Add a file named `REPO` and input the url for the repository of the images (e.g. https://github.com/containous/traefik)
- For Dockerfile hosting with another repository, please put the repository url in a file named `IMAGE`
- Create the yaml files for the deployment

## Deployment with Exists Helm Chart
- Create a directory for the deployment
- Add a file named `REPO` with the hostname of the repository if the repository is not the default stable repository
- Add a file named `CHART` for name of the chart
- Put all the customizing chart value in `config.yml`
- Add a file named `NAME` for the deployment

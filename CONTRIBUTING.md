# Contributing Guide

## Make suggestion on deployment
1. [Fork this repository](https://help.github.com/articles/fork-a-repo/)
2. Make change on your own forked repository. Please follow the [guideline](./GUIDELINE.md)
3. [Create Pull Request](https://help.github.com/articles/creating-a-pull-request/) to the branch which is named the same as the modified namespace (e.g. Create pull request to `oshk` branch if you make change in `oshk` namespace). Please create pull request to `doc` branch if you make change in document.

## Run deployment (For namespace maintainers only)
1. Checkout the specific branch
2. Check if the deployment is made
3. Execute the deployment with `kubectl` or `helm`
4. Make pull request to `master` branch

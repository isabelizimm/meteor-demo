Meteor Demo
==============================

This repository has materials for a hands-on tutorial to demonstrate tools developed by Red Hat's Artificial Intelligence Center of Excellence to aid Data Scientists and DevOps Engineers by automating many tasks involved in building an end-to-end machine learning application.

This tutorial highlights the capabilities of [Project Meteor](https://github.com/AICoE/meteor), which is a web application that converts users' GitHub repositories into [JupyterBook](https://jupyterbook.org/intro.html) environments. The demo features a "hello world" MNIST machine learning application, but the focus is on the integration of different tools for techniques such as dependency management, model serving, and others detailed below. Overall, this demo highlights the fact that Data Scientists benefit from many DevOps practices.


## Tools

There are a variety of tools that are highlighted in this tutorial. The main focus is on the tools below:

- [Jupyterlab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) is used to build Jupyter notebooks, text editors, and other components.
- [Elyra](https://github.com/elyra-ai/elyra) supplies a set of extensions to JupyterLab notebooks to support AI projects
- [Thoth](https://thoth-station.ninja/) is used to manage dependencies and keep tutorials up to date with the latest releases.
- [Kubeflow Pipelines](https://www.kubeflow.org/docs/components/pipelines/overview/pipelines-overview/) are used to schedule machine learning workflows via a user interface located within the JupyterLab environment.
- [Seldon Core](https://docs.seldon.io/projects/seldon-core/en/latest/) deploys machine learning models as REST/GRPC microservices.
- [Grafana](https://grafana.com/grafana/) is a dashboarding tool to observe data. In this demo, it is used to monitor model health.


## About the Environment

The Operate First open source production OpenShift environment currently hosts Project Meteor and this demo. Operate First looks to open-source operations on community managed clusters. To learn more about Operate First, visit the [website](https://www.operate-first.cloud/) or GitHub [community](https://github.com/operate-first).


## Project Organization

Project based on the cookiecutter data science [project template](https://drivendata.github.io/cookiecutter-data-science/).


## How to Contribute

If you would like to suggest a new feature or report a bug, please open a new [issue](https://github.com/aicoe-aiops/meteor-demo/issues/new/choose).


## Contact

This project is maintained as part of Red Hat's Artificial Intelligence Center of Excellence. More AICoE projects can be found [here](https://github.com/AICoE).

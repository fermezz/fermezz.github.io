---
layout: page
title: About
---

## What I’m interested in
### Open Source
I believe open source to be an extremely important part of the work that gets done software-wise, but also  wisdom-wise. I’ve sadly participated very little in it, but I try to do so [any chance I get](https://github.com/pytest-dev/pytest/compare/f606fef...a6029ff).

## What I’ve done
### [Eventbrite](https://eventbrite.com)
#### Tech Debt
I consider addressing tech debt a very important part of our –the software developers'– jobs so I like to get involved thus this section right here at the top.

I was part of a project that consisted in migrating all of our +100 repositories using Python from Python 2 to Python 3 and from Python 3.5 to Python 3.7+. For that to happen, we implemented a bunch of Jenkins pipelines that run tests – with [Tox](https://tox.readthedocs.io/en/latest/) and [Pytest](https://docs.pytest.org/en/latest/) – inside a Docker container for several combinations of versions of Python and other libraries. This allowed us not only to upgrade the version of Python once, but laid the foundations for further upgrades, sped up the process, and gave the rest of the developers a fairly easy way of doing upgrades in their respective services.

I also participated on deprecating a built-in-house, very old ORM for Python in favor of the Django ORM.

I was involved in a company-wide effort of breaking up a huge monolith into remote services.

#### DevTools
I worked on building and maintaining our CI/CD process with mainly Jenkins and on supporting and maintaining Eventbrite’s built-in-house, Kubernetes-based development tool hosted in EKS. Because of this I am familiar with the AWS stack –EKS, ECR, CloudWatch, etc.,– and infrastructure as Code tools such as Terraform.

I worked on and led the project of re-designing the Dockerfiles for our 50+ services so that developers could have development and production environments defined in the same repository and implemented all the necessary CI pipelines for the changes to be as transparent as possible for them. This project removed a lot of friction between developers and the DevTools team, and gave a lot more freedom to developers.

I implemented a Docker caching mechanism that reduced CI build time between 30% and 70%. Developer productivity is _important_.

#### Music Product
I worked on building and maintaining a Python and Django –to name a few technologies– powered service that featured the management and search of 5M+ artists indexed in Elasticsearch.

I worked on designing, implementing, documenting and maintaining public and private REST-ish API endpoints.

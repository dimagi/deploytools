Dimagi Deployment Skeleton
==========================

This repository is a set of frequently reused scripts and tools for a django deployment on a production environment.

These tools make a few assumptions:

- You use upstart for your init scripting
- You use virtualenv for your python environments
- You plan on putting your project in a directory relative to this project dir
- You run django the way we run django.

Workflow
========

- cd /project_repository
- git clone this
- cp -r this to project_name
- cd project_name
- cd src
- git clone project_src
- edit the upstart scripts to reflect your project and copy it to init

More to come

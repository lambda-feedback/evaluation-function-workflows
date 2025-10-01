# Evaluation Function Reusable Workflows

This repository contains common workflows which can be used to build and deploy evaluation functions.

Notes:
- For production deployment, `eval-production` must be defined in the repo (or template repo) with review protections
- To build to AWS or GCP, the calling workflow should add `build-platforms: 'gcp'` to the calling workflow. 'aws' is the default
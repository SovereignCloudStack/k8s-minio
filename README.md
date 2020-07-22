# Deployment manifests for MinIO®

## Attribution

MINIO/MinIO is a trademark of the MinIO Corporation which is not affiliated with the SCS project.

## Repository content

This repository is intended to include all relevant configuration
and Kubernetes manifests for the deployment of the open source MinIO
object storage software inside SCS.

## Repository layout

This repository contains kustomize bases which may be referenced by
kustomize overlays which in turn define the deployment of whole
environments/clusters.

## Automated smoke tests

In order to ensure that every component inside of SCS behaves as
expected, there should be simple smoke tests.
These tests are implemented using GitHub Actions/Workflows.

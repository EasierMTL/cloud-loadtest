# `cloud-loadtest`

CLI that loadtests your cloud infrastructure (GCP GCE/AWS EC2) with Locust.

- Automatically deploys your cloud infrastructure for load-testing
- And cleans it up when load-testing is done.
- Outputs the benchmarks in a nice table.

Uses `terraform`, `gcloud` and `aws` under the hood, so it will require some basic preliminary setup with each of those providers.

## WIP

1. Need to make the CLI more generalizable to all containers
2. Allow flexibility to set environment variables at runtime.
3. Output the loadtesting results to a `.csv` more cleanly.

## Getting Started

```
poetry install
```

## Future Plans

- Automatically deploy Kubernetes GKE/EKS infrastructure and load test that.

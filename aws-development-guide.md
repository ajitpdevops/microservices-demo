# Development Guide with AWS

This document explains how to get started with 11-tier microservices demo application with

## Steps to undertake

1. Review all microservices and change google-cloud dependancies to AWS or Generic (E.g. AlloyDB to RDS or similar)
2. Figure out a way to run this with Development Env in AWS.
   - Create cluster
   - Deploy microservices
   - Use `skaffold` to build docker in bulk
3. Review the K8s manifests.
4. Once the application is running in development, implement terraform for infra.
5. Review the Kubernetes extended components like helm, istio, kustomize etc.
6. CI/CD with GitHub Actions or Jenkins

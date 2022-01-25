# Argocd

This repository containing application yaml files that will be install in argocd.



In kustomization.yaml file we point on the resources that have to be install on argocd.

Evry application has her own configuration.

## Change configuration

_role-arn_ - in every application you have to change the role-arn in annotations to yor role (you can find it in aws/iam/role)

_prometheus.yaml_ - change annotations and hosts to your domain

_pocoz.yaml_ - change repoURL to your repository

_manifests/nginx-culster-Issuers.yaml_ - this yaml is part of cert-manager application you have to change the email address
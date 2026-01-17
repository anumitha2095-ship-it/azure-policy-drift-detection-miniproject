# azure-policy-drift-detection-miniproject
Azure custom policies for detecting configuration drift and security misconfigurations
# Azure Configuration Drift Detection using Custom Policies

## Overview
This repository contains custom Azure Policy definitions developed to detect
and prevent cloud security misconfigurations such as:
- Publicly accessible storage accounts
- Non-compliant Network Security Group (NSG) rules
- Excessive RBAC permissions

The project demonstrates practical implementation of
Cloud Security Posture Management (CSPM) concepts using Azure native services.

## Policies Included
- deny-public-storage.json  
- enforce-nsg-rules.json  
- restrict-rbac-roles.json  

## Deployment
Policies can be deployed using:
- Azure Portal
- Azure CLI
- Azure Policy Assignments at subscription level

## Academic Use
This repository supports the master thesis:
"Azure Configuration Drift: An Experimental Study on Cloud Security Misconfigurations"

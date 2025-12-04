Azure Identity Governance Automation

Automation tools for Cloud Security, IAM, and GRC assessments in Microsoft Azure.

Overview

This project contains two Python-based automation tools that perform identity governance tasks commonly required in Cloud Security, IAM Operations, and Security Auditing.

Both tools use the Azure CLI and run entirely in Azure Cloud Shell — requiring no local setup.

Included Tools

1) IAM Least Privilege Scanner

Detects overly permissive Azure RBAC assignments

Flags Owner, Contributor, and User Access Administrator roles

Highlights roles scoped too broadly (subscription or resource group level)

Generates a CSV governance report

Helps enforce least privilege and reduce attack surface

Folder: /iam-least-priv-scanner

2) Inactive User / Identity Lifecycle Scanner

Enumerates Azure AD users

Identifies disabled accounts

Detects guest accounts older than 90 days

Helps support periodic access reviews (NIST AC-2)

Outputs a CSV for audit or IAM cleanup work

Folder: /inactive-user-scanner

Technologies Used

Python 3

Azure CLI

Azure Cloud Shell

Entra ID (Azure AD)

CSV reporting for audit evidence

Purpose

These tools demonstrate automation capabilities in:

Cloud Identity Governance

RBAC Hardening

Access Review Automation

Security & Compliance Auditing

IAM Lifecycle Management

They can be used by:

Cloud Security Engineers

GRC/Audit Teams

IAM Analysts

SOC & Operations teams

Author

Michael McPhee Jr.
Cloud Security & GRC Analyst

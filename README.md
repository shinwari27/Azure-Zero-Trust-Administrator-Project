Azure Zero Trust Administrator Project
Overview

This project demonstrates the design and implementation of a Zero Trust security model in Microsoft Azure, focusing on identity-first security, least privilege access, governance, monitoring, cost control, and incident response.

The project follows real enterprise practices and is executed in six structured phases, combining GUI-based validation with automation-ready configurations.

Architecture Summary

Identity as the control plane (Azure Entra ID)

Least privilege via RBAC and custom roles

Governance enforced through Azure Policy

Operational visibility using logs and alerts

Cost governance using budgets

Incident response procedures documented and tested

Project Phases
Phase 1 – Identity & Access Management

Configured Azure Entra ID users and roles

Enforced MFA using Conditional Access

Designed break-glass emergency access

Validated secure sign-in behavior

Phase 2 – Role-Based Access Control (RBAC)

Assigned built-in roles at correct scopes

Created a custom RBAC role (JSON)

Applied least privilege access principles

Tested role behavior using standard users

Phase 3 – Governance & Resource Control

Enforced mandatory resource tags

Restricted allowed deployment locations

Assigned Azure Policies at subscription scope

Reviewed compliance results

Phase 4 – Resource Organization & Cost Management

Organized workloads using standardized Resource Groups

Created monthly cost budgets

Configured cost alerts

Reviewed cost optimization opportunities

Phase 5 – Monitoring, Logging & Alerts

Reviewed Azure Activity Logs

Reviewed Entra ID sign-in logs

Configured alerts for:

Failed sign-in attempts

Role assignment changes

Validated alert behavior and notifications

Phase 6 – Incident Response & Operational Readiness

Designed response procedures for account compromise

Implemented account isolation and recovery steps

Documented remediation and reporting workflows

Created an administrator operational checklist

 Tools & Technologies

Azure Portal (GUI)

Azure Entra ID

Azure RBAC

Azure Policy

Azure Monitor & Logs

PowerShell (Az & Microsoft Graph)

JSON (Custom RBAC)

Skills Demonstrated

Cloud security fundamentals

Zero Trust architecture

Identity and access management

Governance and compliance

Incident response planning

Operational readiness

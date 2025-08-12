# DevSecOps-Snyk-GithubActions
This repo builds a github action workflow that uses Snyk to automatically scan for vulnerabilities in the codebase and dependencies.

## 🔍 How It Works
- The workflow runs **Snyk** on every push and pull request.
- Snyk checks for known vulnerabilities in dependencies and reports them directly in the GitHub Actions log and the repository’s Security tab.
- This helps ensure security risks are identified and addressed early in the development process.

## ⚠ Known Vulnerability
This repository currently includes the NuGet package:

- **[OpenTelemetry.Api](https://www.nuget.org/packages/OpenTelemetry.Api)** – version **1.10.0**

> **Severity:** High  
> **Description:** This version contains a **serious known security vulnerability**.  
> It is strongly recommended to update to a secure version as soon as possible.

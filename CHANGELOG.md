# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added
- Pending

### Changed
- Pending

### Fixed
- Pending

### Removed
- Pending

---

## [2026-05-12] - Project Setup and Initial Azure Deployment

### Added
- [arabyte-src] Created the Azure Resource Group `fixit` in the Southeast Asia region to serve as the main container for the FIXIT deployment.
- [arabyte-src] Created the App Service Plan `FIXIT` on Linux Basic B1 tier to provide the compute layer for the web application.
- [arabyte-src] Deployed the Web App `fixit-app` using Python 3.11 on Linux and confirmed that the site was running in Azure Portal.


### Fixed
- [arabyte-src] Fixed the App Service deployment workflow so it matched the actual Azure Portal configuration after repeated failed runs.
- [arabyte-src] Corrected the Azure login OIDC subject issue that caused deployment attempts to fail during the GitHub workflow.
- [arabyte-src] Serialized Azure deployments so overlapping build/deploy jobs would not conflict with each other.

---

## [2026-05-13] - Deployment Documentation and Cost Report Finalization

### Added
- [elyssaolivares] Added the deployment guide in `cloud-computing/deployment/README.md` with the step-by-step Azure Portal workflow and screenshot requirements.
- [elyssaolivares] Added the cost estimate report in `cloud-computing/report/cost-estimate.md` with the Azure Pricing Calculator estimate and optimization notes.

### Changed

### Fixed


### Removed
# wordpress-wimp-kudu-gcp
Wordpress on Windows Server + IIS setup (WIMP) stack utilizing Kudu git-based deploy workflow with pull request instances | Google Cloud Platform

## tools/services utilized:
- Wordpress
- Wordpress CLI
- Lando
- wp-packagist
- satispress
- composer
- PHP
- IIS
- Windows Server
- PowerShell
- Project Kudu
- Visual Studio Community (version x.x)
- nodejs (version x)
- chocolatey
- nuget
- PS-Install
- scoop?
- Certify the Web (windows server desktop application / requires license)
- Github
- Cloudflare
- MySQL community edition (for local install on PR Deploy instances)
- Google Cloud Platform:
  - Compute Engine (using a machine image for pre-installed kudu deploy win server instance, if not starting from scratch)
  - Cloud SQL (mysql v 5.x)
  - Cloud Build
  - Secret Manager
  - Cloud Storage
  - Cloud Run
  - Cloud Scheduler
  - Cloud Source Repositories
  - Cloud Batch (?)
  - 



Site setup checklist reference (example is with Machform install):
https://github.com/The-Clinton-Foundation/cf-forms-builds/issues/310

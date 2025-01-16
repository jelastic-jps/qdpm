<p align="center"> 
<img src="images/qdpm.png" alt="qdPM">
</p>

# qdPM

The package deploys the [qdPM](https://qdpm.net/) solution - a web-based project management tool with a user-friendly interface suitable for a small team working on multiple projects. qdPM offers a comprehensive suite of features, including task management, time tracking, and reporting.
 

## Environment Topology

This package creates a dedicated qdPM environment that contains one application server and one database container. It automatically deploys and sets the qdPM application. The automatic vertical scaling is enabled out of the box, and [horizontal scaling](https://www.virtuozzo.com/application-platform-docs/automatic-horizontal-scaling/) can be configured (if needed). The default software stacks utilized in the package are the following:

- Apache 2 PHP application server (PHP 8.2)
- MySQL 8 database
- qdPM 9.3


## Deployment to Cloud

To get your qdPM solution, click the "**Deploy to Cloud**" button below, specify your email address within the widget, choose one of the [Virtuozzo Public Cloud Providers](https://www.virtuozzo.com/application-platform-partners/), and confirm by clicking **Install**.

[![Deploy to Cloud](https://raw.githubusercontent.com/jelastic-jps/common/main/images/deploy-to-cloud.png)](https://www.virtuozzo.com/install/?manifest=https://raw.githubusercontent.com/jelastic-jps/qdpm/refs/heads/master/manifest.jps)

> If you already have a Virtuozzo Application Platform (VAP) account, you can deploy this solution from the [Marketplace](https://www.virtuozzo.com/application-platform-docs/marketplace/) or [import](https://www.virtuozzo.com/application-platform-docs/environment-import/) a manifest file from this repository.


## Installation Process

In the opened installation window at the VAP dashboard, provide a preferred environment and display names, choose a region (if available), and confirm the installation.

![qdPM deployment wizard](images/qdpm-deployment-wizard.png)

Your qdPM application will be automatically installed in a few minutes.

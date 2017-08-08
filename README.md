[![Build Status](https://travis-ci.org/capitalone/Hygieia.svg?branch=master)](https://travis-ci.org/capitalone/Hygieia)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/de1a2a557f8e458e9a959be8c2e7fcba)](https://www.codacy.com/app/amit-mawkin/Hygieia)
[![Maven Central](https://img.shields.io/maven-central/v/com.capitalone.dashboard/Hygieia.svg)](http://search.maven.org/#search%7Cga%7C1%7Ccapitalone)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Join the chat at https://gitter.im/capitalone/Hygieia](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/capitalone/Hygieia?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  

<img width="600" src="/images/hygieia_b.png"> <a href="https://info.blackducksoftware.com/OpenSourceRookies2015.html" > <img src="/images/Rookies_Award_Badge.png" width="100" align="right" alt="Hygieia℠ is now BlackDuck 2015 OpenSource Rookie of the Year"></a>

Contents
--------
- [About Hygieia](#about-hygieia)
- [Objectives](#objectives)
- [Features](#features)
- [Hygieia Architecture](#hygieia-architecture)
- [Quick Setup Instructions](#quick-setup-instructions)
- [Hygieia Dashboard - A Snapshot](#hygieia-dashboard-a-snapshot)
- [Contributing](#contributing)
- [Links](#links)

## About Hygieia
**Pronunciation: _hi-gee-ya_ (Origin: Greek)**

Hygieia dashboard is a single, configurable, easy-to-use dashboard to visualize near real-time status of the entire delivery pipeline. In addition, it provides a continuous feedback loop for any DevOps organization.

Hygieia dashboards are customizable: you can select your story tracking tools, code repository, users can select VersionOne or Jira for story tracking, Subversion or GitHub as repositories, Jenkins/Hudson for builds, Selenium and SonarQube for quality, uDeploy and Jenkins for deployment. More plugins are available.

Hygieia dashboards assist in achieving process transparency and therefore help establish feedback loops that are the underlying concept of lean and DevOps. They contain interactive elements which enable drill-down and linking to the connected tools.

Watch this video to see Hygieia in action:
[![Hygieia℠ Is AWESOME](/images/video-shot.png)](https://www.youtube.com/watch?v=SoNTA78j0tc "Hygieia Is AWESOME")

## Objectives
* Automate Development Environment Setup
* Continuous Performance Measurement and Visualization
* Unified DevOps Dashboard

## Features
- **Visual Delivery Pipeline** - Use the pipeline view to visualize the status of the entire delivery pipeline and the components’ lifecycle progression.
- **Team Dashboard** - Monitor work items, code repo, builds, quality items (unit tests, security coverage), and deployments in a single dashboard.
- **Real-time Status** - Monitor quality, productivity, and work in process on a real-time basis within the dashboard.
- **Configurable View** - Setup the dashboard to display the widgets that matter most to your project, which helps amplify and shorten to feedback loop.
- **Open Source** - Hygieia is open source and free for everyone to use. We also encourage external users to contribute to the project.

## Hygieia Architecture

[!Architecture Overview](/images/architecture.png)

## Quick Setup Instructions

Hygieia layers:
* DB
* API
* UI
* Collectors

## Hygieia Dashboard - A Snapshot
A view is a primary mechanism for displaying data. The Hygieia dashboard offers comprehensive overview through two view methods:
- **Widget view** - Widget view showcases more detailed information: features in the current sprint, code contribution activities, continuous integration activities, code analysis, security analysis, unit and functional test results, and deployment and environment status.
- **Pipeline view** - The pipeline view pulls back to show each component’s lifecycle progression through the development, testing, and deployment stages.

### Widget View
[!Widget View](/images/hygiea-screenshot.jpg)

### Pipeline View
[!Pipeline View](/images/hygieia-product-dashboard.png)

## Contributing

We welcome Your interest in Capital One’s Open Source Projects (the “Project”). Any Contributor to the Project must accept and sign an Agreement indicating agreement to the license terms below. Except for the license granted in this Agreement to Capital One and to recipients of software distributed by Capital One, You reserve all right, title, and interest in and to Your Contributions; this Agreement does not impact Your rights to use Your own Contributions for any other purpose.

##### [Individual Agreement](https://docs.google.com/forms/d/19LpBBjykHPox18vrZvBbZUcK6gQTj7qv1O5hCduAZFU/viewform)
##### [Corporate Agreement](https://docs.google.com/forms/d/e/1FAIpQLSeAbobIPLCVZD_ccgtMWBDAcN68oqbAJBQyDTSAQ1AkYuCp_g/viewform?usp=send_form)

This project adheres to the [Open Code of Conduct][code-of-conduct]. By participating, you are expected to honor this code.

[code-of-conduct]: http://www.capitalone.io/codeofconduct/

## Links
- Documentation
- Installation and Setup Instructions
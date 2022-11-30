---
sidebar_position: 1
slug : /
---

# GitHub metrics tracker

Ever wanted to track your GitHub activity over time? Well, now you can!

## Contributing

This [GitHub Metrics](https://github.com/gloveboxes/GitHub-Metrics-Endpoint) project is open source and welcomes contributions. Please raise an issue or submit a pull request.

## Overview

![The image shows the solution architecture](img/architecture.png)

GitHub metrics are collected by a GitHub action that is triggered by a scheduled event. The GitHub action collects metrics from the GitHub API and posts the metrics to an Azure Function App webhook. The Azure Function App webhook is a secure endpoint that accepts the metrics payload and stores the metrics in a database. Power BI is used to visualize the metrics data.

## Understanding the documentation

1. If you are enabling GitHub metrics tracking for a repo then follow the [metrics tracker](20-metrics-tracker/05-introduction.md) documentation.
1. If you are deploying the GitHub metrics solution then follow the [deploy solution](10-deploy-solution/03-introduction.md) documentation.

# Graph Technologies Service Status

[![Upptime](https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/logo.svg)](https://upptime.js.org)

This repository contains the service status monitoring for Graph Technologies services, powered by [Upptime](https://upptime.js.org).

## 📊 Live Status

Visit our status page to see real-time availability and performance metrics.

## 🔧 Configuration

This status page is configured to monitor:

- **Graph Technologies Main Site** - https://graphtechnologies.xyz

Additional services can be added by updating the `.upptimerc.yml` configuration file.

## 📈 How it works

- GitHub Actions is used as an uptime monitor
  - Every 5 minutes, a workflow visits our services to make sure they're up
  - Response time is recorded every 6 hours and committed to git
  - Graphs of response time are generated every day
- GitHub Issues is used for incident reports
  - An issue is opened if an endpoint is down
  - Issues are closed automatically when the site comes back up
- GitHub Pages is used for the status website
  - A simple, beautiful, and accessible PWA is generated
  - Fetches data from this repository using the GitHub API

_This monitoring solution is powered by [Upptime](https://upptime.js.org), an open-source uptime monitor and status page._

## 📖 Documentation

For more information about how this monitoring system works, visit the [Upptime documentation](https://upptime.js.org/docs).

# Webinar registration sample application

This application is a slightly more advanced version of the basic node.js
starter application provided by the IBM Cloud platform. It uses the express
package to serve a web form from the /public directory. When the user clicks
Submit on that page, app.js takes the data from the form and inserts it into
a Cloudant database hosted in the IBM Cloud.

## Running this app
This app is designed to be run four different ways:

1. As a standalone app running on your machine
1. As a Cloud Foundry app running in the IBM Cloud
1. In a Docker container running on your machine
1. In a Kubernetes cluster running in the IBM Cloud

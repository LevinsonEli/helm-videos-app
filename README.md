# Videos App Helm Chart

This Helm chart is part of the [videos-app](https://github.com/LevinsonEli/videos-app/tree/master) project.

## Project Structure

This project includes the following Kubernetes resources:
* **Deployment** - Manages the deployment of the Videos App.
* **Service** - Exposes the application within the cluster.
* **ConfigMap** - Handles non-sensitive configuration data.
* **Ingress** - Manages external access to the application.
* **ServiceMonitor** - Enables Prometheus to monitor the application's metrics.

## Dependencies

* **MongoDB** - The application relies on MongoDB for data storage.
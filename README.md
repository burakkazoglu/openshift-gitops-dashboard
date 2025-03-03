## OpenShift GitOps (ArgoCD) Dashboard

## 📌 Description
This OpenShift GitOps Dashboard is designed to monitor ArgoCD applications synchronization status, memory & CPU usage, gRPC calls, error codes, and repository management using Grafana. Failed Syncs, application health status, and critical ArgoCD indicators are analyzed in detail on this dashboard.

## 🛠 Included Panels
- **⏳ Uptime** → Shows how long the ArgoCD server has been running.
- **📦 Applications** → Lists ArgoCD applications running on OpenShift.
- **🔗 Repositories** → Tracks Git repositories connected to ArgoCD.
- **🔄 Sync Status** → Displays application synchronization status (Synced, OutOfSync, Error, etc.).
- **❤️ Health Status** → Shows the health status of applications (Healthy, Degraded, Missing, etc.).
- **📋 ArgoCD Applications Sync Status** → Provides a table view of applications and their synchronization status.
- **🔄 Sync Success vs Failures (24h)** → Compares successful vs. failed syncs in the last 24 hours.
- **🔥 ArgoCD CPU & Memory Usage** → Measures the memory and CPU usage of the ArgoCD server.
- **📡 OpenShift API Request Latency (HAProxy)** → Monitors OpenShift API request latency.
- **📊 gRPC Calls & Errors** → Shows detailed gRPC calls and error codes for ArgoCD.
- **📋 Auto-Sync Status** → Displays ArgoCD's auto-sync status.
- **🛠 Redis & Git Requests** → Monitors Redis and Git requests made by ArgoCD.

## 🚀 Setup & Usage
1. Go to the "Dashboards" section in Grafana
2. Select the "Import" option
3. Upload the JSON file or paste its content
4. Select your data source (Prometheus)
5. Save the dashboard and start monitoring!


## 🔄 UPCOMING UPDATES  

- **📊 User-Based Sync Tracking** → A new metric panel will be added to monitor synchronization actions performed by specific users on ArgoCD.  
- **🔍 Search and Filtering Feature** → Advanced search and filtering options will be added to tables on the dashboard.  
- **📉 More Detailed Memory and CPU Usage Graphs** → Detailed pod-level analysis will be included in existing resource usage graphs.  
- **🚨 Error and Warning Alerts** → A Grafana alert mechanism will be added for ArgoCD synchronization errors.  
- **🌍 Multi-Namespace Support** → The ability to monitor applications across multiple namespaces simultaneously will be introduced.  
- **📌 Dashboard Performance Optimization** → Queries will be optimized to reduce dashboard load time.  



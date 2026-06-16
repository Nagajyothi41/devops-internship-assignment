\# Monitoring Strategy



\## Metrics



Metrics are numerical measurements collected over time.



Examples:



\* CPU Usage

\* Memory Usage

\* Network Traffic

\* Request Count



Tools:



\* Prometheus

\* CloudWatch



\---



\## Logs



Logs record events occurring inside applications.



Examples:



\* User Login Events

\* Application Errors

\* API Requests



Tools:



\* ELK Stack

\* CloudWatch Logs



\---



\## Traces



Traces follow a request across multiple services.



Examples:



\* API Gateway → Service → Database



Tools:



\* OpenTelemetry

\* AWS X-Ray



\---



\## Kubernetes Monitoring



Recommended Stack:



\* Prometheus

\* Grafana



Prometheus collects metrics.



Grafana visualizes dashboards.



\---



\## Pod Crash Investigation



Useful Commands:



kubectl get pods



kubectl describe pod <pod-name>



kubectl logs <pod-name>



These commands help identify application failures.




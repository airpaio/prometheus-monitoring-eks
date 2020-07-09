## Synthetic Monitoring With Prometheus In The Cloud

This repo extends the previous example of UI automation using Synthetic Transaction Monitoring with Prometheus & Grafana from https://github.com/airpaio/prometheus-synthetic-transactions. The code accompany's the fourth in a series of blog posts on monitoring and observability which can be found on https://airpa.io/post/prometheus-monitoring-eks.

This code focuses on deployment to Amazon's Elastic Kubernetes Service (EKS) of our project using Prometheus & Grafana to monitor synthetic transactions on a web application.

#### Use Your Own AWS Resources:
Since we are using AWS Resources, please be sure to replace "ID" values with your own in the locations I have marked throughtout the code. You will find markers like **`<yourSubnet01ID>`** or **`<yourVPCID>`**, and some comments like **`# replace with your Worker node IP`**

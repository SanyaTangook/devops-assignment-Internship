# DevOps Internship Assignment

## Objective
This assignment is designed to test the candidate's knowledge and skills in various DevOps areas, including CI/CD pipelines, Docker, Kubernetes, scaling, monitoring, logging, and automation scripting.

## Tasks

### Task 1: Build CI/CD Pipeline
1. Create a Continuous Integration/Continuous Deployment (CI/CD) pipeline for an application using Docker.
2. The pipeline should:
   - Build a Docker image for the application.
   - Run unit tests and ensure the code quality is acceptable.
   - Deploy the application to a Kubernetes cluster.
   - Ensure rollback capability in case of failed deployments.
3. Use Jenkins or GitLab CI/CD for the pipeline orchestration.
4. Integrate a code quality tool (e.g., SonarQube) to analyze code quality.

### Task 2: Deploy Application on Kubernetes
1. Write YAML files to deploy an application on a Kubernetes cluster.
2. The YAML files should include:
   - A Deployment resource to manage application pods.
   - A Service resource to expose the application.
   - An Ingress resource for external access (optional, based on requirements).
3. Use ConfigMap and Secret to manage configuration and sensitive data for the application.

### Task 3: Autoscaling & Monitoring
1. Implement autoscaling for the deployed application based on CPU and memory usage.
2. Set up monitoring with Prometheus and Grafana to track the application's resource usage and health.
3. Create basic Grafana dashboards to visualize CPU, memory usage, and the status of the application.

### Task 4: Centralized Logging
1. Set up centralized logging using Fluentd or Fluent Bit.
2. Send logs to either Elasticsearch or Loki for aggregation.
3. Use Kibana or Grafana to visualize logs and monitor application logs for errors or performance issues.

### Task 5: Automation Scripting
1. Write a script (Bash or Python) that automates the creation of resources on a cloud platform (AWS, DigitalOcean, or similar).
2. The script should be able to:
   - Create a Kubernetes cluster.
   - Deploy a sample application to the cluster.
   - Monitor the status of the deployment.

## Deliverables
1. A Git repository with all code and configuration files.
2. A README file that explains how to set up and run each part of the assignment, including how to access the Kubernetes cluster and monitor the application.
3. Screenshots or logs of the working CI/CD pipeline, application deployment, autoscaling, and monitoring setup.
4. Any relevant documentation or instructions for setting up the logging system and the automation script.

## Evaluation Criteria
1. **Correctness**: Is the pipeline functioning as expected? Are the Kubernetes resources configured correctly?
2. **Scalability**: Does the system scale automatically based on traffic/load?
3. **Monitoring & Logging**: Are Prometheus, Grafana, and logging tools configured properly?
4. **Automation**: Does the script automate the required cloud resources creation efficiently?
5. **Code Quality**: Is the code clean, well-organized, and well-documented?

## Deadline
- The assignment should be submitted within 5 days of receiving it.

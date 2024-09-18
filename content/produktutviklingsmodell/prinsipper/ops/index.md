---
title: Ops
ingress: The Ops (Operations) part of DevOps refers to the practices, processes, and technologies involved in managing and maintaining IT 
infrastructure, systems, and applications in production. It focuses on ensuring that software runs smoothly, reliably, and securely in a live 
environment.

navigation_link:
  subtitle: Prinsipper

banner:
  image:
    src: /illustrations/illustration-03.png
    alt: Illustrasjon av en person som holder mobilskjerm på kneet sitt
---

The Ops (Operations) part of DevOps refers to the practices, processes, and technologies involved in managing and maintaining IT infrastructure, systems, and applications in production. It focuses on ensuring that software runs smoothly, reliably, and securely in a live environment. Here's a breakdown of the key components of the Ops side:

1. Infrastructure Management
Provisioning: Setting up and configuring servers, storage, networking, and other infrastructure.
Automation: Using tools (e.g., Terraform, Ansible) to automate the provisioning and configuration of infrastructure to ensure consistency and scalability.

Monitoring and Alerts: Continuously monitoring system performance, uptime, and health (using tools like Prometheus, Nagios, or Datadog). Alerts are triggered when thresholds are breached, allowing for immediate attention to potential issues.

3. System Reliability and Availability
Incident Management: Ensuring that when an issue occurs (e.g., a system outage), it's resolved quickly with minimal disruption. This involves maintaining runbooks, response teams, and postmortem processes.
High Availability (HA) and Fault Tolerance: Designing systems to be resilient to failures through redundancy, failover mechanisms, and load balancing.
Backup and Disaster Recovery: Ensuring that data and systems can be restored in the event of hardware failures, cyber-attacks, or other disasters.

4. Security
Patching and Updates: Regularly applying software updates, patches, and security fixes to ensure that systems are protected from vulnerabilities.
Access Control and Permissions: Managing who has access to different parts of the infrastructure, often implemented through role-based access control (RBAC).
Network Security: Implementing firewalls, VPNs, and other security measures to protect the network.

5. Deployment and Configuration Management
CI/CD Pipelines: Automating the deployment process by integrating continuous integration/continuous delivery (CI/CD) pipelines that ensure code changes are tested, built, and deployed in an automated and reliable manner.
Configuration Management: Ensuring that the system configurations (e.g., environment variables, service settings) are consistent across environments (development, staging, production) through tools like Puppet, Chef, or SaltStack.

6. Performance Optimization
Scaling: Ensuring systems can scale to handle increased load by adding resources or improving performance through horizontal or vertical scaling.
Resource Management: Optimizing the use of computational resources (CPU, memory, storage) to improve performance and reduce costs, often using orchestration tools like Kubernetes.

7. Observability
Logging: Collecting and managing logs (e.g., application logs, system logs) to troubleshoot and track issues. Tools like ELK Stack (Elasticsearch, Logstash, Kibana) or Splunk are commonly used.
Metrics and Tracing: Tracking key metrics (e.g., latency, throughput, error rates) and tracing requests through distributed systems to diagnose performance bottlenecks or failures.

8. Collaboration with Dev
Feedback Loops: Working closely with development teams to provide feedback about how applications perform in production, helping developers optimize code and avoid potential issues.
Shared Responsibility: In DevOps, Ops teams often share the responsibility of deployment and issue resolution with Dev teams, fostering closer collaboration and communication.

In summary, the Ops part of DevOps focuses on the stability, reliability, security, and performance of the system in production. It's about creating a seamless, automated, and efficient operational environment where developers can deploy their code quickly, safely, and at scale.

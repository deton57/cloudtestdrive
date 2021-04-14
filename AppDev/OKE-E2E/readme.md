Welcome to OKE-E2E.
This will be a new OKE Workshop which will include an App/Webapp that will be installed on top of OKE. 
In this workshop we will use different open source tools for installation, development, deployments, and maintenance.


# Goals: #

1. Achieve E2E workshop that can be deployed easily in each OCI tenant 
2. Each pillar of the workshop can be disscussed and demonstrated individually 


### Guidelines: ###

1. Use open source 
2. Utilize the advantage of OCI services
3. Learn & Contribute for self and project improvement 


### The flow (high level): ###


A Company that wants to release new features for their customers, has 2 groups of users: 

1. Regular users
2. Early adopters 

When releasing a new feature one of their non technical personnel (Administrator/ Manager /UI/UX Designer) 
will connect to an administrator panel in the Web App, and will select one of the desired group of users and will select the new feature to release.
Only the desired group of users will receive the new feature. 
In order to achieve this flow, we will use different tools and technologies: 

### Tech and tools: ###

1. Git Repository - for the application source code.
2. Docker & Oracle Registry - all the app components will be based on dockers and the dockers will be stored in OCIR.
3. Helm & Chartmuseum - all the deployments will be defined in helm charts and stored in a chartmuseum.
4. GitOps - all the deployments will be based on GitOps principals and we will use one of the GitOps open source tools like: Flux/Argo/others.
5. Web App - we can use Python (not a must) and we can use any web development framework.
6. Database - TBD...
7. OKE - we will use Oracle Managed Kubernetes service as our infrastructure for deploying the application components.
8. Terraform - we will use Terraform and Resource Manager for creating all the OCI resources we need for this workshop.
9. Service Mesh - we will use for routing traffic and observing services we can use Istio/Linkerd.
10. Progressive Deployments - we will use tools such as Flagger/Argo rollouts for Canary, Blue/Green and A/B testing. 
11. Monitoring - we will use Prometheus/Grafana and Kubernetes Dashboard for monitoring our services and events.
12. API Gateway - we will use Oracle API Gateway service for managing our App API Calls.
13. Serverless - we will use Functions fo running particular flows in OCI and in the Web App. TBD..
14. Identity and Access Management- we will use Oracle IDCS for users self registration and group management for our Web App. 
15. Logging - we will use centralized logging such as: Loki/Elastic Search or others. 
*Optional - Ansible - for configuration. 

### Note - The mentioned tools are not a must, we can use multiple tools or others tools, if you have better suggestion feel free to add them ###

Each tool can be a different section in the workshop, 
and can have different tasks for learning how to use them and maintain the software development and release pipeline.

For participating in this project, please email me: daniel.kaganovitch@oracle.com 

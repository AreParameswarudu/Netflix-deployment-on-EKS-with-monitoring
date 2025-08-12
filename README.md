Netflix application:

<img width="900" height="629" alt="Screenshot 2025-08-11 230751" src="https://github.com/user-attachments/assets/7db829e1-e3e5-4943-9e58-66c8826c9580" />

Deployment pipeline:

<img width="900" height="139" alt="Screenshot 2025-08-11 230814" src="https://github.com/user-attachments/assets/0ded8e0d-acf3-4697-b99f-1d561e792e96" />


Grafana's dashboard:

<img width="900" height="750" alt="Screenshot 2025-08-12 014202" src="https://github.com/user-attachments/assets/a9f27b5e-7d96-4330-a91b-5c4e02e7565f" />

  
<img width="900" height="784" alt="Screenshot 2025-08-12 014222" src="https://github.com/user-attachments/assets/314323c8-3a46-4c0c-9a5b-440ff455aefc" />

  
<img width="900" height="328" alt="Screenshot 2025-08-12 014242" src="https://github.com/user-attachments/assets/acd886c1-d04a-46ed-b99b-cc5248c2bc53" />


## 💻 Situation:  
  A **Netflix prototype** application to be hosted.  
  Use of **k8s** pods for hosting and making it haighly available, resilient to increased load.  
  Needs to have a monitoring tools to be setup for **monitoring the k8s cluster**.  
  Deployment sholud have no manual interventions.  
  needs to have **Contineous file scans and quality checks and docker images scan**.  
		
## 🕵️‍♂️ Task:
  Application deployment, npm dependencies, quality checks.  
  Docker image creations, webhooks, CI and CD pipeline.  
  k8s cluster for hosting the application with deployment and services objects.  
  no manual interventions.  
  docker scout for image scanning.  
  monitoring tools to monitor k8s cluster.  

## 🏋️‍♂️ Actions:
  github for version control, and use of webhooks to listen for changes or pulls.  
  AWS eks for k8s cluster setup using terraform with jenkins pipelie with this pipelie is parameterized.  
  sonarqube scanner, owasp, docker scout for quality, file, image checks.  
  docker hub for pushing and pulling images.  
  jenkins for the pipeline (CI), EKS for CD.  
  Laod balancer, r53 for serving the application to the users.  
  Prometheus and grafana setups with helm charts in EKS cluster for realtime monitoring.  

## 😎 Result:
  Netflix application, with zero to no downtime.  
  Contineous interaction and Contineous Deployment.  
  pipelie with no manual interventions, with use of webhooks.  
  Terraform to setup eks cluster managed by amazon so no overhead of maintaining the cluster.  
  Realtime monitoring of the cluster with promrtheus and grafana.  

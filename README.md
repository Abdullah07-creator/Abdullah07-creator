<div align="center">

  # ⚡ Muhammad Abdullah
  ### **Undergraduate Computer Engineering Student @ UET Lahore | Junior Cloud & DevOps Engineer**

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@gmail.com)
  [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=about.me&logoColor=white)](https://YOUR_WEBSITE.com)

</div>

---

### 👨‍💻 About Me

An ambitious **Cloud & DevOps Engineer** and Computer Engineering student at **University of Engineering and Technology (UET), Lahore**. Dedicated to closing the gap between software engineering and cloud operations by automating infrastructure provisioning, enforcing supply-chain DevSecOps controls, and maintaining resilient, self-healing Kubernetes workloads.

* 🎓 **Degree:** Bachelor of Science in Computer Engineering — *UET Lahore*
* 🎯 **Core Focus:** Infrastructure-as-Code (IaC), GitOps Continuous Delivery, Observability, Multi-Cloud Reliability
* 💡 **Philosophy:** *"If you have to do it manually more than twice, write code to automate it."*

---

### 🛡 DevOps Toolchain & 3D Tech Stack

<p align="center">
  <!-- Container & Orchestration -->
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/docker.png" alt="Docker" width="55" height="55" title="Docker" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/kubernetes.png" alt="Kubernetes" width="55" height="55" title="Kubernetes" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/helm.png" alt="Helm" width="55" height="55" title="Helm" />
  &nbsp;&nbsp;
  <!-- Infrastructure as Code -->
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/terraform.png" alt="Terraform" width="55" height="55" title="Terraform" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/ansible.png" alt="Ansible" width="55" height="55" title="Ansible" />
  &nbsp;&nbsp;
  <!-- Cloud & CI/CD -->
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/amazon_web_services.png" alt="AWS" width="55" height="55" title="AWS" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/github_actions.png" alt="GitHub Actions" width="55" height="55" title="GitHub Actions" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/git.png" alt="Git" width="55" height="55" title="Git" />
  &nbsp;&nbsp;
  <!-- Monitoring & Linux -->
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/prometheus.png" alt="Prometheus" width="55" height="55" title="Prometheus" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/grafana.png" alt="Grafana" width="55" height="55" title="Grafana" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/linux.png" alt="Linux" width="55" height="55" title="Linux" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/main/icons/python.png" alt="Python" width="55" height="55" title="Python" />
</p>

---

### 🚀 High-Impact Engineering Projects

<details open>
<summary><b>1. GitOps Continuous Delivery with Kubernetes & ArgoCD</b></summary>
<br />

* **Tech Stack:** `Kubernetes (EKS/Minikube)` | `ArgoCD` | `Helm` | `Docker` | `GitHub Actions`
* **Architecture:** Packaged multi-service microservices into Helm charts. Established an automated GitHub Actions workflow to build, vulnerability-scan, and publish Docker images while dynamically pushing updated tag parameters to a GitOps configuration repository.
* **Key Outcome:** Deployed ArgoCD within the cluster to monitor configuration commits and automatically synchronize state, eliminating manual `kubectl` intervention and establishing self-healing cluster states.
</details>

<details>
<summary><b>2. Zero-Touch Infrastructure-as-Code (IaC) Provisioning</b></summary>
<br />

* **Tech Stack:** `Terraform` | `AWS (VPC, EKS, EC2, RDS, ALB)` | `Ansible` | `Terragrunt`
* **Architecture:** Designed modular Terraform configurations to provision production network topologies (Public/Private VPC subnets, NAT Gateways, Internet Gateways, Security Groups). Configured remote state storage using AWS S3 with DynamoDB state locking.
* **Key Outcome:** Used Ansible playbooks post-provisioning for server dependency setup, security hardening, and automated database deployments with zero AWS console clicks.
</details>

<details>
<summary><b>3. Automated DevSecOps CI/CD Pipeline</b></summary>
<br />

* **Tech Stack:** `GitHub Actions` | `SonarQube` | `Trivy` | `Snyk` | `Docker` | `Amazon ECR`
* **Architecture:** Engineered a security-first CI/CD pipeline triggered on pull requests. Integrated SonarQube for SAST code quality checks and Trivy/Snyk for vulnerability scanning on base container images and third-party dependencies.
* **Key Outcome:** Enforced automated gate-keeping rules that automatically block deployments whenever high or critical severity CVEs are detected, safeguarding supply chain security.
</details>

<details>
<summary><b>4. End-to-End Observability & Alerting Stack</b></summary>
<br />

* **Tech Stack:** `Prometheus` | `Grafana` | `Grafana Loki` | `Alertmanager` | `Slack Integration`
* **Architecture:** Deployed Prometheus to collect node-level infrastructure metrics alongside custom application-level HTTP error rates and latencies. Deployed Grafana Loki for unified cross-microservice log ingestion.
* **Key Outcome:** Designed dynamic Grafana dashboards and configured Alertmanager routing logic to trigger instant Slack notifications whenever key SLO thresholds are crossed.
</details>

<details>
<summary><b>5. Multi-Cloud Container Deployment & Traffic Routing</b></summary>
<br />

* **Tech Stack:** `AWS (EKS/RDS)` | `GCP (Cloud Run)` | `Docker` | `Terraform` | `NGINX Ingress`
* **Architecture:** Containerized stateless applications for cross-cloud deployment (primary on AWS EKS, secondary on GCP Cloud Run) connected to a centralized AWS RDS instance.
* **Key Outcome:** Automated traffic shifting via NGINX Ingress to validate zero-downtime canary releases, achieving cloud neutrality and fault tolerance.
</details>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&count_private=true" width="48%" alt="Muhammad's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide=html,css" width="48%" alt="Top Languages" />
</div>

<br />

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight" width="97%" alt="GitHub Streak" />
</div>

---

<div align="center">
  <sub>Designed with precision for Cloud & DevOps Operations • 2026</sub>
</div>


**Goal: filling the skill gaps that I think I have**

Today marks week 4 of my 2026 job hunt. While the general sentiment is futile, the effort remains. As a sysadmin / network engineer, lateral moves seem to be limited to MSPs and other service providers, or local businesses in need of internal IT. 

 The MSP world has given me value - namely in modernization, hardening, the ability to context switch, and rapid root-cause analysis. However that breadth and pace comes at the cost of the true depth I need to build actual senior level expertise.

I digress.

While I do find myself qualified for many positions, I'm noticing two main market trends for IT engineers:
1. Cloud infrastructure
2. Cloud IAM
3. Cloud MDM

Small to medium sized businesses, especially those that have been in business many decades  don't seem to have the use-cases for these skills. So I'll be applying some learning methods in the test/dev/homelab context.

## Cloud Infrastructure
#### Google Cloud Platform
#### Azure:
> [!NOTE]
> Azure AD Lab - Learning Plan
> 
> **Round 0 - GUI:** Full setup using Azure tenant admin
> 
> **Round 1 — Manual:** Every command entered by hand. Know what each line does before running it. VNet, subnet, NSG, static IP — build it yourself, understand it yourself.
> 
> **Round 2 — PS1 in ISE**: Run the scripts, follow along. Same knowledge, now automated. Repeatable process.
> 
> **Round 3 — Git clone + execute:** Pull from source, deploy, validate, tear down. Full IaC workflow.
> 
> **After all 3 rounds — layer on top:**
> 
> Entra Connect → sync ADLab.local to Entra ID tenant
> Azure Backup → protect a VM
> Azure Site Recovery → simulate on-prem migration
> 
> **Resources:**
> 
> Article: [https://happycamper84.medium.com/how-to-setup-an-ad-lab-in-azure-48a19ff5081b](https://happycamper84.medium.com/how-to-setup-an-ad-lab-in-azure-48a19ff5081b)
> GitHub: [https://github.com/EugeneBelford1995/Polished-Setup-a-simple-AD-lab-in-Azure-with-UI](https://github.com/EugeneBelford1995/Polished-Setup-a-simple-AD-lab-in-Azure-with-UI)

#### AWS
#### Kubernetes:

> [!NOTE]
> Linux-based technology built on kernel features (namespaces, chroot, cgroups)
> 	
> Cluster = 1 control plane VM + worker node VMs
> 	
> Worker nodes joined to control plane via kubeadm
> 	
> Kubelet runs on worker nodes, receives instructions from control plane
> 	
> Images built via Dockerfile, a text file containing docker instrcutions + Docker a linux service that build the container based on the dockerfile.
> 	
> The container is then pushed to and stored in registry (Docker Hub, AWS ECR, Azure ACR)
> 	
> Control plane schedules containers on worker nodes, tells them which image to pull from registry
> 
> Containerd on worker nodes actually runs the containers
> 	 
> Each container can contain it's own set of application dependencies and contains only what is needed for a single application to run.
> 	
> This is extremely lean compared to full VMs dedicated to a single app.

#### Docker
<u></u>
	Linux based
	Uses namespaces to isolate processes, file systems, and networking into containers
	Mainly used for building and shipping containers	
	
#### Terraform
## Cloud IAM
#### Okta

## Cloud MDM
#### JAMF
#### Kandji

Automation
Python
PowerShell


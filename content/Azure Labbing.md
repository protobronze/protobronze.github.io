---
Title: Azure HomeLab
---

We are IN. Azure free tenant aquired with $200 credit (thanks for the chump change Microsoft)

Interesting endeavor - probably far different than the experience I'll have in a production environment, my network was created alongside the first VM

This is because it took my an unreasonable amount of time to find a VM size that I could afford available in any of the regions. 

I ended up picking North South Africa, landing a measly  DS1 v2 size.

The reason I had to set up my network post VM provisioning is because I wasn't certain on the region I would get, and your network resources need to be regioned the same as your VMS.

So the process was provision VM > create VNET

I skipped the VM NSG because I wanted a subnet-wide NSG

I think in a production environment, I would virtualize a licensed firewall. But for the sake of a cloud homelab, a subnet NSG will do fine.

And that's it. At the end of this session I powered off the VM to avoid eating up my credit budget for usage rates, and next time I will be actually booting the thing up for real. Then will come promotion to DC, sync to Entra, and exploring other deeper infra subjects.

The goal is to spend most of this homelab in the Azure tenant admin designing and configuring the backend.

Once I get a handle on the admin, I'm tearing everything down and recreating it using powershell commands to get a deeper understanding of Microsoft IaC. 

After that, I'll rebuild a third time using .PS1 modules that pack all of the commands sequentially to deploy a template environment.

THEN, after I am confident with those PS1s, I'm going to see how I can automate further using GitHub. Not sure if I want to move to Terraform for that or stick with PowerShell. That is still a ways out!
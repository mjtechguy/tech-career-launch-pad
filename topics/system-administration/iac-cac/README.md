# Infrastructure-as-Code (IaC) and Configuration-as-Code (CaC)

IaC and CaC tend to go hand in hand and often are possible within the same tool.

In my (MJ) opinion and experience, Terraform and Ansible are really the front runners here. While they do have some overlap, I like to use Terraform for deploying all the infrastructure (VMs, DBs, cloud firewalls, etc) and Ansible for managing the configuration of the deployed assets (Linux/Windows servers, firewalls, Kubernetes clusters, etc).

Also, there is a system I am working on a course for that joins the 2 tools. I call it "Terransible". (Don't hate. I am a tech guy not a marketer. 😄) This uses Terraform to provision and track the state of all of the infrastructure and Ansible to provide the ongoing security and configuration management of the artifacts that are deployed. Be on the lookout for that.

## Infrastructure As Code (IaC)
Infrastructure as Code (IaC) is the managing and provisioning of infrastructure through code instead of through manual processes.

With IaC, configuration files are created that contain your infrastructure specifications, which makes it easier to edit and distribute configurations. It also ensures that you provision the same environment every time. By codifying and documenting your configuration specifications, IaC aids configuration management and helps you to avoid undocumented, ad-hoc configuration changes. [Source](https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac)

## Configuration As Code (CaC)

Configuration as code is a technique of controlling your program that promotes the use of code to describe configuration settings.

When it comes to building and deploying software, there is often a separation of concerns between the application’s source and the configuration of its server deployment.

Typically, the Ops team is responsible for developing the tools and configuration settings necessary to create and deploy your application across several server instances and environments.

Configuration as code promotes the idea of treating configuration settings the same way you would approach application code. This entails using version control to manage your setup settings. [Source](https://secpigeon.com/ultimate-guide-what-is-configuration-as-code-everything-to-know/)

## Intro to IaC and CaC

- What is Infrastructure as Code? - freeCodeCamp (blog): https://www.freecodecamp.org/news/what-is-infrastructure-as-code/

- What is Infrastructure as Code? - IBM Technology (9 Mins): https://www.youtube.com/watch?v=zWw2wuiKd5o

- Infrastructure as Code - Crash Course - freeCodeCamp (1+ Hours): https://www.youtube.com/watch?v=EtEb40LE5zQ&t=1s

- Ansible vs. Terraform: What's the difference? - IBM Technology (10 Mins): https://www.youtube.com/watch?v=rx4Uh3jv1cA

- What is Infrastructure as Code? Difference of Infrastructure as Code Tools - TechWorld with Nana (8 Mins): https://www.youtube.com/watch?v=POPP2WTJ8es

- What is Infrastructure As Code? What is Configuration As Code? - Michael Crilly (18 Mins): https://www.youtube.com/watch?v=wKZLhJh2234

- What is Configuration As Code - Michael Crilly (4 Mins): https://www.youtube.com/watch?v=Vh6qJ1RzvQk

- Infrastructure As Code + Configuration As Code = Automation! (Terraform, Ansible) - Michael Crilly (4 Mins): https://www.youtube.com/watch?v=vCBYTqCsb0g

- Chef vs Puppet vs Ansible vs SaltStack | Configuration Management Tools Comparison | Edureka (26 Mins): https://www.youtube.com/watch?v=OmRxKQHtDbY&t=585s

## Terraform Training Resources

HashiCorp Terraform is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage all of your infrastructure throughout its lifecycle. Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features. [Source](https://www.terraform.io/intro)

- Terraform in 100 Seconds - Fireship (2 Mins): https://www.youtube.com/watch?v=tomUWcQ0P3k

- Terraform Explained - IBM Technology (9 Mins): https://www.youtube.com/watch?v=HmxkYNv1ksg

- Terraform explained in 15 mins | Terraform Tutorial for Beginners- TechWorld with Nana (18 Mins): https://www.youtube.com/watch?v=l5k1ai_GBDE

- What is infrastructure as code? // Terraform Tutorial - The Digital Life (30 Mins):https://www.youtube.com/watch?v=fEIIxZUf4co

- Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code) - DevOps Directive (2.5+ Hours): https://www.youtube.com/watch?v=7xngnjfIlK4

- Terraform 101 - Crash Course - Warp9 (1 Hour): https://www.youtube.com/playlist?list=PLBzCxg00CgbqdfUYDAvU_3hfPRExxeEmm

- Terraform Course - Automate your AWS cloud infrastructure - freeCodeCamp (2.5 Hours): https://www.youtube.com/watch?v=SLB_c_ayRMo

- Learn Terraform with Azure by Building a Dev Environment – Full Course for Beginners - freeCodeCamp (1.5+ Hours): https://www.youtube.com/watch?v=V53AHWun17s

- Learn Terraform (and AWS) by Building a Dev Environment – Full Course for Beginners - freeCodeCamp (1.5+ Hours): https://www.youtube.com/watch?v=iRaai1IBlB0

- HashiCorp Terraform Associate Certification Course - Pass the Exam! - freeCodeCamp (13+ Hours): https://youtu.be/V4waklkBC38

- Build a Dev Environment with AWS and Terraform - Derek Morgan (~2 Hours): https://courses.morethancertified.com/p/rfp-terraform

- Build a Dev Environment with Azure and Terraform - Derek Morgan (~2 Hours): https://courses.morethancertified.com/p/rfp-terraform-azure

## Ansible Training Resources

Ansible® is an open sourceIT automation tool that automates provisioning, configuration management, application deployment, orchestration, and many other manual IT processes. Unlike more simplistic management tools, Ansible users (like system administrators, developers and architects) can use Ansible automation to install software, automate daily tasks, provision infrastructure, improve security and compliance, patch systems, and share automation across the entire organization.[Source](https://www.redhat.com/en/technologies/management/ansible/what-is-ansible)

- What is Ansible In Under 3 Minutes - Linux Academy (3 Mins):  https://www.youtube.com/watch?v=tWR1KXgEYxE

- What is Ansible - IBM Technology (11 Mins): https://www.youtube.com/watch?v=fHO1X93e4WA

- What is Ansible | Ansible Playbook explained | Ansible Tutorial for Beginners - TechWorld with Nana (17 Mins): https://www.youtube.com/watch?v=1id6ERvfozo

- you need to learn Ansible RIGHT NOW!! (Linux Automation) - NetworkChuck (21 Mins): https://www.youtube.com/watch?v=5hycyr-8EKs

- Getting Started with Ansible - Red Hat (52 Mins): https://youtu.be/MRoLVm6nTCU

- Just enough Ansible to be dangerous - Gourav Shah (1 Hour): https://www.udemy.com/course/just-enough-ansible/

- Getting Started with Ansible Navigator - Open Source Ops/Nikhil Jain (50 Mins): https://www.youtube.com/watch?v=SvI-90g4u9o

- Ansible Basics: An Automation Technical Overview - Red Hat Inc (2 Hours): https://www.udemy.com/course/ansible-basics-an-automation-technical-overview/

- Ansible Full Course | 34 Topics in 2 Hours | Ansible Tutorial for Beginners - TechWorld with Nana (2.5 Hours): https://www.youtube.com/watch?v=Wr8zAU-0uR4

- Full Ansible Tutorial for Beginners 2021 | Playbooks | Modules | Variables | Start Here - Pythoholic (2.5+ Hours): https://www.youtube.com/watch?v=MNGfPn0Yvs8

- Getting Started with Ansible - Learn Linux TV (5 Hours): https://www.youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70

- Automate EVERYTHING with Ansible! (Ansible for Beginners) - Techno Tim (18 Mins): https://www.youtube.com/watch?v=w9eCU4bGgjQ

- Simple automation for all your Linux servers with Ansible - The Digital Life (25 Mins): https://www.youtube.com/watch?v=uR1_hlHxvhc

- Ansible 101 - Jeff Geerling (15 Hours): https://www.youtube.com/playlist?list=PL2_OBreMn7FqZkvMYt6ATmgC0KAGGJNAN

- Introduction to Ansible for Network Engineers - Calvin Remsburg (2.5 Hours): https://youtu.be/zhgZbaqL3Rk

- Cisco IOS Automation with Ansible - Calvin Wallace (30 Mins): https://www.youtube.com/watch?v=wbVZkb8ocH4

- Ansible Network Automation - David Bombal (1 Hour): https://www.youtube.com/watch?v=2W_YE0fZs88

- Ansible Learning For Network Engineers: Network Automation tutorial with Cisco Examples - NetworkEvolution (7+ Hours): https://www.youtube.com/playlist?list=PLOocymQm7YWbrBP_UWeA4CGmsTKqj-OWL

## AWX

AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is one of the upstream projects for Red Hat Ansible Automation Platform.[Source](https://github.com/ansible/awx)

- Introduction to AWX - Open Source Ops (28 Mins): https://www.youtube.com/watch?v=mxaToXn_q4E

- Introduction to Automation with Ansible AWX, GitHub and Openstack - Sean Shuping (15 Mins): https://youtu.be/ubZrwI4SJQY

- AWX - Introduction to Custom Execution Environment - Open Source Ops (18 Mins): https://youtu.be/zi5EtEcBXHE

- AWX AND ANSIBLE TOWER / AUTOMATION PLATFORM - COMPREHENSIVE OVERVIEW TO RUN YOUR FIRST JOB! - The_Sudo (33 Mins): https://youtu.be/49x1jEliq5U

- Ansible 101 - Episode 10 - Ansible Tower and AWX - Jeff Geerling (1 Hour): https://youtu.be/iKmY4jEiy_A

- Getting started with AWX / Ansible Tower / Automation Controller - Karneliuk (1.5+ Hours): https://youtu.be/Ax30RFhI1I8

- Up and running with Ansible AWX / Tower - Calvin Remsburg (2.5+ Hours): https://youtu.be/mTllPoQQFjg

## Salt Stack Training Resources

The Salt system is a Python-based, open-source remote execution framework for configuration management, automation, provisioning, and orchestration.

Salt delivers a dynamic communication bus for infrastructure to leverage in:
- Remote execution.
- Configuration management.
- Automation and orchestration.

[Source](https://docs.saltproject.io/salt/user-guide/en/latest/topics/overview.html)

- Why SaltStack? - SaltProject (2 Mins): https://youtu.be/K_0k9-38ztk

- On The Spot - How Is SaltStack Different From Ansible? - PacketPushers (2 Mins): https://www.youtube.com/watch?v=ppu6K5Cp1Zo

- SaltStack: Basic Grains for Your Brain - Spooky Software (30 Mins): https://youtu.be/zXUaYhvy33E

- Getting Started with Salt Project - DevOps Clinic (1.5 Hours): https://www.youtube.com/playlist?list=PLzDaW424lWh7ZCdCVUhYvd38ArQarm6ul

- Learning SaltStack - LearnDevOps (8+ Hours): https://www.youtube.com/playlist?list=PLgGQIE0cGrkiDRmJ3YWBKlI2KuYfFvfzV

- SALT AIR powered by Salt Stack (behind the scenes on Salt) - SaltProject (3 Hours): https://www.youtube.com/playlist?list=PL9svBjLDUl_-yS-Nmlzom_dM81dmF1Ye7

- Managing Windows with SaltStack Config - Salt Project (41 Mins): https://youtu.be/PNgG_vXo8S8

- Building a Secure Enterprise with SaltStack SecOps - SaltProject (1 Hour): https://www.youtube.com/watch?v=CbxrAAUVVTs

- Introduction to DevOps with AWS Cloud and SaltStack Tool - SkillCurb (52 Mins): https://www.youtube.com/watch?v=orXTWmFP1WU

## Chef Training Resources

Chef is an automation company. Ever since it was founded in 2008, we have been bringing together developers and system administrators with our namesake product, Chef Infra. Over the years, what we mean by automation has expanded. Today, Chef has a complete automation solution for both infrastructure and applications that takes you all the way from development to production.[Source](https://docs.chef.io/platform_overview/)

- Chef Infra in 60 Seconds - Chef Software (1 Min): https://www.youtube.com/watch?v=tt9_aWiSW5M

- Chef InSpec in 60 Seconds - Chef Software (1 Min): https://www.youtube.com/watch?v=79tzn0LHwpM

- Learn How to Accelerate Your DevOps Journey with Chef in 60 Seconds - Chef Software (1 Min): https://www.youtube.com/watch?v=Ssy4d6dFkaU

- Chef Quickstart Series - Chef Software (33 Mins): https://www.youtube.com/playlist?list=PL11cZfNdwNyNYcpntVe6js-prb80LBZuc

- Learn Chef - Chef.io: https://learn.chef.io/



# Introduction-to-terraform

this repo has target explain terraform following what I learn on the:

[Introduction](https://hashicorp.wistia.com/medias/cb6o3i9l5w)

[Introduction to HashiCorp Terraform with Armon Dadgar
](https://www.youtube.com/watch?v=h970ZBgKINg)

![terraform](terraform.png)

## what is terraform

[Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.](https://www.terraform.io/intro/index.html)

## Terraform Goals

1) Unify the view of resources using infrastructure as code
2) Support the modern data center (IaaS, PaaS, SaaS)
3) Expose a way for individuals and teams to safely and predictably change infrastructure
4) Provide a Workflow as is technology agnostic
5) Manage anything with an API

## Terraform features

1) Provide a high-level  abstraction of infrastructure (IAC)
   1) IAC - infrastructure as code 
2) Allows for composition and combination
   1) abstraction 
3) Supports Parallel management of resources (graph,fast)
   1) terraform decide when to execute parallel action or sequential
4) Separates planning from execution (dry-run)
   1) terraform permit us a test preview using plan which gave us a reliable view of the future infrastructure

# Modern Data Stack Project

## Overview
 This is a side project done by Henrique Pegorari (call me Henri, pls) using various so-called 'modern data stack' tools, which are being used (or being massively adopted) by companies worldwide. I like open-source and I am eager to contribute to the community, so I plan to write articles and update this architecture regularly, as the technologies evolve and the market decides to use X or Y stack.

## Why we are building this the way we are building this
The main goal here is to build a robust but portable stack. Picture that stakeholder who pretty much only cares about saving money. We are the stakeholders, so fictionally, if we need to change the entire project to another cloud provider, our gig here should be cloud-agnostic at most, right? That's why I'm using a solution that can be built on-premise, on AWS, Azure, GCP, Alibaba or My-Cousin's-Cloud. In short, we need to guarantee maximum uptime and portability whilst saving tons of cash - and trust me, we are doing it because the tools selected here (90%) are open-source.

## Mock architecture
I'll improve it later when it becomes more 'definitive'. It's just a sketch, but that's the idea.

![Mock Architecture](<screenshots/mock_architecture.jpg>)

## Getting started

### AWS CLI
First of all, install AWS CLI if you don't have it, as we'll be using AWS EKS to deploy everything we build. Run `msiexec.exe` in PowerShell (Which provides the means to install, modify, and perform operations on Windows Installer from the command line):

`msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi`

Just hit the next button as many times as necessary and voilà. If for some reason you need to read the official AWS doc for other OS and other means of setting this up, you can check it out by clicking right [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html).

![AWS CLI Installed](<screenshots/aws_cli_completed.png>)

After installation, further configurations are needed to make sure you have the necessary permissions, which includes configuring IAM roles in the AWS console.



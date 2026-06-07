---
title: "Tech Stack"
date: "2022-01-02"
menu: "main"
description: "A page to describe my skillset"
---


My primary programming language for personal projects and automation is Python, but I also work heavily with Typescript. I tend to use Poetry for Python dependency management, and GitHub Actions for CI/CD.

At my current employer I work heavily with AWS and Terraform. Our platform is contained within a monorepo, using NX to manage service relationships and commands. GitLab CI is used for deployment, with pipelines generated using a pipeline generator, written in javascript.

I tend to containerise projects both personal and professional. Those containers have been ran in ECS, Lambda, and EKS, depending on the scale of the project, but I lean towards ECS for APIs and Lambda for automation.
---
layout: bt_wiki
title: Create Deployment
category: User Interface
publish: true
abstract: Create Deployment Guide
pageord: 100

terminology_deployment: http://getcloudify.org/guide/3.1/reference-terminology.html#deployment
terminology_workflow: http://getcloudify.org/guide/3.1/reference-terminology.html#workflow
blueprint_upload: http://getcloudify.org/guide/3.1/ui-blueprint-upload.html
terminology_link: reference-terminology.html
---
{%summary%} {{page.abstract}}{%endsummary%}

# Create Deployment
This guide will explain how to create new [deployment]({{page.terminology_deployment}}) using the user interface.<br/>
To Create new [deployment]({{page.terminology_deployment}}) go to the blueprint's screen, choose a blueprint (see [Upload Blueprint]({{page.blueprint_upload}})) and click on the button `Create Deployment`:<br/>
![Create deployment button](/guide/images/ui/ui-create-deployment.jpg)

A create deployment box will open.<br/>
Next, please fill out the deployment name and insert row params (optional), then click on `create` button:<br/>
![Create deployment box](/guide/images/ui/ui-create-deployment-box.jpg)

After creating the deployment, you will be move to the deployment page to follow the initialize stage:<br/>
![Deployment initialize](/guide/images/ui/ui-initialize-deployment.jpg)

Once the initialize complete, you will be able to start using the deployment and execute [workflow]({{page.terminology_workflow}}):<br/>
![Deployment ready to use](/guide/images/ui/ui-deployment-ready.jpg)
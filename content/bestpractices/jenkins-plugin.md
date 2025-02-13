---
title: "Jenkins Plugin"
description: "Introduction to Jenkins' Cloudify integration"
weight: 99
alwaysopen: false
---

{{%children style="h2" description="true"%}}

## Overview

![Jenkins Plugin]( /images/jenkins/jenkins-plugin.png )

The Jenkins Plugin for Cloudify, provided with version 5.0.5 onward, allows Jenkins authors
to embed Cloudify functions within jobs and pipelines.

### Plugin contents

The plugin provides:

* Discrete build steps for basic Cloudify functions (uploading / deleting blueprints, creating / deleting environments, workflow execution and so forth)
* A standard Jenkins _Build Wrapper_, a convenient enclosure for other build steps that sets up a Cloudify environment before the main steps and deletes the environment afterwards
* Build steps for integration with other provisioning tools:
    * Azure ARM
    * AWS CloudFormation
    * Terraform
    * Ansible
    
For more information, please refer to the plugin's page in Jenkins CI's website.

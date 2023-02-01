# Connecting Antimatter to a key held in Google Cloud KMS

## Overview

This guide will show you how to create a key in Google Cloud, create a service account with least-privilege access
to that key, and connect that service account to Antimatter running in a SaaS product

**Time to complete**: About 5 minutes

Click the **Start** button to move to the next step.

## Configuring the project

Ensure you are in the project you wish to create the key in. This can be done with

<walkthrough-project-setup></walkthrough-project-setup>

You will also need to enable the Cloud KMS API, if it is not already enabled:

<walkthrough-enable-apis apis="cloudkms.googleapis.com"></walkthrough-enable-apis>

## Pairing with the SaaS product

After you have selected a project, you can run the following command to automatically create a keyring, key and service account: 

```
./antimatter pair [PAIRING CODE]
```

If you would like to walk through the steps interactively and run the gcloud commands yourself, you can run this
command to begin the process:

```
./antimatter pair-interactive [PAIRING CODE]
```

# Connecting Antimatter to a key held in Google Cloud KMS

## Overview

This guide will show you how to create a key in Google Cloud, create a service account with least-privilege access
to that key, and connect that service account to Antimatter running in a SaaS product

**Time to complete**: About 5 minutes

Click the **Start** button to move to the next step.

## Configuring the project

Ensure you are in the project you wish to create the key in.

<walkthrough-project-setup></walkthrough-project-setup>

## Pairing with the SaaS product

### Fully automatic
To automatically create a keyring, key and service account in one step, you can run:

```sh
./antimatter pair PAIRING_CODE
```

### Interactive

If you would like to walk through the steps interactively and run the gcloud commands yourself, you can run this
command to begin a guided walkthrough:

```sh
./antimatter pair-interactive PAIRING_CODE
```

## Congratulations

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

You’re all set!

You can return to the Antimatter "Enable Encryption" screen where you clicked this Cloud Shell button

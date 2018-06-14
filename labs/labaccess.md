# PCF Environment Access

## Apps Manager UI
1. Navigate in a web browser to https://apps.sys.cfapp.org
2. Your login is your email address and password is your ADFS password
3. **IMPORTANT: We will be following the lab instructions on this page, not the getting started lab on run.pivotal.io**

## Target the Environment

If you haven't already, download the latest release of the [Cloud Foundry CLI](https://github.com/cloudfoundry/cli?mkt_tok=eyJpIjoiTXpoaE5UbGpNR0l3WldReCIsInQiOiIremNMNzlod0k5ekRGZDBOb0lXNTFYWGhhQU9LRnRKMW4rbnJIYWhCYjVUWk40dmVCUndKbFFRY1Q2SzF3T0VBd0FSQ0hHbGlsTlF4OVFQckNzYk9sZFpmcStxeE1VcmVOSis1VGJEcXZKUT0ifQ%3D%3D#installers-and-compressed-binaries) for your operating system and install it.

Set the API target for the CLI: (set appropriate end point to this lab environment "https://apps.sys.cfapp.org")

`$ cf api https://api.sys.cfapp.org`

Login to Pivotal Cloud Foundry:

`$ cf login`

Follow the prompts and login with the account from above.

## The Labs
[You are now ready to start Lab 1](../README.md#labs)

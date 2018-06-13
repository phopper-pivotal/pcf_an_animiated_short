# PCF Environment Access

## Apps Manager UI
. Navigate in a web browser to https://apps.sys.cfapp.org
. Your login is your email address and password is "w0rksh0p"
. *IMPORTANT: We will be following the lab instructions on this page, not the getting started lab on run.pivotal.io*

## Target the Environment

. If you haven't already, download the latest release of the Cloud Foundry CLI from https://github.com/cloudfoundry/cli/releases for your operating system and install it.

. Set the API target for the CLI: (set appropriate end point to this lab environment "https://apps.sys.cfapp.org")

+
----
$ cf api https://api.sys.cfapp.org
----

. Login to Pivotal Cloudfoundry:
+
----
$ cf login
----
+
. Follow the prompts and login with the account from above.

## The Labs
[You are now ready to start Lab 1](../README.md#labs)

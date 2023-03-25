# Accounts

It is the folder we run terraform from, all other folders in this repo are child modules we call from here.

Scenarion for deployment of entire set of environments for the product might looks like this:

Developers sandbox deployment:

  account/sandbox-john/terraform-remote-state
  account/sandbox-john/account
  account/sandbox-john/environment
  account/sandbox-john/app-hello-world-1
  account/sandbox-john/app-hello-world-2

  account/sandbox-john/terraform-remote-state
  account/sandbox-john/account
  account/sandbox-john/environment
  account/sandbox-john/app-hello-world-1
  account/sandbox-john/app-hello-world-2

Development environment deployment

  account/sandbox-john/terraform-remote-state
  account/sandbox-john/account
  account/sandbox-john/environment
  account/sandbox-john/app-hello-world-1
  account/sandbox-john/app-hello-world-2

Production environment deployment

  account/sandbox-john/terraform-remote-state
  account/sandbox-john/account
  account/sandbox-john/security-compliance
  account/sandbox-john/environment
  account/sandbox-john/app-hello-world-1
  account/sandbox-john/app-hello-world-2

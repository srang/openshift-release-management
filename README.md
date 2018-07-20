# OpenShift Release Management

## Goal
The goal of this project is to provide release management capabilities, specifically release sign-off and verification,
to OpenShift through opensource tools. A release manager should have a way to designate that an image has been approved
for release. Similarly, a team should have a way to define requirements for a release to happen (eg signature verification)

## Targeted Tools
* Automated Image Signatures: [image-scanning-signing-service](github.com/sabre1041/image-scanning-signing-service)
* GPG Key Management: [hashicorp-vault](github.com/hashicorp/vault)
* Release Orchestration: [jenkins](github.com/jenkinsci/jenkins)
* Policy Enforcement: [open-policy-agent](github.com/open-policy-agent/opa)
* Kubernetes Application Management: [operator-sdk](github.com/operator-framework/operator-sdk)
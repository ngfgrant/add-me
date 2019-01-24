# Add Me

This app provides a web interface for allowing GitHub users to add themselves
to a Team within your GitHub Organization.

It was created as many Open Source projects benefit from having a GitHub
Organization but users can not request to join they must be added.

# Project Goals

The initial goal is to allow users to deploy a AWS CloudFormation stack with
a Lambda function and a static Web UI with a URI that open source projects can
use to direct those wishing to be part of the organization to join.

## UX for user

1. URL to add-me page is displayed on GitHub org page.

2. User visits url and enters their GitHub username.

3. Lambda function attempts to add the User to that GitHub Organization.

4. GitHub will automatically send user an email with invitation to join.

## UX for project owners

1. Launch stack provided by this repository into their AWS account

2. Configure properties of the GitHub Org and Initial Team that user will join.

3. Paste link generated into a prominent place in website/GitHub.

# Contributing

See the [Contributing Guide](CONTRIBUTING.md)

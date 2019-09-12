# Artifactory Orb ![CircleCI status](https://circleci.com/gh/jfrog/artifactory-orb.svg "CircleCI status") [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/jfrog/artifactory)](https://circleci.com/orbs/registry/orb/jfrog/artifactory) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/jfrog/artifactory-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/orbs)

JFrog Artifactory orb created in partnership with CircleCI.

## Features
This orb supports the major features of the [JFrog CLI](https://jfrog.com/confluence/display/CLI/CLI+for+JFrog+Artifactory), including uploading artifacts, build integration (collecting environment info, etc.), and publishing Docker images.

To limit the permutations of variables, advanced users may pass a [File Spec](https://jfrog.com/confluence/display/CLI/CLI+for+JFrog+Artifactory#CLIforJFrogArtifactory-UsingFileSpecs).

### Examples
For usage examples, see the [src/examples](https://github.com/jfrog/artifactory-orb/tree/master/src/examples) directory or the [listing in the orb registry](https://circleci.com/orbs/registry/orb/jfrog/artifactory).

### Parameters/Configuration
See [orb registry listing](https://circleci.com/orbs/registry/orb/jfrog/artifactory) for complete parameters information.

## Contributing
[Issues](https://github.com/jfrog/artifactory-orb/issues) and [pull requests](https://github.com/jfrog/artifactory-orb/pulls) welcome!

This orb follows the general integration testing guidelines shown in [this example](https://github.com/CircleCI-Public/orb-tools-orb#examples) and outlined in the following blog posts:

- https://circleci.com/blog/creating-automated-build-test-and-deploy-workflows-for-orbs
- https://circleci.com/blog/creating-automated-build-test-and-deploy-workflows-for-orbs-part-2

### Orbs Authoring/Contributing
See [Using Orbs](https://circleci.com/docs/2.0/using-orbs) and [Creating Orbs](https://circleci.com/docs/2.0/creating-orbs) to get started.

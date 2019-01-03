# Project Name

The section after the title is where we say what this library, sample, or SDK does in a few sentences. Consider adding:

- Short description of use case + problem(s) solved. Consider the following ([from here](https://threadreaderapp.com/thread/921921604140937216.html )):
	- Have you described what it is and what the benefits are in a way a non-developer can understand?
	- If someone Googles to try to learn more about it, is this description easy to find?
	- Is this description easily skimmable? If someone looks at it for 6 seconds can they be convinced?
	- Do you compare your tool to other similar tools so people feel educated about pros/cons of yours?
	- If performance matters, do you have easy-to-skim benchmarks that include comparing it to other tools?
	- Do you have a demo? If it’s open source, are there well documented and easy to build samples/demos?
Have you talked with developers who may be interested to learn about why they haven’t tried it or don’t use it?
- Platform/language version supported
- Links to the project in other repos (npm, packagist, etc)
- Information about maintained and deprecated branches
- Repo status - maintained, deprecated, etc.
- Other resources:
	- https://github.com/coreinfrastructure/best-practices-badge/blob/master/doc/criteria.md
	- https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
	- https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46

Search-replace the org/repo in the badge images and links below.

**Note:** See individual language directories in this repo for technology-specific badges. 

[![CircleCI](https://img.shields.io/circleci/project/github/auth0/open-source-template.svg?style=flat-square)](https://circleci.com/gh/auth0/open-source-template/tree/master)
[![TravisCI](https://travis-ci.org/auth0/open-source-template.png)](https://travis-ci.org/auth0/open-source-template)
[![CodeCov](https://img.shields.io/codecov/c/github/auth0/open-source-template/v3.svg?style=flat-square)](https://codecov.io/github/auth0/open-source-template)
[![Coveralls](https://coveralls.io/repos/auth0/open-source-template/badge.svg?branch=master)](https://coveralls.io/r/auth0/open-source-template?branch=master)
[![Code Climate](https://img.shields.io/codeclimate/maintainability/auth0/open-source-template.svg)](https://codeclimate.com/github/auth0/open-source-template)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat)](https://opensource.org/licenses/MIT)

## Table of Contents

Make sure this is updated based on the sections included:

- [Documentation](#documentation)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Support + Feedback](#support--feedback)
- [Vulnerability Reporting](#vulnerability-reporting)
- [Thank You](#thank-you)
- [What is Auth0](#what-is-auth0)
- [License](#license)

## Documentation

This section should describe the documentation contained within this repo as well as links to other helpful pages. Full documentation for the library should not, ideally, be located in the repo README and must not be duplicated from somewhere else. If the README is being updated to adhere to these guidelines and the documentation only exists in the readme, consider moving it to a docs page or a Quickstart.

Consider adding:

- How to generate documentation in the project (if applicable)
- Links to Quickstarts and sample projects
- Links to any specific `.md` files in the repo
- Links to [auth0/docs](https://auth0.com/docs/)
- Links to [Auth0 blog posts](https://auth0.com/blog/tech/)
- Links to any helpful supporting information about the project
- Links to relevant Community posts (consider parsing and adding somewhere more easily accessible)

## Installation

This section should outline what is required to install and configure this project. Consider adding:

- Prerequisites for use
- Command line instructions using `bash` syntax:

```bash
npm install
composer install
```

- Links to information about package manager used
- Information about `.env` values needed (include an `example.env` file)
- Include different ways to install, indicate preferred method
- Include instructions on how to install older versions

## Getting Started

This section should include basic usage instructions that can be successfully completed after [Installation](#installation) above. This section should be a short introduction to how this library can be used, not a duplication of existing Quickstarts.

Consider adding:

- Working with the Authentication API
	- Basic login
	- Basic code exchange
	- Authorize redirect
	- Logout
- Working with the Management API
	- Perform a Client Credentials grant
	- Get Users by page
	- Get Clients by page
	- Get Connections by page
- Other common tasks
- Security recommendations
	- State validation
	- ID token verification

## Contributing

We appreciate feedback and contribution to this repo! Before you get started, please see the following:

- [Auth0's general contribution guidelines](https://github.com/auth0/open-source-template/blob/master/GENERAL-CONTRIBUTING.md)
- [Auth0's code of conduct guidelines](https://github.com/auth0/open-source-template/blob/master/CODE-OF-CONDUCT.md)
- [This repo's contribution guide](CONTRIBUTING.md)

## Support + Feedback

Include information on how to get support. Consider adding:

- Use [Issues](https://github.com/auth0/open-source-template/issues) for code-level support
- Use [Community](https://community.auth0.com/) for usage, questions, specific cases
- Link to other support forums and FAQs

## Vulnerability Reporting

Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## What is Auth0?

Auth0 helps you to easily:

- implement authentication with multiple identity providers, including social (e.g., Google, Facebook, Microsoft, LinkedIn, GitHub, Twitter, etc), or enterprise (e.g., Windows Azure AD, Google Apps, Active Directory, ADFS, SAML, etc.)
- log in users with username/password databases, passwordless, or multi-factor authentication
- link multiple user accounts together
- generate signed JSON Web Tokens to authorize your API calls and flow the user identity securely
- access demographics and analytics detailing how, when, and where users are logging in
- enrich user profiles from other data sources using customizable JavaScript rules

[Why Auth0?](https://auth0.com/why-auth0)

## Thank You! (optional)

Information on the dependencies used, if desired.

## License

Link to [LICENSE](LICENSE) doc. Typically MIT but can be different for a specific platform.

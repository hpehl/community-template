# Community Template

This repository is a collection of [recommended community standards](https://opensource.guide/). The recommendations are based on the [community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) from the GitHub documentation.

The recommendations are just that - recommendations. They should help you when you create a new repository or want to adjust the community standards of your existing repositories. None of the files are mandatory, but having as many of them as possible helps build a trusted community for your project. 

You can view how well you're doing with your repository by opening the community standards page of your repository: `https://github.org/<user|org>/<repository>/community` (see https://github.com/hal/console/community for an example). This page also links to further resources on enhancing your repository's community standards. 

## Code of Conduct

A code of conduct defines standards for how to engage in a community. It signals an inclusive environment that respects all contributions.

The code of conduct in this repository is adapted from the [Contributor Covenant](https://www.contributor-covenant.org), version 1.4,
available at https://www.contributor-covenant.org/version/1/4/code-of-conduct.html.

Another option is to adopt the [Red Hat Code of Conduct and Ethics](https://source.redhat.com/departments/legal/globallegalcompliance/compliance_folder/code_of_business_conduct_and_ethics_pdfpdf), which is only available if you have an account for the Source though. 

**Adopt:**

- Replace `__YOUR@EMAIL__` with your email.

**References:**

- https://opensource.guide/code-of-conduct/
- https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project
- https://www.contributor-covenant.org/version/1/4/code-of-conduct.html
- https://source.redhat.com/departments/legal/globallegalcompliance/compliance_folder/code_of_business_conduct_and_ethics_pdfpdf

## Code Owners

Pull requests often remain unprocessed for a long time because no developer feels responsible. When a repository contains a file called `CODEOWNERS`, pull requests are automatically assigned to teams or users.

A `CODEOWNERS` file uses a pattern that follows most of the same rules used in [`.gitignore`](https://git-scm.com/docs/gitignore#_pattern_format) files. With a few rules, new PRs are automatically assigned to a team or a user. The `CODEOWNERS` file in this repository shows some sample rules.

**Adopt:**

- Add your own rules. 

**References:**

- https://git-scm.com/docs/gitignore#_pattern_format
- https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

## Contributing

To help your project contributors do good work, you can add a file with contribution guidelines to your repository. When someone opens a pull request or creates an issue, they will see a link to that file. The link to the contributing guidelines also appears on your repository's contribute page: `https://github.com/<user|org>/<repository>/contribute`  

See https://github.com/hal/console/contribute for an example.

The contribution guide in this repository is an example that follows some best practices and should be appropriate for many projects. You may need to adjust it to your projects and requirements, though. 

**Adopt:**

- Replace `__REPOSITORY__` with your `<user|org>/<repository>` i.e. `hal/console` or `wildfly/core`
- Replace `__REPOSITORY_NAME__` with the name of your repository
- Add links for the issue tracker and chat. 

**References:**

- https://opensource.guide/how-to-contribute/
- https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors

## Issue & Pull Request Templates

With issue and pull request templates, you can customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository. While these templates are not required for all repositories, they can help enforce standards and avoid burdensome information retrieval.

This repository does not contain templates for issues and pull requests. Please read the official documentation and follow the guides to enable issue and pull request templates for your repository. 

**References:**

- https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates

## Security

You can give instructions on reporting a security vulnerability in your project by adding a security policy to your repository. If your repository contains a file called SECURITY.md, users who create an issue will see a link to your project's security policy.

This repository contains an example of a security policy excerpt from the official Red Hat security policy. 

**References:**

- https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository

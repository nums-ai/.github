# Nums AI community policies

<!-- SPDX-License-Identifier: Apache-2.0 -->

Reusable contribution, conduct, and security guidance for Nums AI open-source
projects, with issue and pull request templates ready for projects to adopt.

## Documents

| File | Purpose |
| --- | --- |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to propose and validate changes |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Community behavior and conduct reporting |
| [SECURITY.md](SECURITY.md) | Confidential vulnerability reporting |
| [Pull request template](.github/PULL_REQUEST_TEMPLATE.md) | Changes and validation |
| [Issue forms](.github/ISSUE_TEMPLATE) | Bug reports and feature requests |

## Organization defaults

This public `nums-ai/.github` repository provides organization defaults. GitHub
uses the files on its default branch for organization repositories that do not
define their own corresponding files. Publishing a GitHub release is not required
to activate these defaults.

Keep the community documents at the root and the templates at their current
paths. The `.github/ISSUE_TEMPLATE` directory is inside the repository named
`.github`; both uses of the name are intentional.

GitHub can show these defaults in public and private repositories. A project's
own community file takes precedence for that file type. If it defines any valid
issue template or configuration in `.github/ISSUE_TEMPLATE`, its entire local
issue-template set takes precedence over the organization defaults.

Default files are linked from this repository; they are not copied into project
Git history, clones, packages, or downloads. GitHub does not inherit `README`,
`LICENSE`, CI, or branch settings through this feature.
See [GitHub's default-file guidance](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## In each project

Projects without their own community files use the defaults automatically. Keep
their development instructions, CI, and code and documentation licenses in the
project. Each project must include its own `LICENSE` file.

Add policy links to the project's README:

```markdown
## Community

See our [contribution guide](https://github.com/nums-ai/.github/blob/main/CONTRIBUTING.md),
[Code of Conduct](https://github.com/nums-ai/.github/blob/main/CODE_OF_CONDUCT.md), and
[security reporting policy](https://github.com/nums-ai/.github/blob/main/SECURITY.md).
```

Keep shared files in the defaults repository for centralized updates. Add local
community files only when a project needs its own guidance, such as specific
development instructions or security coverage, and link the shared policy where
appropriate. Local copies take precedence over future default-file updates.

## Copying to other repositories

For repositories outside the organization or projects that need standalone
copies, copy the community documents to the project root and the templates to
their matching `.github` paths. Preserve the license notices and conduct
attribution. Include the Apache 2.0 license text and `NOTICE` with copied guides
and templates, using a separate policy license file if the project has a different
license. Keep `LICENSES/CC-BY-SA-4.0.txt` with the conduct document.

## Licensing

Company-authored guides, issue forms, and pull request templates in this
repository are licensed under [Apache 2.0](LICENSE). See [NOTICE](NOTICE).

[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) is adapted from Contributor Covenant 3.0
and remains licensed under [CC BY-SA 4.0](LICENSES/CC-BY-SA-4.0.txt), with its
source attribution and modification summary retained.

These licenses cover the policy files in this repository. Each adopting project
maintains its own licenses for its other content.

## Contacts

- Security and conduct reports: [trust@nums.world](mailto:trust@nums.world).
- Licensing and commercial enquiries: [contact@nums.world](mailto:contact@nums.world).

Project maintainers handle reports, monitor the reporting mailbox, and limit
access to people handling reports.

<!--
SPDX-FileCopyrightText: 2023 Eduardo Robles <edulix@sequentech.io>

SPDX-License-Identifier: AGPL-3.0-only
-->

# Meta

This is where Sequent puts:
- Reusable cross-project code.
- Templates, code, and documentation required for getting a repository working.
- Plan and schedule open source activities, like out Public Product Roadmap.

## Reusable Github Workflows

In [`.github/workflows`] you can find a list of [reusable Github Workflows], to
be easily reused in other Sequent repositories (or by anyone else really).

Workflows are designed to be easily usable within Sequent. [Variables] and
[secrets] required are typically defined and stored at Sequent
[organization level]. Typically any repository in our organization can access
them and you can find an example of how to call a sequent reusable workflow
in the bulletin-board repository call to [update-flake.yml action].

## List of project templates

TODO

## Sequent Public Product Roadmap

:sparkle: [Sequent public product roadmap]

:sparkle: [Sequent public feedback discussions]

The meta repository is for communicating Sequent's roadmap. Our product roadmap
is where you can learn about what features we're working on, what stage they're
in, and when we expect to bring them to you. Have any questions or comments
about items on the roadmap? Share your feedback via 
[Sequent public feedback discussions]. 

### Disclaimer 

Any statement in this repository that is not purely historical is considered a
forward-looking statement. Forward-looking statements included in this
repository are based on information available to Sequent as of the date they are
made, and Sequent assumes no obligation to update any forward-looking
statements. The forward-looking product roadmap does not represent a commitment,
guarantee, obligation or promise to deliver any product or feature, or to
deliver any product and feature by any particular date, and is intended to
outline the general development plans. Customers should not rely on this roadmap
to make any purchasing decision.

[`.github/workflows`]: https://github.com/sequentech/meta/blob/master/.github/workflows/
[reusable Github Workflows]: https://docs.github.com/en/actions/using-workflows/reusing-workflows#creating-a-reusable-workflow
[Variables]: https://docs.github.com/en/actions/learn-github-actions/variables
[secrets]: https://docs.github.com/en/actions/security-guides/encrypted-secrets
[organization level]: https://github.com/organizations/sequentech/settings/secrets/actions
[update-flake.yml action]: https://github.com/sequentech/bulletin-board/blob/main/.github/workflows/update-flake.yml
[Sequent public product roadmap]: https://github.com/orgs/sequentech/projects/2
[Sequent public feedback discussions]: https://github.com/sequentech/meta/discussions/1

# github-workflows-templates <!-- omit from toc -->

Here I define and share all the GH workflows I use across al my personal repositories.

- [Why?](#why)
- [Inspired](#inspired)

## Why?

1. **DRY:** [Don't repeat your self!](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) I am tired of defining the same workflows over and over again in different repositories.
2. **Standardization**: I want all my repositories to use the same CI/CD pipelines. I achieve that by calling the workflows located in here as `use: cangulo-actions/github-workflows-templates/.github/workflows/<workflow>.yml@main` in the consumer repository GH workflows.

## Inspired

Inspired by:

- [BretFisher/github-actions-templates](https://github.com/BretFisher/github-actions-templates)
- [Create GitHub Actions Templates - New Composite Actions Feature Explored](https://dev.to/n3wt0n/create-github-actions-templates-new-composite-actions-feature-4ibk)

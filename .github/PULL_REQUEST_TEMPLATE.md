<!--
  Your PR title must conform to the conventional commit spec:
  https://www.conventionalcommits.org/en/v1.0.0/

  <type>(<scope>)!: <description>

  * `type` = chore, enhancement, feat, fix, docs, revert
  * `!` = OPTIONAL: signals a breaking change
  * `scope` = Optional when `type` is "chore" or "docs"
  * `description` = short description of the change

Examples:

  * enhancement(file source): Add `sort` option to sort discovered files
  * feat(new source): Initial `statsd` source
  * fix(file source): Fix a bug discovering new files
  * chore(external docs): Clarify `batch_size` option
-->

## Summary

<!-- Please provide a brief summary about what this PR does.
This should help the reviewers give feedback faster and with higher quality. -->

## Change Type

- [ ] Bug fix
- [ ] New feature
- [ ] Non-functional (chore, refactoring, docs)
- [ ] Performance

## Is this a breaking change?

- [ ] Yes
- [ ] No

## How did you test this PR?

<!-- Please describe your testing plan here.
Providing this information upfront will facilitate a smoother review process. -->

## Does this PR include user facing changes?

- [ ] Yes. Please add a changelog fragment based on
  our [guidelines](https://github.com/vectordotdev/vector/blob/master/changelog.d/README.md).
- [ ] No. A maintainer will apply the "no-changelog" label to this PR.

## Checklist

- [ ] Our [CONTRIBUTING.md](https://github.com/vectordotdev/vrl/blob/main/CONTRIBUTING.md) is a good starting place.
- [ ] If this PR introduces changes to [LICENSE-3rdparty.csv](https://github.com/vectordotdev/vrl/blob/main/LICENSE-3rdparty.csv), please
  run `dd-rust-license-tool write` and commit the changes. More details [here](https://crates.io/crates/dd-rust-license-tool).
- [ ] For new VRL functions, please also create a sibling PR in Vector to document the new function.

<!-- Examples for the above:
  PR adding new VRL function: https://github.com/vectordotdev/vrl/pull/993
  PR adding documentation: https://github.com/vectordotdev/vector/pull/21142
  
  We are working towards improving this workflow.
-->

## References

<!-- Please list any issues closed by this PR. -->

<!--
- Closes: <issue link>
-->

<!-- Any other issues or PRs relevant to this PR? Feel free to list them here. -->

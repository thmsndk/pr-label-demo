# pr-label-demo

A test of automatic PR labels using [Multi Labeler](https://github.com/marketplace/actions/multi-labeler)

# What does it do?

- Newly created PR's will get `Status: waiting for review` applied
- Assigns `Scope: XXX` labels depending on edited code paths
- PR author can type /ready to set the `Status: waiting for review` label again
  - I've not found a way to remove `Status: waiting for author` yet when this comment happens.

# GitHub Action Templates
A repo with examples of GitHub actions in various scenarios. 

## GHA Explanations

### gha-debug.yml

The [gha-action.yml](./.github/workflows/gha-debug.yml) shows how all the available context can be dumped out to the console. This is useful for seeing what is available, and potentially what can be passed on as parameters, or even with tags. Full details on the [GitHub Contexts page](https://docs.github.com/en/actions/learn-github-actions/contexts). The only really interesting one is the GitHub context. See the action for how to access the context values in an action.

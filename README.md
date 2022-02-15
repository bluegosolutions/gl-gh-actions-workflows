# gl-gh-actions-workflows
Defines reusable [github actions](https://docs.github.com/en/actions) workflows.

A guide for the integration of reusable github actions can be found [here](https://docs.github.com/en/actions/using-workflows/reusing-workflows).

The reusable workflows can be found here `./.github/workflows`.

The following workflows are reusable:

- `increment-tag-version.yaml`\
Retrieves the latest tag of a repo and increments its patch number.\
The tag must be a semantic version number.


- `merge-pr.yaml`\
Merges automatically any pull request that was created by `dependabot[bot]`.


- `publish.yaml`\
Executes a `Makefile` located at the project's root by calling `make publish`.


- `scan.yaml`\
Executes a `Makefile` located at the project's root by calling `make scan`.


- `test.yaml`\
Executes a `Makefile` located at the project's root by calling `make`.

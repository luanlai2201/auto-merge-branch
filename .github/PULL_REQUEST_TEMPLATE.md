# Card/Issue

<!-- Fill this out. -->

# Pull request type

<!-- Please try to limit your pull request to one type, submit multiple pull requests if needed. -->

Please check the type of change your PR introduces:

- [ ] New feature
- [ ] Breaking change
- [ ] Bug fix
- [ ] Enhancement
- [ ] Documentation
- [ ] Internal
- [ ] Other (please describe)

# Description

<!-- Fill this out. -->

# Does this introduce a breaking change?

- [ ] Yes
- [ ] No

<!-- If this introduces a breaking change, please describe the impact and migration path for existing applications below. -->

#### Screenshot

<!-- Include an image of the most relevant user-facing change, if any. -->

# Checklist

- [ ] Update documentation
- [ ] Add changeset

# Changeset Guideline

- You can determine how to write a correct changeset based on the type of change below:

| Changes          | Description                                                                        | Bump type |
| ---------------- | ---------------------------------------------------------------------------------- | --------- |
| Breaking Changes | Release as a breaking change. This requires a migration guide.                     | major     |
| New Feature      | New feature. New props/behaviors/variants/states added to the components.          | minor     |
| Bug Fix          | Bug fix. This won't change the interface.                                          | patch     |
| Enhancement      | Improvement on UI / UX or internal implementation. This won't change the interface | patch     |
| Documentation    | Improvement / Update on the documentation.                                         | patch     |
| Internal         | Related to library build tool, library or internal change.                         | patch     |

If you don't want to include your changes on the change log, please commit an empty changeset.

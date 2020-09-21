# .github

This repository is for sharing org-wide Github metadata and workflow templates.

The source of truth for this content is: https://github.com/knative-sandbox/.github,
which is mirrored to "downstream" `.github` repositories (e.g. `knative/.github`)
automatically on a [cron](/.github/workflows/sync.yaml).

The workflow files under `workflow-templates/*.yaml` are automatically pulled into
"downstream" code repositories (e.g. `knative/serving`'s `.github/workflows`) via
a Pull Request opened each weekday, currently by the [knobots](https://github.com/mattmoor/knobots).

```yaml
# This file is automagically synced here from github.com/knative-sandbox/.github
# repo by knobots: https://github.com/mattmoor/knobots and will be overwritten.

```


# [Unmock CircleCI orb](https://circleci.com/orbs/registry/orb/unmock/unmock)

[![CircleCI](https://circleci.com/gh/unmock/unmock-orb.svg?style=svg)](https://circleci.com/gh/unmock/unmock-orb)

Use [Unmock](https://unmock.io) to power your CI/CD testing workflows.

See the [orb page](https://circleci.com/orbs/registry/orb/unmock/unmock) for documentation and examples.

## Development

List orbs for namespace `unmock`:

```bash
circleci orb list unmock
```

Display info for `unmock/unmock` orb:

```bash
circleci orb info unmock/unmock
```

Validate an orb:

```bash
circleci orb validate orb.yml
```

Publish a development version:

```bash
circleci orb publish orb.yml unmock/unmock@dev:0.0.X
```

Publish a production version:

```bash
circleci orb publish orb.yml unmock/unmock@0.0.x
git tag -a "v0.0.x" -m "v0.0.x"
git push origin v0.0.x
```

Alternatively, you can use `promote` command to promote a development version to a semantic release:

```bash
circleci orb publish promote unmock/unmock@dev:0.0.x patch
# Push git tags as above
```

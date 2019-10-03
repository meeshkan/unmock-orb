# unmock-orb

The unmock [CircleCI orb](https://circleci.com/orbs/registry/orb/unmock/unmock).

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

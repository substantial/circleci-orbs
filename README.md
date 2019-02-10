# Substantial orbs

CircleCI orbs for our projects.

## Orbs

### [substantial/yarn](https://circleci.com/orbs/registry/orb/substantial/yarn)

### [substantial/node-build](https://circleci.com/orbs/registry/orb/substantial/node-build)

## How to

### Validate

```bash
circleci orb validate yarn.yml
```

### Publish dev version

```bash
circleci orb publish yarn.yml substantial/yarn@dev
```

### Promote to live version

```bash
circleci orb publish promote substantial/yarn@dev patch
```

# Substantial orbs

CircleCI orbs for our projects.

## Validate

```bash
circleci orb validate yarn.yml
```

## Publish dev version

```bash
circleci orb publish yarn.yml substantial/yarn@dev
```

## Promote to live version

```bash
circleci orb publish promote substantial/yarn@dev patch
```

# Rollbar Orb [![CircleCI status](https://circleci.com/gh/lex111/rollbar-orb.svg "CircleCI status")](https://circleci.com/gh/lex111/rollbar-orb) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/lex111/rollbar/master/LICENSE)

CircleCI Orb for reporting deploys to Rollbar.

## Usage

```yaml
version: 2.1

orbs:
  rollbar: lex111/rollbar@x.y.z

workflows:
  notify_deploy:
    jobs:
      - rollbar/notify_deploy:
          project_environment: development
```


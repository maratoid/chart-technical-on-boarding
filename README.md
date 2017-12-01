# Chart for Technical On-boarding

## Configuration

The following tables lists the configurable parameters of the Technical On-boarding chart and their default values.

| Parameter                | Description                                     | Default                                                |
| ------------------------ | ----------------------------------------------- | ------------------------------------------------------ |
| `image           `       | FQDN repository/image name                      | `quay.io/samsung_cnct/technical-on-boarding-container` |
| `onboard.org`            | organization                                    | ` samsung-cnct`                                        |
| `onboard.repo`           | repo where new issues will be created           | `technical-on-boarding`                                |
| `onboard.clientId`       | github client id                                |  **Required**                                          |
| `onboard.clientSecret`   | github client secret                            |  **Required**                                          |

### GitLab Configuration

The following project level [GitLab secret variable](https://git.cnct.io/help/ci/variables/README.md#secret-variables)
is required:

  - `REGISTRY_PASSWORD`: Set as gitlab secret variable. The associated registry password. (corresponding quay.io robot token)

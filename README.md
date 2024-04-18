# Open edX nightly sandbox

This repository contains deployment scripts for the instance hosted at https://next-release.openedx.org.

See the deployment script [here](./.github/workflows/install.yml).

To trigger a deployment, hit the "Run workflow" button [here](https://github.com/edly-io/openedx-nightly-sandbox/actions/workflows/install.yml). Checking the "reset" box will effectively delete all data on the platform.

LMS accounts:
    - Student:
        - username: student
        - password: student
    - Staff user:
        - username: admin
        - password: admin

## License

The content of this repository is provided under the terms of the [MIT license](./LICENSE.txt).


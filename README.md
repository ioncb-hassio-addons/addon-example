# IonCB Home Assistant App: Example

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

Example app by Community Home Assistant Apps.

## About

This is an example app for Home Assistant. When started, it displays a
random quote every 5 seconds.

It shows off several features and structures like:

- Full blown GitHub repository.
- General Dockerfile structure and setup.
- The use of the `config.yaml` and `build.yaml` files.
- General structure on how to use S6 overlay with services.
- Basic usage of Bashio.
- Continuous integration and deployment using GitHub Actions.
- Deployment to the GitHub Container registry.
- Small use of the Bash function library in our base images.
- The use of Docker label schema.

[:books: Read the full app documentation][docs]

## Support

Got questions?

You could also [open an issue here][issue] GitHub.

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original setup of this repository is by [Jhon Coronel][jhoncb].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## We have got some Home Assistant Apps for you

Want some more functionality to your Home Assistant instance?

We have created multiple apps for Home Assistant. For a full list, check out
our [GitHub Repository][repository].

## License

MIT License

Copyright (c) 2017-2026 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/ioncb-hassio-addons/app-example.svg
[commits]: https://github.com/ioncb-hassio-addons/app-example/commits/main
[contributors]: https://github.com/ioncb-hassio-addons/app-example/graphs/contributors
[docs]: https://github.com/ioncb-hassio-addons/app-example/blob/main/example/DOCS.mdu=jhoncb
[jhoncb]: https://github.com/jhoncb
[github-actions-shield]: https://github.com/ioncb-hassio-addons/app-example/workflows/CI/badge.svg
[github-actions]: https://github.com/ioncb-hassio-addons/app-example/actions
[github-sponsors-shield]: https://jhoncb.dev/wp-content/uploads/2019/12/github_sponsor.png
[github-sponsors]: https://github.com/sponsors/jhoncb
[issue]: https://github.com/ioncb-hassio-addons/app-example/issues
[license-shield]: https://img.shields.io/github/license/ioncb-hassio-addons/app-example.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[releases-shield]: https://img.shields.io/github/release/ioncb-hassio-addons/app-example.svg
[releases]: https://github.com/ioncb-hassio-addons/app-example/releases
[repository]: https://github.com/ioncb-hassio-addons/repository

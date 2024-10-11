# New Fedora When?

[![See in action](https://img.shields.io/badge/see%20in%20action-click%20me-blue)][url]
[![pages-build-deployment](https://github.com/2zqa/new-fedora-when/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/2zqa/new-fedora-when/actions/workflows/pages/pages-build-deployment)

A simple website that shows the planned release date of Fedora releases. See it in action at [2zqa.github.io/new-fedora-when][url].

Powered by [new-fedora-when-worker].

## Running locally

Ensure the [new-fedora-when-worker] is running locally. See its readme file.

1. `git clone https://github.com/2zqa/new-fedora-when.git && cd new-fedora-when`
2. Run a local webserver in the current directory at port 8000, like with Python: `python -m http.server`, or with npx: `npx http-server -p 8000`

## License

New Fedora When? is licensed under the [CC BY 4.0](LICENSE) license.

[url]: https://2zqa.github.io/new-fedora-when/
[new-fedora-when-worker]: https://github.com/2zqa/new-fedora-when-worker

# Wellenplan Helm Charts

This repository provides the `wellenplan` [Helm](https://helm.sh) chart for [Wellenplan](https://wellenplan.io).

Please refer to the [Getting Started](https://www.wellenplan.io/guide/getting-started.html) docs for further infromation.

## Quick Start

```bash
helm repo add https://charts.wellenplan.io
helm install wellenplan wellenplan/wellenplan
```

## Development

This repository only hosts the Helm chart index itself. The code for the chart is in the main
repository at [`charts/wellenplan`](https://github.com/wellenplan/wellenplan/tree/main/charts/wellenplan).

Updating the chart index is also handled by [an action in the wellenplan repo](https://github.com/wellenplan/wellenplan/blob/main/.github/workflows/release.yaml).

The chart is considered a core component of Wellenplan and is versioned in sync with the main Wellenplan version.

## Contributing

Contributions are very welcome and can take any shape or form. Please
refer to our [contributing guidelines](https://github.com/wellenplan/.github/blob/main/CONTRIBUTING.md)
for more information.

## Code of Conduct

Wellenplan adheres to a [Code of Conduct](https://github.com/wellenplan/.github/blob/main/CODE_OF_CONDUCT.md).
The Code of Conduct is a guideline for how to conduct yourself in our
community. Any member who breaks the Code of Conduct may be banned and
their contributions will be removed.

## License

This application is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

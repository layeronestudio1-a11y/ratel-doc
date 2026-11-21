# ratel-doc

ratel-doc provides a dashboard for managing Kubernetes resources across multiple clusters from one place. It is intended for teams that need a single interface for routine Kubernetes resource management.

**This standalone project is based on `dotbalo/ratel-doc`.**

## Features

- Manage Kubernetes resources across multiple clusters.
- Provide a dashboard interface for Kubernetes administration.
- Group multi-cluster resource management in one application.
- Build the project with the Go toolchain.

## Installation

Clone the repository and build the binary:

```sh
git clone https://github.com/dotbalo/ratel-doc.git
cd ratel-doc
go build -o ratel-doc .
```

You can also install it with Go:

```sh
go install github.com/dotbalo/ratel-doc@latest
```

## Usage

Run the compiled program and inspect the available command-line options:

```sh
./ratel-doc --help
```

When running from a checkout:

```sh
go run . --help
```

Use the options shown by the program to configure its runtime environment.

## License

ratel-doc is licensed under the Apache License 2.0. This project is based on [dotbalo/ratel-doc](https://github.com/dotbalo/ratel-doc), which is also distributed under Apache-2.0. Preserve the original copyright and license notices when redistributing the project or derivative works.

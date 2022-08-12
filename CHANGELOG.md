# Change Log

Notable changes.

## August 2022

### [0.11.0]

- WIP on features v2:
	- Auto map old feature ids to OCI features. (https://github.com/devcontainers/cli/pull/100)

### [0.10.0]

- Implement optional default values in localEnv/containerEnv expansions. (https://github.com/devcontainers/cli/issues/50)
- Log version and install location at the end of `--help`. (https://github.com/devcontainers/cli/issues/114)
- WIP on features v2:
	- Update `direct-tarball` to follow spec. (https://github.com/devcontainers/cli/pull/105)
	- Add `features package` command. (https://github.com/devcontainers/cli/pull/93)
	- Fix cwd for building with local features. (https://github.com/devcontainers/cli/issues/116)

### [0.9.0]

- WIP on features v2:
	- Contributable features in OCI registries.

## July 2022

### [0.8.0]

- Build command: Support multiple --image-name parameters  (#61)
- WIP on features v2:
	- Contributable features.
	- `features test` command.

## June 2022

### [0.7.0]

- Multi-platform build support. (https://github.com/devcontainers/cli/pull/24)
- User-scoped tmp folder on Linux. (https://github.com/microsoft/vscode-remote-release/issues/2347)

## May 2022

### [0.6.0]

- Handle undefined context. (https://github.com/microsoft/vscode-remote-release/issues/6815)
- Avoid comment after ARG for Podman. (https://github.com/microsoft/vscode-remote-release/issues/6819)
- Update to vscode-dev-containers 0.238.1.

### [0.5.0]

- Update to vscode-dev-containers 0.238.0.

### [0.4.0]

- Merge user and features Dockerfile to simplify cache and multi-platform handling.
- Use PTY for `--log-format-json`.

### [0.3.0]

- BuildKit version check for `--build-context`.

### [0.2.0]

- Use single Dockerfile to build image for single container using BuildKit.

### [0.1.0]

- Initial version.
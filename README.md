> :warning: This project is currently **under heavy development and is not considered stable yet**. This means that there may be bugs or unexpected behavior, and we don't recommend using it in production.

# Scoop Bucket for Admiral

This is the official [Scoop](https://scoop.sh) bucket for [Admiral](https://admiral.io/) tools on Windows.

## Available Manifests

| Manifest  | Description                                  | License    |
| --------- | -------------------------------------------- | ---------- |
| `admiral` | Command-line client for the Admiral platform | Apache-2.0 |

> Only the `admiral` CLI is distributed via Scoop. The `admiral-server` (platform orchestrator server and web UI) is macOS/Linux only and is not available for Windows.

## Installation

First, add the bucket:

```powershell
scoop bucket add admiral-io https://github.com/admiral-io/scoop-bucket
```

Then install the CLI:

```powershell
scoop install admiral-io/admiral
```

Or in a single command without adding the bucket first:

```powershell
scoop install https://raw.githubusercontent.com/admiral-io/scoop-bucket/master/bucket/admiral.json
```

## Upgrading

```powershell
scoop update
scoop update admiral
```

## Uninstalling

```powershell
scoop uninstall admiral
```

## Supported Platforms

| OS      | Architecture |
| ------- | ------------ |
| Windows | x86_64       |
| Windows | arm64        |

## macOS and Linux

macOS and Linux users should install `admiral` (and `admiral-server`) via the [Homebrew tap](https://github.com/admiral-io/homebrew-tap):

```sh
brew install admiral-io/tap/admiral
brew install admiral-io/tap/admiral-server
```

## License

This bucket's metadata is licensed under Apache-2.0. See [LICENSE](LICENSE) for details. The `admiral` CLI itself is also Apache-2.0 licensed.

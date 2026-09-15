> :warning: This project is currently **under heavy development and is not considered stable yet**. This means that there may be bugs or unexpected behavior, and we don't recommend using it in production.

# Scoop Bucket for Admiral

This is the official [Scoop](https://scoop.sh) bucket for the [Admiral](https://admiral.io/) CLI on Windows.

## Available Manifests

| Manifest  | Description                                  | License    |
| --------- | -------------------------------------------- | ---------- |
| `admiral` | Command-line client for the Admiral platform | Apache-2.0 |

## Installation

```powershell
scoop bucket add admiral-io https://github.com/admiral-io/scoop-bucket
scoop install admiral-io/admiral
```

Or install directly from the manifest without adding the bucket:

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

To remove the bucket as well:

```powershell
scoop bucket rm admiral-io
```

## Supported Platforms

| OS      | Architecture |
| ------- | ------------ |
| Windows | x86_64       |
| Windows | arm64        |

## Other Install Methods

- **macOS and Linux:** install via the [Homebrew tap](https://github.com/admiral-io/homebrew-tap) with `brew install admiral-io/tap/admiral`.
- **Linux packages, Docker, and standalone binaries:** see the [admiral-cli releases](https://github.com/admiral-io/admiral-cli/releases).

The Admiral server is not distributed through this bucket.

## License

This bucket's metadata is licensed under Apache-2.0. See [LICENSE](LICENSE) for details. The `admiral` CLI itself is also Apache-2.0 licensed.

# randlee Scoop Bucket

A [Scoop](https://scoop.sh) bucket for [randlee](https://github.com/randlee)
packages.

## Add the bucket

Run this once:

```powershell
scoop bucket add randlee https://github.com/randlee/scoop-bucket
```

## Packages

Each command below installs the latest version currently available from this
bucket.

| Package | Description | Repository | Install |
| --- | --- | --- | --- |
| `atm` | Local agent-team mail CLI and daemon | [atm-core](https://github.com/randlee/atm-core) | `scoop install randlee/atm` |
| `sc-compose` | Template-composition CLI | [sc-compose](https://github.com/randlee/sc-compose) | `scoop install randlee/sc-compose` |
| `wyvern` | Native webview dialogs for CLI agents | [wyvern](https://github.com/randlee/wyvern) | `scoop install randlee/wyvern` |

## Updating

```powershell
scoop update
scoop update <package-name>
```

## Contributing

Manifest updates follow releases from their respective repositories. Report an
issue in the repository for the package concerned.

## License

Each package has its own license; see its repository for details.

# nur-packages

**[NUR](https://github.com/nix-community/NUR) packages of the [spot-go](https://github.com/spot-go) organization**

![Build and populate cache](https://github.com/spot-go/nur-packages/workflows/Build%20and%20populate%20cache/badge.svg)

## Packages

- `spot-go`: [spot-go](https://github.com/spot-go/spot-go), a Spotify terminal UI. Each spot-go release updates [pkgs/spot-go/default.nix](pkgs/spot-go/default.nix) with GoReleaser, so don't edit that file by hand.

## Usage

With NUR, the package is `nur.repos.spot-go.spot-go`. Without it:

```bash
nix run github:spot-go/nur-packages#spot-go
```

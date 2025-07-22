# Unamed-AT

<img src="https://media.tenor.com/MRCIli40TYoAAAAj/under-construction90s-90s.gif" alt="under construction" width="80" align="right"/>

A labler on AT-proto; the following will be changed soon

## Install

You can download a pre-built binary from the releases or you can use the following options

### Go

```bash
# Go
go install github.com/taciturnaxolotl/akami@latest
```

### Nix

```bash
# Direct installation with flakes enabled
nix profile install github:taciturnaxolotl/akami
```

For use in your own flake:

```nix
# In your flake.nix
{
  inputs.akami.url = "github:taciturnaxolotl/akami";

  outputs = { self, nixpkgs, akami, ... }: {
    # Access the package as:
    # akami.packages.${system}.default
  };
}
```

Written in go with [fang](https://github.com/charmbracelet/fang) and [cobra](https://github.com/spf13/cobra). If you have any suggestions or issues feel free to open an issue on my [tangled](https://tangled.sh/@dunkirk.sh/unamed-at) knot

<p align="center">
	<img src="https://raw.githubusercontent.com/taciturnaxolotl/carriage/master/.github/images/line-break.svg" />
</p>

<p align="center">
	<i><code>&copy 2025-present <a href="https://github.com/taciturnaxolotl">Kieran Klukas</a></code></i>
</p>

<p align="center">
	<a href="https://github.com/taciturnaxolotl/unamed-at/blob/main/LICENSE.md"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>

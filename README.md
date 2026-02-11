<div align="center">
  <img src="https://github.com/sxyazi/yazi/blob/main/assets/logo.png?raw=true" alt="Yazi logo" width="20%">
</div>

<h3 align="center">
  Gruvbox Light Hard flavor for <a href="https://github.com/sxyazi/yazi">Yazi</a>
</h3>

This flavor targets the Gruvbox Light Hard palette, tuned for Yazi UI contrast and readability.

## Installation

```sh
ya pkg add viddrobnic/gruvbox-light-hard
```

## Usage

Set it as your light flavor in `theme.toml`:

```toml
[flavor]
light = "gruvbox-light-hard"
```

If you also use a dark flavor, keep both keys:

```toml
[flavor]
light = "gruvbox-light-hard"
dark = "<your-dark-flavor>"
```

See the [Yazi flavor documentation](https://yazi-rs.github.io/docs/flavors/overview) for details.

## License

- Flavor files are MIT licensed under [LICENSE](LICENSE).
- `tmtheme.xml` is MIT licensed under [LICENSE-tmtheme](LICENSE-tmtheme).

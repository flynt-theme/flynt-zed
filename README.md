# Flynt for Zed

Warm tones. Zero visual noise. - [Flynt](https://flynt-theme.github.io/flynt) for [Zed](https://zed.dev).

## Install

Search for **Flynt** in the extension marketplace: `zed: extensions` - search "Flynt" - Install.

Then open the theme picker (`zed: open theme selector`) and choose **Flynt Dark** or **Flynt Light**.

### Manual

```sh
mkdir -p ~/.config/zed/themes
cp themes/flynt-dark.json ~/.config/zed/themes/
cp themes/flynt-light.json ~/.config/zed/themes/
```

Then select it via `zed: open theme selector`.

## Building from source

Themes are generated from [`theme.json.tmpl`](theme.json.tmpl) using [strike](https://github.com/flynt-theme/flynt/tree/main/strike).

```sh
strike build theme.json.tmpl --out themes/
```

## License

MIT - [Flynt Theme](https://github.com/flynt-theme)

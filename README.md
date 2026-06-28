<br />

<p align="center">
  <h1 align="center">Flynt for Zed</h1>
</p>

<p align="center">Warm flint. Zero visual noise — <a href="https://flynt-theme.github.io/flynt">Flynt</a> for <a href="https://zed.dev">Zed</a> editor.</p>

<br />

## Install

### Extension marketplace (recommended)

Search **Flynt** in Zed's extension marketplace: `zed: extensions` → search "Flynt" → Install.

Then open the theme picker (`zed: open theme selector`) and choose **Flynt Dark** or **Flynt Light**.

### Manual

Copy the theme file into `~/.config/zed/themes/`:

```sh
mkdir -p ~/.config/zed/themes
cp themes/flynt-dark.json ~/.config/zed/themes/
cp themes/flynt-light.json ~/.config/zed/themes/
```

Then select it in Zed via `zed: open theme selector`.

## Variants

| Variant | File |
|---------|------|
| Dark | [`themes/flynt-dark.json`](themes/flynt-dark.json) |
| Light | [`themes/flynt-light.json`](themes/flynt-light.json) |

## Building from source

Themes are generated from [`theme.json.tmpl`](theme.json.tmpl) using [strike](https://github.com/flynt-theme/strike).

```sh
strike build theme.json.tmpl --out themes/
```

## License

MIT - [Flynt Theme](https://github.com/flynt-theme)

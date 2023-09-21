# 📰 `suzuri`

Command-line Interface to sumi.news

Who is Suzuri? Sumi Sakurasawa's dog.

## Usage

You can download the script and run it locally, but I'd recommend fetching and
running it from GitHub to ensure that you are always on the latest version:

```shell
bash <(curl -s "https://raw.githubusercontent.com/Fuwn/suzuri/main/suzuri")
```

> Hint: Alias this in your shell profile: `alias suzuri="bash <(curl -s "https://raw.githubusercontent.com/Fuwn/suzuri/main/suzuri")"`

### Token

Obtain your sumi.news token via the `s` cookie on sumi.news.

### `--help`

```text
usage: sumi token [folder]

positional arguments:
  token           sumi.news session token
  folder          sumi.news feed folder

environment variables:
  SUZURI_TOKEN    substitution for token
  SUZURI_FOLDER   substitution for folder
  SUZURI_REVERSE  reverse the output feed
  SUZURI_MINIMAL  output only linked titles
  SUZURI_RAW      output raw markdown
```

Optionally, omit the token and folder arguments and export the environment
variables `SUZURI_TOKEN` and `SUZURI_FOLDER`.

### Dependencies

- [curl](https://curl.se/)
- [pup](https://github.com/ericchiang/pup)
- [html2md](https://github.com/suntong/html2md)
- [glow](https://github.com/charmbracelet/glow)

### Cool Ideas

- Pipe it into [`gum`'s](https://github.com/charmbracelet/gum) `choose` subcommand
- Display the most recent feed item in your status-bar
- Echo out the most recent feed item when you start your shell

## Licence

This project is licensed with the [GNU General Public License v3.0](LICENSE).

# 📰 `suzuri`

Command-line Interface to sumi.news

Who is Suzuri? Sumi Sakurasawa's dog.

## Usage

You can download the script and run it locally, but I'd recommend fetching and
running it from GitHub to ensure that you are always on the latest version:

```shell
bash <(curl -s "https://raw.githubusercontent.com/Fuwn/suzuri/main/suzuri")
```

### Token

Obtain your sumi.news token via the `s` cookie on sumi.news.

### `--help`

```text
usage: sumi [token] [folder]

```

Optionally, omit the token and folder arguments and export the environment
variables `SUZURI_TOKEN` and `SUZURI_FOLDER`.

### Dependencies

- [curl](https://curl.se/)
- [pup](https://github.com/ericchiang/pup)
- [html2md](https://github.com/suntong/html2md)
- [glow](https://github.com/charmbracelet/glow)

## Licence

This project is licensed with the [GNU General Public License v3.0](LICENSE).

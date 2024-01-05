# gophernotes-cli

A basic Bash CLI that wraps the [gophernotes](https://github.com/gopherdata/gophernotes) container image.

It offers commands for starting & stopping the server container in detached mode, as well as retrieving the URL + token for the running Jupyter web interface.

## Usage

Requires Docker

1. Clone repo or download `gophernotes` file
1. `chmod +x gophernotes`
1. Move `gophernotes` to somehwhere on your `PATH`. e.g. `mv gophernotes /usr/local/bin/`
1. Run `gophernotes help` to verify it's working and receive usage instructions
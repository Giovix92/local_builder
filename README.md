# Local ROM builder

## General overview

This is just a simple script with the following functions:

- Builds whatever you put in there, given the variables at the `# Main variables` section
- Automatically sends&edit a Telegram message given `TELEGRAM_BOT_TOKEN` and `CHAT_ID`
- Automatically sideloads the generated zip file
- Includes a temporary fix for 6.x kernel

## Usage

Run in your terminal `bash build_auto --help` to see what it can do.

Make sure to define `TELEGRAM_BOT_TOKEN` and `CHAT_ID` beforehand in your environment!

## License

```text
#
# Copyright (C) 2023 Giovanni Gualtieri <giovix92@giovix92.com>
#
# SPDX-License-Identifier: Apache-2.0
#
```

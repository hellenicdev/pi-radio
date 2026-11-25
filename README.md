# Pi Radio

[![Live demo](https://img.shields.io/badge/demo-live-19336e?style=flat-square)](https://hellenicdev.eu/pi-radio/) [![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

A 24/7 internet radio station hosted on a Raspberry Pi 5.

**Live site:** <https://hellenicdev.eu/pi-radio/>

## Features

- One-tap play and pause
- Live status indicator (connecting, live, reconnecting)
- Automatic reconnect with exponential backoff if the stream drops
- Volume control that remembers your setting
- Lock-screen and media-key controls through the Media Session API

## Run locally

No build step. Serve the folder with any static server:

```sh
git clone https://github.com/hellenicdev/pi-radio.git
cd pi-radio
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Tech

- HTML5 `<audio>`, CSS3 and vanilla JavaScript
- Stream served from a Raspberry Pi 5

## License

MIT. See [LICENSE](LICENSE).

## Credits

Made by [HellenicDev](https://hellenicdev.eu). More projects at <https://hellenicdev.eu>.

If you enjoy it, you can support the work here:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S31XB030)

# JioTV Go 📺

JioTV Go, an exciting project that allows you to stream Live TV channels on the web and IPTV. It's a web wrapper around the JioTV Android app, utilizing the same API to fetch and stream channels.

Ready to dive in? Download the latest binary for your operating system from [here](https://github.com/rabilrbl/jiotv_go/releases/latest), and explore the [documentation](https://jiotv_go.rabil.me/) to start your JioTV Go adventure! 🚀

_Give us 🌟 on GitHub if you like this project!_

We have video tutorials for [Windows](https://youtu.be/BnNTYTSvVBc),  and [Android](https://youtu.be/ejiuml11g8o) users. Please watch them if you are unsure about the installation process.

## Features 🌟

- 📺 Stream Live TV channels, just like in the JioTV Android app.
- 🎬 M3U playlist support for IPTV.
- 🌐 Web interface for watching Live TV.
- 📅 EPG (Electronic Program Guide) support in compressed GZipped XML or JSON format.
- 🎥 Quality selection (Low, Medium, High) supported.
- ⚙️ Configurable port and host.
- 🔐 Authentication options using Jio ID/Number with password or Jio number with OTP.
- 📺 Additional Sony channels from SonyLiv for convenience.
- 👥 Support for multiple clients simultaneously.
- 🚀 Written in Go, ensuring it's fast, lightweight, and portable.
- 💻 Command-line interface for server management and self-update.
- 🔄 Background start and stop feature.

## Install steps 🌟

apt  install docker.io && apt  install docker-compose -y

git clone https://github.com/emishperraj/jiotv_go

cd jiotv_go

docker build -t jiotv_go:latest .

docker-compose -f docker-compose.yml up -d

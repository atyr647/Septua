# Septua

**Your AI dev team.** Seven specialists who plan, build, review and ship
software with you. You talk to them like you would to any team: they
suggest the work, you decide what happens.

This is where Septua is released. Its source is kept elsewhere.

## Download

**[The latest version](../../releases/latest)**.

### On an Android phone

Download `Septua-<version>.apk` on your phone.

1. Open the downloaded file. Android asks once to allow installing apps
   from your browser (or Files app): allow it.
2. Tap **Install**.

Septua tells you when a newer version is out (Settings > About) and
takes you here to get it. Installing it keeps everything you have.

### On a Linux computer (x86-64)

Download `Septua-<version>-linux-x86_64.tar.gz` from the same page, then:

    tar -xzf Septua-*-linux-x86_64.tar.gz
    cd septua
    ./install.sh

Septua is then in your applications menu (it installs into `~/.local`, no
root needed). It needs SDL2, curl, SQLite and git, which most desktops
have; on Ubuntu or Debian:
`sudo apt install libsdl2-2.0-0 libcurl4 libsqlite3-0 git`. Built on
Ubuntu 24.04.

On a computer, newer versions install from inside the app: Settings >
About > **Update to ...**, then **Restart now**. The app checks the
download's SHA-256 against this page's before using it.

Each release lists the SHA-256 of its downloads, if you'd like to check
them.

## Privacy

Septua has no servers of its own and collects nothing: see the
[privacy policy](PRIVACY.md).

## For the curious

- `latest.json` is what the app reads to know the latest version.
- Releases are published by this repository's workflow
  (`.github/workflows/publish.yml`) from an `upload/v<version>` branch,
  which it deletes when it's done.

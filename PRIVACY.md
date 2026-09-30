# Septua privacy policy

*Last updated: (date of publication)*

Septua ("the app") is made by (your name or company) ("we"). This policy
says what the app does with your information. In short: **we don't
collect it.** Septua has no servers of its own that receive your code,
chats or keys; the app talks directly to the services you connect.

## What stays on your device

- Your projects, chats, roadmaps and settings, in the app's private
  storage.
- The API key for each AI provider you connect, and your GitHub sign-in.
  On Android they are encrypted with a key Android keeps for the app
  alone; on a computer they are kept in its keyring. Each key is only
  ever sent to the service it belongs to, never to us or anyone else.
- Crash reports, which stay on the device. If you choose to share one,
  you decide where it goes.

## What the app sends, and to whom

The app sends data only to services you connect, only to do what you ask:

- **The AI provider you choose** (for example SiliconFlow, Baseten,
  OpenRouter, OpenAI or Anthropic): the messages you write to the team
  and the context the team needs (parts of your code, the task at hand),
  so the AI models can answer, and the photos and files you attach to a
  chat (a picture only to a model that can see pictures). They go only to the provider of the model
  that answers, and that provider bills your account. Its privacy policy
  applies to what it receives.
- **GitHub** (github.com): the app reads and changes the repositories you
  work on (branches, commits, pull requests, CI results), and keeps your
  workspace (projects, chats, roadmaps, and the photos and files you
  attach to chats) in a private repository in your own account so your
  devices share it. GitHub's privacy statement
  applies.
- **Notifications**: when the app is closed and another of your devices
  runs the team, the phone app checks your private sync repository on
  GitHub about every 15 minutes (with your own GitHub sign-in) for news,
  and shows it as notifications. Nothing goes anywhere else.
- **Update check (GitHub)**: copies of the app not installed from an app
  store ask Septua's public releases page on GitHub which version is the
  latest (a plain request for one small file; GitHub sees your IP
  address, as for any web page). No data about you or your use is sent.
- **Model catalog (models.dev)**: the app downloads the public catalog of
  AI models and their prices from models.dev, at most once a day (a plain
  request for one file; its host sees your IP address, as for any web
  page). Nothing about you is sent.

All of it travels encrypted (HTTPS), except to a provider you add yourself by an
address starting with http:// (a server on your own network, say).

## What we don't do

No analytics, no advertising, no tracking, no selling or sharing of data.
We can't see your code, chats or keys.

## Your control

- Delete the app's data (or uninstall it) to remove everything on the
  device.
- Your synced workspace is the private repository `septua-sync` (or
  `devteam-sync`) in your GitHub account: delete it there to remove it.
- Disconnect GitHub or remove an AI provider in Settings, or revoke Septua's access
  in your GitHub settings (Applications).

## Children

Septua is a tool for software developers and is not directed at children
under 13 (or the minimum age where you live).

## Changes

If this policy changes, the new version will be published here with a new
date.

## Contact

(your contact email)

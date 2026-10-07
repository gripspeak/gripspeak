# Gripspeak

**Hold-to-talk voice typing for the Steam Frame. On-device speech to text.**

Hold both grips, talk, let go: what you said types into Steam chat, the browser, the terminal or any desktop app on your Steam Frame. Speech recognition runs on the headset, so your voice never leaves it, and dictation works offline once activated.

> Gripspeak is a paid app ($9.99 on [itch.io](https://gripspeak.itch.io/gripspeak)) and is closed source. This repository holds its documentation, changelog and issue tracker, so bugs and ideas have a public home.

- **Get it:** https://gripspeak.itch.io/gripspeak
- **Setup guide:** https://gripspeak.com/setup
- **Website:** https://gripspeak.com
- **Support:** support@gripspeak.com, or [open an issue](../../issues/new/choose)

## What it does

- Hold both grips to dictate; a short phrase usually lands within about a second of letting go.
- Double-tap the grips for hands-free mode (up to 10 minutes), tap once to stop.
- Copy and paste on grip double-taps; Enter and Escape on stick flicks.
- Learns names you correct, and keeps your own dictionary of words.
- Optional AI cleanup through your own OpenRouter account, off by default. Only text is sent, never audio.
- English only for now. Runs on the Steam Frame (SteamOS); not on PC VR or Quest.

## Reporting a bug

Use **Issues → Bug report**. The most useful things to include: what you said or pressed, where you were typing (Steam chat, a browser, a desktop app), what happened, and your Gripspeak version (Settings → About). Please don't post your purchase link or license details in an issue; email those to support@gripspeak.com.

## Privacy, briefly

Audio is processed on the headset and never saved or sent. The app goes online to activate once, to check its license about once a day (a missed check changes nothing) and to look for signed updates. Full policy: https://gripspeak.com/privacy

## How it was made

Gripspeak is made by one developer, with help from an AI coding assistant, and every feature was tested on a real Frame. Speech recognition uses NVIDIA's Parakeet TDT 0.6B v2 (CC BY 4.0).

Gripspeak isn't affiliated with or endorsed by Valve. Steam, SteamVR and Steam Frame are trademarks of Valve Corporation.

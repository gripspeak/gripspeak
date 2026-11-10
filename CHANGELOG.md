# Changelog

Updates install themselves on the headset (or right away with Settings → Check for updates). Every update is signed.

## 0.3.1 · 2026-11-10
- Fixed: new installs stopped with "The speech model download is damaged."
- Fixed: a pop-up like "Misheard something?" could open Settings while you were clicking something else. A pop-up now opens only when you point at it and click.
- New: say "hyphen" between two words to join them. "VRC hyphen lead" types VRC-lead.

## 0.3.0 · 2026-10-31
- New: the setup tour has a little extra pizzazz.
- New: say "slash" to type a slash. "Slash help" types /help. "A slash B" types A/B.
- New: say version numbers. "Version one point one point three" types version 1.1.3. "V one point one point three" types v1.1.3.
- Fixed: a short reply like "yes" could turn into a phrase from your dictionary.
- Fixed: a made-up phrase could appear in front of a short sentence.
- Fixed: "Let's do one tomorrow" typed "Let's do 1 tomorrow".
- Fixed: "I'm" and "I'll" could lose their capital I.
- Dictionary names keep their "'s", like "Gripspeak's".
- Filler words, questions and spoken email addresses come out cleaner.
- Settings says when a dictionary phrase needs a "heard as" spelling.
- Losing the Steam display no longer stops Gripspeak.
- The updater no longer gets stuck on "downloading" or "installing".
- Closing the installer window partway through leaves nothing broken behind.
- A headset that isn't activated keeps trying to restore its license.
- Hidden control characters are never typed or copied.
- Gripspeak's Settings page can't be shown inside another website.
- The setup tour names your own button choices. Many small Settings fixes.

## 0.2.2 · 2026-10-30
- Fixed: the microphone could go silent after Steam restarted.
- Fixed: short replies like "yes" sometimes came out blank or wrong.
- Fixed: counting could turn into a phone number.
- Dictionary names come out right more often.
- Updates are signed and roll back safely if an install fails. The update notice also shows in desktop mode.
- What you dictate or copy stays out of the system's process list.
- Translation (new, optional): type what you say in another language. It needs an OpenRouter account.
- Settings: a long dictionary fades out, with a Show all button.

## 0.2.1 · 2026-10-20
- On the headset: copy in a window opened from VR, like Chromium, and paste in a desktop app like the terminal. It works the other way too.
- Phone numbers stay numbers when they sound like a dictionary word.
- Codes said one character at a time join up: "seven Z Q V nine two" types 7ZQV92.
- Times come out as numbers: "dinner at six thirty" types "dinner at 6:30".
- Street addresses: "one twenty three Main Street" types 123 Main Street.
- Letters said one by one join up: "an L L C" types "an LLC".
- Saved email addresses are found more often.
- A domain on its own keeps no period: "live.com" types live.com.
- Stick typing on Steam's keyboard no longer turns off stick flicks after the keyboard closes.

## 0.2.0 · 2026-10-14
- Hotkeys: a controller gesture presses keys the Steam keyboard doesn't have, like Ctrl+Z, Ctrl+T or F11. It can also type a phrase you use often, with an optional Enter after.
- Desktop apps get the right characters on any keyboard layout, and accented letters (é, ß, ñ) type as themselves.
- A lone word after a pause keeps its first sound (Gripspeak listens before SteamOS's noise filter).
- Typing with a stick on Steam's keyboard, including focus mode from the headset button, no longer sets off stick flicks.
- Email addresses said in a sentence are typed as addresses.
- Accidental repeats and restarted sentences are cleaned up; deliberate repeats stay.
- AI polish never drops your words: if it would, your own words are typed instead.
- Dictionary: newest words first, and a filter.
- "Didn't catch that" asks you to try again when a voice was heard but no words.
- Uninstall can also remove settings, dictionary and history.

## 0.1.10 · 2026-10-14
- Copy and paste in windows opened from VR (Gripspeak's settings, Chromium from the + list) no longer open Chromium's inspector.

## 0.1.9 · 2026-10-12
- The installer always opens its window and explains any problem, and says when it's updating rather than installing fresh.
- The setup tour has a Back button, fits any window, can't get stuck on the paste step, and stays free of pop-ups until it's done.
- Pasted download links activate reliably, even copied out of a message.
- Gripspeak recovers on its own when SteamVR restarts during a game.
- Saying "hyphen hyphen" types --, so "hyphen hyphen help" is --help.
- Settings says "You're up to date" after a check, and open pages refresh themselves after an update.

## 0.1.8 · 2026-10-07
- Fixes the speaker pops for good.

## 0.1.7 · 2026-10-07
- No more random pops from the speakers.

## 0.1.6 · 2026-10-07
- Fixes an occasional click at the start of a chime.

## 0.1.5 · 2026-10-06
- Pressing and letting go without saying anything no longer types stray words.

## 0.1.4 · 2026-10-06
- Chimes recover by themselves if the sound ever goes quiet.
- Double-tapping the grips for hands-free is easier to hit.

## 0.1.3 · 2026-10-05
- Your words, typed more like you meant them: say "slash" for /, and phone numbers come out as 555-212-3185.
- Gripspeak no longer learns words from a terminal's own screen after you send.

## 0.1.2 · 2026-10-04
- Stays fast when the headset is low on memory, and says so when a dictation is slow.
- Settings shows update progress.

## 0.1.1 · 2026-10-04
- Headset pop-ups, like the update notice, can be clicked with the laser.

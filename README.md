# Reflex

Reflex is a memory-reading assist overlay. This repository holds **only release files** — the actual source is not public and will not be.

---

## Ethics

ok one thing to get established is that this is of course not to be used for cheating and is only a example of how cheaters could cheat 👍

## About this project — and about AI

This project is what it is largely because of AI. Most of the code you're running was written, debugged, and rewritten with heavy AI assistance over a very short span of days. I won't pretend otherwise.

But I want to be clear about where I stand, because it matters:

**I don't like AI for what it is today.** I don't like what it's doing to programming as a whole, to the people whose jobs it's eating, or to the culture of pasting prompts and shipping broken nonsense under a name you can't be proud of. And yet, just because I dislike it doesn't mean it's not developing, and it doesn't mean I'm going to pretend it isn't actively speeding up workflows right now, on this project. It is. Denying that would be stupider than any shitty AI Slop.

**I also don't support vibe coders.** I have open contempt for people who generate code they cannot read, cannot debug, and cannot take responsibility for. That said, I understand the usage. I understand why people do it, the pace, the ease, or how cheap it can be and that's formed around the last few years of AI development. Understanding it doesn't mean I respect it.

There's a line between using AI as a tool and surrendering to it. This project does attempt to stay on the right side of that line. Read the code. Question the output. Ship what you know will work.

---

## Detection status

Reflex reads game memory and is **not detected as of this release**. That status is a snapshot, not a promise.

Detection is not permanent for anything in this category. Every game update, every anti-cheat patch, every antivirus signature update can flip it. The intent is for it to stay undetected, and so far it has — but if you need a guarantee, this category has none to sell. Expect the status to possibly change, and check back for a new release when that day comes.

---

## How to download — and keep it from getting deleted

Anti-virus and SmartScreen will treat Reflex like malware, because to them, it is: a native binary that reads another process's memory. A memory-reading overlay looks exactly like a cheat to an AV engine, because that's literally what it is.

**Important:** if you click the download link in a normal browser with real-time protection running, the file will be flagged and **deleted automatically** before you ever see it. That is normal and expected, not a broken download. Real-time protection is exactly what deletes it, so that's what you turn off first.

To actually get it:

1. **Turn off real-time protection temporarily**, so the file is allowed to download:
   - Windows Security → Virus & threat protection → **Manage settings** → turn off **Real-time protection** (toggle it off).
2. **Download the installer asset** from the Releases tab of this repository (the `reflex-*.exe` file). With real-time protection off, the download survives.
3. **Add an exclusion** so Windows leaves the file alone after you re-enable protection:
   - Windows Security → Virus & threat protection → **Manage settings** → **Exclusions** → **Add exclusion** → **Folder**
   - Point it at your **Downloads** folder (or wherever the installer is saved). If the file vanished anyway, check **Protection history → Restore** first, then add the exclusion.
4. **Turn real-time protection back on** — immediately. Downloads folder is covered, nothing to protect against.
5. Run the installer (if SmartScreen says *"Windows protected your PC"* → **More info → Run anyway**).
6. Add an exclusion for the install folder too: `%LOCALAPPDATA%\Reflex`.

The file is intentionally small; detection comes from AV heuristics seeing "small native exe that reads memory," not from anything hidden in the installer.

---

## Source / support

Source is closed and stays closed unless I deem that it should be open-source and free, and for support you can either reach out to me or get support in any future/current server or channel I have for this project.

if u are genuinely competent in reverse engineering then ill say this, please don't reverse this. reversing what ive made would be rlly annoying for both me and you, and i promise the amount of effort you will have to put in to at most get pseudo-code isnt worth it.

if you wanna go reverse smth go reverse a bigger project than mine (🌊, ⚡, etc) 👀

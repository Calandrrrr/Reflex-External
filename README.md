# Reflex External

Reflex is a Windows technology demonstration showing how external software can inspect a running application's state and automate input. It is provided for controlled research and educational testing. It is not intended to provide an unfair advantage in online games.

## Important Notice

- Using software that reads or changes another process can violate that application's terms and may result in account restrictions or bans.
- Reflex is not guaranteed to be undetected. Detection behavior can change at any time. However as of 2026/09/13 it is completely undetected and will not get you banned, do keep in mind that this can always change
- Antivirus and SmartScreen products may flag Reflex because it is currently unsigned and uses process inspection, memory access, and input automation.
- Do not disable security protections for software you do not trust. Verify that downloads come from this repository and compare the published SHA-256 hash.
- You are responsible for how you use this software. The authors are not liable for account action, data loss, or other damage.

## Install

1. Open the latest release on this repository.
2. Download `reflex-1.1.0.exe` and `update.manifest.signed`.
3. Verify the installer SHA-256 against the signed manifest or release notes.
4. Run the installer and select **Install**.
5. Reflex installs to `%LOCALAPPDATA%\Reflex` without administrator access.

6. (Optional) Go to Windows Security > Virus & Threat protection > Manage Settings > Add or Remove Exclusions and whitelist both the installer (wherever you put it, recommended to take out of downloads though) and the actual folder for Reflex itself at %appdata%\local\Reflex (Windows + R the type %appdata% and hit enter)

The installer also provides **Launch** and **Uninstall** controls.

## Current Release

Version: `1.1.0`

Installer SHA-256:

```text
bdbc1eedc17be7db733d60a486f59c746cb89b23d86fb7a8508027351747074e
```

This public repository contains release artifacts and documentation only. Product source and private signing material are not published here. Reflex for now and for the presumed future will stay closed-source and paid unless it is deemed that it should be made open-source and free.


AI was utilized in making this but Reflex is not vibe-coded slop, Reflex will never be as we value actual effort, and was made with genuine care and was thoroughly rewritten multiple times in order to get

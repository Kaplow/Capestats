# CapeStats

A small window that sits on top of **City of Heroes (Homecoming)** and shows your combat
numbers live: damage and DPS, damage taken, healing, accuracy, defeats, XP and influence per
hour, and a POWERS view with every power - and every proc you fire, under the power that fired it.
Save a toon's numbers and compare builds side by side, or share them with friends.

## Download

**[Get the latest version](https://github.com/Kaplow/Capestats/releases/latest)**

- **CapeStats-x.x-Windows.zip** - recommended. Unzip it and double-click `CapeStats.exe`.
  Nothing else to install.
- **CapeStats-x.x-Python.zip** - the same program without the .exe, for people who already
  have Python 3 from python.org. Double-click `capestats.pyw`.

Full setup (about 5 minutes) is in **START HERE.txt** inside the zip. In short:

1. In game: Options > Windows > Chat > **Log Chat: Enabled**.
2. Put the combat channels in a chat tab (Damage Inflicted, Damage Received, Hit Rolls,
   Healing Delivered/Received, Rewards, and the Pet ones).
3. Use **Borderless** or **Windowed** so CapeStats can stay on top.

Windows may say "Windows protected your PC" the first time, because CapeStats isn't
code-signed. Click **More info > Run anyway**.

## Updates

CapeStats checks this page for a new version when it starts (at most twice a day). When
one is out, a gold **UPDATE** button appears - one click downloads it, checks it against
the release's checksum, keeps a backup of your old version and restarts. Your settings
and saved toons stay. You can turn the check off in the menu.

## Is it safe?

- CapeStats only **reads** the chat log file the game saves. It never touches the game.
- The only time it goes online is the update check above. It sends no stats, toon names or
  anything about you.
- The whole program is `capestats.pyw` - plain Python you can read.

## Support

CapeStats is free, and every feature stays free. If it helps you, you can leave a tip on
[Ko-fi](https://ko-fi.com/kaplow026426).

---

CapeStats is an independent, fan-made tool. It is not affiliated with or endorsed by
NCSOFT, NC Interactive, Homecoming, or the HeroStats project.
City of Heroes is a registered trademark of NCSOFT Corporation.

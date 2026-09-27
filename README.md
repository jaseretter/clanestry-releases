# Clanestry

**Evidence-first family history research, for Windows.**

This page is where you download Clanestry. It holds the installers only; the app's source code is kept privately.

**[⬇ Download the latest version](https://github.com/jaseretter/clanestry-releases/releases/latest)**

---

## What Clanestry is

Most family tree programs ask you to type in facts. Clanestry asks you to show your working.

- **Sources** are the records you found: a birth certificate, a census page, a headstone photo, a letter from an aunt.
- **Evidence** is what a source actually says.
- **Claims** are the conclusions you draw, such as "Mary Smith was born in 1872 in Dunedin". Each claim is linked to the evidence that supports or contradicts it, and carries a confidence level: *confirmed*, *likely*, *possible*, *unknown* or *disproved*.

The family tree, timelines and reports are built from those claims. So when two records disagree, both stay on file, you can see why you believe what you believe, and anyone you share the research with can check it.

Everything stays on your own computer. There is no account to create and nothing is uploaded unless you choose to.

## What it can do

- **Family tree, people and biographies**, generated from your claims, with "possible" relationships shown differently from proven ones.
- **Import and export GEDCOM**, the standard file format used by Ancestry, FamilySearch, MyHeritage, Legacy, RootsMagic and others. Bring in an existing tree, see a preview first, and export your research back out (GEDCOM 5.5.1).
- **Research board**: a board of open questions and leads, from first idea to proven or ruled out. Drag cards between columns as the research moves along.
- **Life timeline** for each person, which flags dates that can't all be true (an event dated after someone died, for example).
- **Photos**, attached to people and events and kept with your research.
- **Places map**, showing where your family's events happened (uses OpenStreetMap, so it needs an internet connection).
- **Printable reports**: family tree, family group sheet and biography, printed or saved as PDF.
- **Search** across people, sources, places and evidence (press **Ctrl+K**).
- **Duplicate finder**: after importing a tree, the same person can appear twice. Clanestry finds likely pairs, lets you compare them side by side and merge them. A merge keeps every claim and piece of evidence, and can be undone.
- **Research assistant** (optional): ask an AI to read a document or suggest leads. Use your own API key for Claude, ChatGPT or Gemini, or copy and paste to the Claude app or Microsoft Copilot. Anything the assistant suggests arrives as a draft for you to check, never as a fact.
- **Backup and restore** to a single file you can keep on a USB stick or in cloud storage.
- **Automatic updates**, which always ask first.
- **Help, a short tour and keyboard shortcuts** (press **F1** for help, **Ctrl+/** for the shortcut list), plus light and dark themes.

## Installing

You need a Windows 10 or 11 PC (64-bit).

1. Go to the **[latest release](https://github.com/jaseretter/clanestry-releases/releases/latest)**.
2. Under **Assets**, download `Clanestry-Setup-<version>.exe`.
3. Open the downloaded file.
4. **Windows will probably show a blue "Windows protected your PC" box.** This is because the app is not signed with a paid Microsoft certificate, not because anything is wrong. Click **More info**, then **Run anyway**.
   Your browser may also warn that the file "isn't commonly downloaded". In Edge, click **…** next to the download, then **Keep**, then **Show more** and **Keep anyway**.
5. Follow the installer. You can choose where to install it; the default is fine.
6. Open **Clanestry** from the Start menu. A short tour runs the first time.

To get going quickly, you can load a small example family from the welcome screen, or import a GEDCOM file you already have from **Data → Import & export**.

## Where your data lives

Your research is stored on your computer in:

```
%APPDATA%\FamilyHistoryResearch
```

(Paste that into the File Explorer address bar to open it.) It holds the database, the scans and photos you attach, and any safety backups.

If you installed an early version, your research was kept in a different folder. The first time a newer version opens, it moves everything into this one for you.

This folder is separate from the program. Updating or even uninstalling Clanestry does not delete it.

**Please make backups.** Use **Data → Backup & restore** to save everything into one file, and keep a copy somewhere other than this computer. The same screen restores a backup, which is also how you move your research to a new PC.

## Updating

Clanestry checks for a new version when it opens, and you can check any time from **Settings → Updates**. It always asks before downloading, and again before installing. Before it installs, it saves a safety backup of your research to `%APPDATA%\FamilyHistoryResearch\backups`, then closes, updates and reopens.

You can turn the automatic check off in Settings. You can also update by hand: download the newest installer from the [releases page](https://github.com/jaseretter/clanestry-releases/releases) and run it over the top of the old one. Your research is kept.

## Uninstalling

Use **Settings → Apps → Installed apps** in Windows, find Clanestry and choose **Uninstall**. Your research folder is left in place; delete `%APPDATA%\FamilyHistoryResearch` yourself if you really want it gone (make a backup first).

## Questions and problems

Clanestry is a family history project by Jason Retter. Clanestry is a working name and may change in a future version; your data won't be affected.

If something goes wrong or you have an idea, get in touch with Jason.

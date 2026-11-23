# Rezoin

Rezoin suggests catalogue types for photographs of ancient coins: Roman (RIC, RPC, RRC) and Greek and Hellenistic
(Price, SC, PCO, AGCO, BIGR, LCO, Corpus Nummorum, IRIS). Version 1.0, for Mac and Windows.

**The easiest way to download it is the download page: [rezaramji.com/rezoin](https://rezaramji.com/rezoin/).**
It has one button per download: each edition, for Mac or for Windows. The steps below are for downloading from GitHub directly.

## Which one do I want?

| | Rezoin Lite | Rezoin |
|---|---|---|
| What it does | Suggests coin types for your photos | The same, plus catalogue search and export to spreadsheet and labels |
| Reference photos | Loaded from each catalogue's website when you click | The same; a local copy of the RIC and RPC photos (about 15 GB) is optional, in Settings |
| Download size | about 1.3 GB | about 1.3 GB |

Each edition has a Mac download and a Windows download, and comes with test coins to try it on.
The Mac version needs Apple silicon (M1 or later) and macOS 12 or later; the Windows version needs 64-bit Windows 10
or 11.

## How to download from GitHub

You do not need a GitHub account.

1. On this page, find **Releases** in the right-hand column (on a phone, scroll down) and click the newest one.
   Or go straight to [the latest release](https://github.com/Zed-Rez/rezoin/releases/latest).
2. Scroll down to **Assets**. If the list is folded shut, click **Assets** to open it.
3. Click the one you want: **Rezoin-Lite-…-Mac.zip**, **Rezoin-Lite-…-Windows.zip**, **Rezoin-…-Mac.zip** or
   **Rezoin-…-Windows.zip**. The download starts in your browser.
4. Ignore the two files called **Source code (zip)** and **Source code (tar.gz)**. GitHub adds them to every release;
   they are not the app.

Do not use the green **Code** button at the top of this page either: it downloads this page's text, not the app.

## Opening it

**Mac**
1. Double-click the downloaded zip. It makes a folder.
2. Open the folder and double-click the app.
3. The first time, macOS says it "could not verify" the app. Click **Done**, then open
   **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to Rezoin, and confirm.
   You only do this once.

**Windows**
1. Right-click the downloaded zip and choose **Extract All…**, then **Extract**. It makes a folder.
   (Opening the zip without extracting it will not work.)
2. Open the folder, then the **Windows** folder, and double-click the .exe.
3. If you see "Windows protected your PC", click **More info**, then **Run anyway**.
4. If Windows says a .dll file is missing, run **vc_redist.x64.exe** from the same folder, then try again.

Keep the folder together: the app needs the files beside it.

## Reference photos

When a type has no reference photo on your computer, Rezoin shows a button that loads one from the catalogue's
website. To keep a local copy instead, tick **Keep a local copy of the reference photos** in Settings: Rezoin then
downloads the RIC and RPC photos (about 15 GB), one catalogue volume at a time, into its own folder. A line in the
bottom-right corner shows how far it has got. If you quit, it carries on where it stopped the next time it opens.

The volumes are also in the **Rezoin reference photos** release, for a computer without a fast connection: unzip each
and move the folder it makes (such as **Rezoin photos 06 RIC IV**) anywhere inside the **Rezoin** folder.

## Updates

When a newer version is out, a small red dot appears in the bottom-right corner of the app.
Hover over it to see what changed; click it to open the download page.
Download the new version the same way and replace the old folder. Move the **Rezoin photos …** folders across so they are not downloaded again.

## Terms of use

- Research use only.
- Do not publish or monetize this software, its data or its model.
- Matches are a model's suggestions, not identifications: check every attribution against the catalogue.
- Provided as is, without warranty of any kind.

Until the accompanying paper is published, cite Rezoin as:

> Ramji, Reza (ORCID 0009-0007-1469-0670). 2026. Rezoin: identification of ancient coin types from photographs
> (version 1.0). Unpublished software, Princeton University. reza.ramji@gmail.com.

For corrections, please contact [Rezoin@rezaramji.com](mailto:Rezoin@rezaramji.com).

# K-Projects

A Windows launcher for independent projects, including Patchlines and Character Relay.

## Install

[Download the Windows x64 installer](https://github.com/Keo-Reinz/k-projects-downloads/releases/download/v0.1.0-beta.1/K-Projects-0.1.0-beta.1-windows-x64-setup.exe)

Open the EXE and choose an empty installation folder. Start menu shortcuts are included; Desktop shortcuts are optional. **Neither app is included.** Open a project's page and choose **Install** to download only that project.

No Node installation, developer tools or command files are needed. App windows use Microsoft WebView2, included with current Windows installations. The beta installer is unsigned and may prompt a Windows or antivirus reputation check.

## Updates and your data

Opening a shortcut checks this public GitHub release channel for launcher updates. Launcher program versions live in `Versions`; apps live in `Apps`; each app's saved data lives separately under `K-Projects Data/Apps`. Launcher settings and app registrations live under `K-Projects Data/Hub`.

Apps have their own update buttons and channels:

- [Patchlines downloads](https://github.com/Keo-Reinz/patchline-downloads/releases)
- [Character Relay downloads](https://github.com/Keo-Reinz/character-relay-downloads/releases)

Updates verify release checksums before replacing program files. Previous program versions are retained for recovery. Quit an app before updating it. Removing K-Projects through Windows Installed apps keeps the installed project folders and saved data. Keep those folders when reinstalling or moving an installation; do not delete them unless you intend to remove your data.

The launcher contacts GitHub for release metadata and chosen downloads. Each installed app contacts its own content sources as described in its documentation. K-Projects does not upload saved libraries or Patchlines profiles.

Release ZIPs are launcher update payloads. Use the EXE installer for a first installation.

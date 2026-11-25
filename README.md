# Tecrys Vault releases

**Tecrys Vault** serves a team's vault of Tecrys files to Tecrys and Tecrys PDM: settings,
users, backups and the database (built-in, PostgreSQL or MariaDB). A new vault starts with a trial;
serving after it needs a licence, installed in the app. On Linux it comes as a `.tar.gz` and a
`.deb` package with a systemd service.

- **Download**: see [Releases](../../releases). Mac (Apple Silicon, macOS 14+): the `.dmg`;
  Windows: `windows-x64.exe` (most PCs) or `windows-arm64.exe` (ARM PCs).
- **First start**: Tecrys Vault is not signed by Apple or Microsoft. On the Mac open System Settings ▸
  Privacy & Security ▸ Open Anyway; in Windows click More info ▸ Run anyway. Later versions arrive
  through *Check for Updates…* in the app and need no approval.
- Tecrys Vault is free to download; it is not open source.

**Ideas and problems**: [open an issue](../../issues/new/choose) (Suggest a feature / Report a problem;
a free GitHub account is needed), or in the app: Help ▸ Suggest a Feature… / Report a Problem….

The `appcast-*.xml` files are the update feeds (signed with the Tecrys update key); don't edit them by hand.

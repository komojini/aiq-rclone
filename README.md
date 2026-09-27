# aiq-rclone

Personal OAuth client used by its owner's [rclone](https://rclone.org) setup to back up research files to the owner's own Google Drive.

- Single user: the repository owner. The app is not offered to anyone else.
- Google scope: `https://www.googleapis.com/auth/drive.file` only. The app can see and manage only the files it creates. It cannot read any other file in the Drive.
- No server, no database, and no analytics. Tokens stay on the owner's own machines.

Privacy policy: [PRIVACY.md](PRIVACY.md)

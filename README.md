# rclone-backup

Personal OAuth brand page for a private backup job. This is not a public service.

A server owned by luozn123 runs [rclone](https://rclone.org/) once a day to copy database backup files (PostgreSQL `pg_dump` output) to the owner's own Google Drive account. The app uses the `drive.file` scope: it can only access files that rclone itself created. Those files are visible in Google Drive like any other file.

No data is collected, stored, or shared by this app. See [PRIVACY.md](PRIVACY.md).

Contact: luozn123@gmail.com

# dropbak

Wrapper around rsync to allow syncing to a local dropbox directory, while filtering
on `.gitignore` files, kind of like [dbignore](https://github.com/tkonolige/dbignore)
except you are selectively syncing to a local dropbox directory, which then syncs with
dropbox as normal.

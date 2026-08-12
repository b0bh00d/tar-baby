# tar-baby
This repo contains a simple incremental backup/restore solution that is based on features in GNU tar.

This exists mainly because I needed something like this for the ARM64 platform.  Unfortunatly, the commercial options for that platform are limited to non-existent right now.  So, I wrote my own.

While I'd prefer the more advanced sector-bawsed approach that software like Acronis or Macrium Reflect use, but _something_ is better than just rsync'ing folders to an exterrnal drive.  With this at least I have a history.

Stored on github so I can pull the files directly into a live boot image environment.
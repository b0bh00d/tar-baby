# tar-baby
This repo contains a simple incremental backup/restore solution that is based on features in GNU tar.

This exists mainly because I needed something like it for the Linux ARM64 platform.  Unfortunatly, the commercial options for that platform are limited-to-non-existent right now.  Thus, I wrote my own.

While I'd prefer the more advanced sector-based approach that software like Acronis or Macrium Reflect use, this is at least better than just rsync'ing folders to an exterrnal drive; with this I have a history of changes.

Stored on github so I can pull the files directly into a live boot image environment.
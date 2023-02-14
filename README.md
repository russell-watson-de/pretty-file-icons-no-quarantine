# pretty-file-icons-no-quarantine
Is it possible to distribute mac files with custom icons, *without* them being placed in quarantine?


# Background

People with Ventura have started having problems downloading and opening fmWorkMate, because the files are being considered a security hazard and quarantined.

This happens only with the zip archive which is created on my mac computer and uploaded as part of the release.

This repo sets out to discover if 

- if this is due to the custom icon which is added to the file (via Finder > Information), or
- if it is because a file's extended attribute com.apple.quarantine is being transfered to the target computer within the zip file

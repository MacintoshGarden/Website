# File Integrity
We keep a hash for each and every file available in our archive, both for our own sake and for our users, You.  
Each file also comes with a GnuPG v2 signature as a means to verify a downloaded file.

## The Archive
We make sure to check the integrity of each file whenever there are file system actions involved, such as file writes (uploads) and copy / move file(s) from one location to the other. The archive is also periodically checked for data degradation and automatic restoration of damaged files on the off-chance that this occurs.

### Checksums
CRC32, MD5, SHA-1, SHA-256, SHA-512

The above should be available for each and every file inside the archive.

### More to come
Sometime soon
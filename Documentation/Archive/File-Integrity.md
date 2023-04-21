# File Integrity
We keep a hash for each and every file available in our archive, both for our own sake and for our users, You.  
Each file also comes with a GnuPG v2 signature as a means to verify a downloaded file.

## The Archive
We make sure to check the integrity of each file whenever there are file system actions involved, such as file writes (uploads) and copy / move file(s) from one location to the other. The archive is also periodically checked for data degradation and automatic restoration of damaged files on the off-chance that this occurs.

### Checksums
CRC32, MD5, SHA-1, SHA-256, SHA-512

Hash values for the above should be available for each and every file inside the archive, where CRC32 and MD5 are mostly available for those really old machines if verification is done on that end, and the rest to verify integrity on something more modern.  
For more information on verifying files using this method, check out the Guides.

### Digital Signatures
We digitally sign files without encrypting them, this is another means available so that you know where the file comes from and to verify that said file hasn't been tampered with.  
For more information on verifying files using this method, check out the Guides.
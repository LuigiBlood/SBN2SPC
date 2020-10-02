# SBN2SPC
Makes SPC files out of SBN files

# SBN file format

Basically it's blocks of data to upload to SPC700 RAM. They don't always have SBN as a file extension.

- 16-bit Block Size (if 0, then stop)
- 16-bit Address (to ARAM)
- Data Block
- Repeats until size = 0


This WILL not make working SPC files, they need additional work to start the song.

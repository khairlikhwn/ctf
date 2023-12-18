# Writeup for Wargames 2023 CTF

## Forensics

### Compromised
- https://zachwong02.github.io/post/wgmy2023-compromised/

`ll` to see file and directory details  
`tree` to see detailed directory  
`file` to see type of file
`strings` to see printable characters in file  
Perform `RDP Bitmap Cache` method using BMC Tools on github to parse cache  
Use `RDP Cache Stitcher` tool on github and arrange the picture to get flag

### SeeYou
- https://zachwong02.github.io/post/wgmy2023-seeyou/

Run a `tshark` query to find destination ports (30XXX)  
Run a `bash` script to remove the front parts (30000)  
Decode using `From Decimal` and `Render Image` on CyberChef to get flag
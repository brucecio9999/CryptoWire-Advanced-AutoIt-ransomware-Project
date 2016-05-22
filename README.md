CryptoWire - A advanced prof of concept ransomware project without a panel, to prevent skids from abusing it.

Compile : Requires autoit version: v3.3.14.2

Open source: http://ge.tt/1uQXLoa2

- Encryption algoritm is AES 256.

- The ransomware will encrypt all files stored on: 
Network drives, Network Shares, Usb Drives/sticks, Externals Disks, Internal Disks, Games (Steam), Onedrive, Dropbox, Google Drive (any cloud service that is running on the machine).

- It encrypts all files It's not extension based. The max file size limit is 30 mb, you can change that if you want.
The reason is to keep the performance high, while targetting most files.

- All shadow copies are being permanently deleted upon execution.

- The old non-encrypted files are being overwritten 10 times, and then deleted permanently. Only the encrypted files will be left back.
The recyclebin is being overwritten 10 times and deleted permanently as well.

- It will avoid heuristic detections by calculating different math algorithms.

- Persistence startup.

- Machine Domain check. If the victims pc is joined to a domain (company machine) the ransom will be 10x bigger (you can change that).

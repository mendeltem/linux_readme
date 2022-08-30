# Final Solution for Mounting Using the "cifs" Protocol
-----------------------------------------------------------------------------------------

-	Connect to the Linux power server of interest and login

- 	Move to your home directory on the power server (if not already in) by typing "cd ~"

-	Create directory “CSB_NeuroRad” in your home directory on the power server by typing "mkdir CSB_NeuroRad"

-	Mount Windows folder S:\AG\AG-CSB_NeuroRad from the Charite-IT-Geschaeftsbereichsspeicher on the power server by issueing

# Mount
`sudo mount -t cifs -o username="temuuleu",uid=temuuleu,gid=temuuleu //s-vfs24.charite.de/share$ /home/temuuleu/PROSCIS`


# Mac-OS-Password-Generator
- This applescript can be expanded to change Root's blank password to address the High Sierra vulnerability. 

# How to use
- Download generatepw.scpt to your mac and open with Script Editor

# How to use the new password for root
- Open terminal
- Type  passwd root
- For the old password leave blank and press enter
- For the new password, type the generated password and hit enter
- Retype the new password
- If your computer is vulnerable the password will be changed for the root account, otherwise you will receive an error message stating "authentication token failure". This means your root's account password is not blank or your mac is patched. 
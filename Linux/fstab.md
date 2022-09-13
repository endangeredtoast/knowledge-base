## Mount SMB/CIFS Share in Linux with /etc/ftab
```
//192.168.1.10/share 	/your/mountpoint 	cifs 	uid=0,credentials=/home/user/.smb,iocharset=utf8,vers=3.0,noperm 0 0
```
This requires a credential file placed at /home/user/.smb that looks like this:
```
username=yourusername
password=yourpassword
domain=yourdomain
```

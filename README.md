# Open Real Estate app for YunoHost
<b> *******Only intall on root path<br> Backup and Restore scripts not working******* </b>

## Postinstallation
Currently, you will have to do manually postinstallation.

You will have to go to `/index.php?r=install/main/index` and and enter the database setting received by the email.<br>
After this you need to set 'read-only' 644 right for the file protected/config/db.php with this command: 
```bash
chmod 644 /var/www/opr/protected/config/db.php
```

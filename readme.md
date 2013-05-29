Bash No-IP Updater
------------------

A bash script to update the IP address of a no-ip.com hostname.

__Usage__

1.  Configure the script with the correct username, password, hostname, IP cache file, and log file
2.  Make it executable (`chmod +x`)
3.  Run it (`./noipupdater.sh`)

__Automation__

Include the script in your cron file (`crontab -e`):

Run script once each day at 5:30am:  
    `30 5 * * * /path/to/noipupdater.sh`

Run the script every fifteen minutes:  
    `*/15 * * * * /path/to/noipupdater.sh`

Note: If the cron job doesn't execute correctly, try removing the `.sh` extension.

Based on the [Simple Bash No-IP Updater by AntonioCS](https://github.com/AntonioCS/no-ip.com-bash-updater)

__🌟 AWS Resource Tracker Shell Script 🌟__


Automate the tracking of your AWS resources with this powerful shell script! Set it up to run every 30 or 20 minutes, and get detailed emails with the latest resource status.

__🚀 Features:__

Automated Resource Tracking: Schedule the script to run at your desired intervals.
![AWS Resource Tracker](https://github.com/vermayesh123456/AWS-Resource-Tracker-Shell-Script/blob/main/Sample1.png)

Email Notifications: Integrate a mail transfer agent to receive detailed reports after every execution.

__🎉 Getting Started__


__Clone the repository:__


git clone
`https://github.com/vermayesh123456/AWS-Resource-Tracker-Shell-Script
.git`


__Navigate to the directory__

`cd AWS-Resource-Tracker-Shell-Script`


__Make the script executable:__

`chmod 777 aws_resource_tracker.sh`


__🛠️ Steps to Automate the Script__


__1. Set Up Crontab__
Use crontab to schedule your script:
`crontab -e`


__2. Add the Job to Your Crontab File__
Add the following line to run the script every minute:
`* * * * * /home/ubuntu/aws_resource_tracker.sh`


__4. Save and Exit__
Save the file: Press `CTRL+O`
Exit the file: Press `CTRL+X`


__6. Verify the Automation__
Check the logs to ensure your automation is working:
`grep CRON /var/log/syslog`



Feel free to reach out if you encounter any issues or need further assistance! 🚀

*__🎉Thankyou__*


🏆 AWS Resource Tracker Shell Script 🏆

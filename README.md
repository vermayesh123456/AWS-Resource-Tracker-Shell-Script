🌟 AWS Resource Tracker Shell Script 🌟


Automate the tracking of your AWS resources with this powerful shell script! Set it up to run every 30 or 20 minutes, and get detailed emails with the latest resource status.

🚀 Features:

Automated Resource Tracking: Schedule the script to run at your desired intervals.

Email Notifications: Integrate a mail transfer agent to receive detailed reports after every execution.

🛠️ Steps to Automate the Script


1. Set Up Crontab
Use crontab to schedule your script:
crontab -e


2. Add the Job to Your Crontab File
Add the following line to run the script every minute:
"* * * * * /home/ubuntu/aws_resource_tracker.sh"


4. Save and Exit
Save the file: Press 'CTRL+O'
Exit the file: Press 'CTRL+X'


6. Verify the Automation
Check the logs to ensure your automation is working:
grep CRON /var/log/syslog



Feel free to reach out if you encounter any issues or need further assistance! 🚀








🎉 Getting Started
Clone the repository:
git clone https://github.com/vermayesh123456/AWS-Resource-Tracker-Shell-Script
.git
Navigate to the directory:
cd AWS-Resource-Tracker-Shell-Script
Make the script executable:
chmod 777 aws_resource_tracker.sh
🎉Thankyou
🏆 AWS Resource Tracker Shell Script 🏆

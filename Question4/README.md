Question 4 – System Monitoring

Command: uptime  
Output:  
15:36 up 49 days, 16:16, 2 users, load averages: 2.13 1.78 1.78  
Explanation:  
This shows how long the system has been running, number of users, and system load.

Command: ps -u $USER  
Output:  
UID   PID TTY           TIME CMD  
501   739 ??         5:05.08 /usr/sbin/distnoted agent  
501   777 ??         7:49.79 /usr/libexec/secd  
501   779 ??         9:17.45 /usr/sbin/cfprefsd agent  
Explanation:  
This lists all processes running under my user account.

Command: sleep 300 &  
Output:  
[1] 56938  
Explanation:  
This started a background process that runs for 300 seconds.

Command: ps | grep sleep  
Output:  
56938 ttys000 0:00.00 sleep 300  
Explanation:  
This confirms that the background process is running.

Command: df -h ~  
Output:  
/dev/disk3s5 228Gi 106Gi 98Gi 53% /System/Volumes/Data  
Explanation:  
This shows disk usage of the filesystem where my home directory is stored.

Command: echo $SHELL  
Output:  
/bin/zsh  
Explanation:  
This shows the shell currently in use.

Command: uname -a > system_report.txt  
Output:  
(No output)  
Explanation:  
This command saved system information into a file.

Command: cat system_report.txt  
Output:  
Darwin Shobbus-MacBook.local 25.1.0 Darwin Kernel Version 25.1.0: Mon Oct 20 19:34:03 PDT 2025; root:xnu-12377.41.6~2/RELEASE_ARM64_T8112 arm64  
Explanation:  
This displays the contents of the system report file.

Command: ncdu ~  
Output:  
Command not found  
Explanation:  
The ncdu utility is not installed by default on macOS, but this command is used to view disk usage interactively when available.

Question 1 – Linux User & Environment Verification

Command: whoami  
Output:  
shobbu  
Explanation:  
This shows my login username.

Command: groups  
Output:  
staff everyone localaccounts _appserverusr admin _appserveradm com.apple.sharepoint.group.1 _appstore _lpadmin _developer _analyticsusers com.apple.access_ftp com.apple.access_screensharing com.apple.access_ssh com.apple.access_remote_ae  
Explanation:  
This shows the groups my user belongs to.

Command: pwd  
Output:  
/Users/shobbu  
Explanation:  
This shows my current working directory.

Command: ls -l  
Output:  
total 0  
drwx------@ 13 shobbu staff 416 11 Dec 08:11 Applications  
drwx------+ 9 shobbu staff 288 2 Jan 15:00 Desktop  
drwx------+ 8 shobbu staff 160 27 Oct 12:26 Documents  
drwx------+ 8 shobbu staff 256 30 Dec 18:52 Downloads  
drwx------@ 97 shobbu staff 3104 27 Oct 12:31 Library  
drwx------+ 4 shobbu staff 128 9 Oct 20:18 Movies  
drwx------+ 5 shobbu staff 160 9 Oct 20:15 Music  
drwx------+ 5 shobbu staff 160 10 Nov 20:57 Pictures  
drwxr-xr-x+ 5 shobbu staff 160 9 Oct 20:15 Public  
drwxr-xr-x 5 shobbu staff 160 27 Oct 12:10 Shobbu Verse  
Explanation:  
This lists all files and folders in the current directory with detailed information.

Command: wc -m user_info.txt  
Output:  
32 user_info.txt  
Explanation:  
This shows the number of characters present in the file.

Command: uname -r  
Output:  
25.1.0  
Explanation:  
This shows the Linux kernel version.

Command: ping -c 4 www.google.com  
Output:  
4 packets transmitted, 0 packets received, 100.0% packet loss  
Explanation:  
This checks network connectivity by sending packets to Google.

Command: uptime  
Output:  
15:03 up 49 days, 15:42, 2 users, load averages: 1.72 1.71 1.71  
Explanation:  
This shows how long the system is running, number of users, and system load.

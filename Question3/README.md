Question 3 – Links and Disk Usage

Command: echo "Sample data file" > sample_data.txt  
Output:  
File created successfully.  
Explanation:  
This created a file named sample_data.txt with sample text inside it.

Command: ln sample_data.txt sample_hard.txt  
Output:  
(No output)  
Explanation:  
This created a hard link to the original file.

Command: ln -s sample_data.txt sample_soft.txt  
Output:  
(No output)  
Explanation:  
This created a symbolic (soft) link to the file.

Command: ls -i sample_data.txt sample_hard.txt sample_soft.txt  
Output:  
5095832 sample_data.txt  
5095832 sample_hard.txt  
Explanation:  
Both files have the same inode number, which means they point to the same data on disk.

Command: ls -l sample_data.txt  
Output:  
-rw-r--r-- 2 shobbu staff 17 2 Jan 15:22 sample_data.txt  
Explanation:  
This shows file permissions, owner, size, and link count.

Command: du -sh ~  
Output:  
24G /Users/shobbu  
Explanation:  
This shows the total disk space used by my home directory.

Command: rm sample_soft.txt  
Output:  
(No output)  
Explanation:  
This removed the symbolic link only.

Command: ls sample_data.txt  
Output:  
sample_data.txt  
Explanation:  
This confirms that the original file still exists after deleting the soft link.

Command: df -h  
Output:  
/dev/disk3s1s1   228Gi   11Gi   98Gi   11%   /  
Explanation:  
This shows the total disk size, used space, and available space of the system.

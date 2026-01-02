Question 2 – File and Directory Management

Command: mkdir documents  
Output:  
Directory created successfully.  
Explanation:  
This created a new folder named documents inside my project directory.

Command: cd documents  
Output:  
(No output)  
Explanation:  
This moved me into the documents folder.

Command: touch plan.txt  
Output:  
(No output)  
Explanation:  
This created an empty file named plan.txt.

Command: echo "This is my project plan file" > plan.txt  
Output:  
(No output)  
Explanation:  
This added sample text into the plan.txt file.

Command: ls -l plan.txt  
Output:  
-rw-r--r-- 1 shobbu staff 29 2 Jan 15:16 plan.txt  
Explanation:  
This shows the file permissions, owner, and size of plan.txt.

Command: cp plan.txt plan_copy.txt  
Output:  
(No output)  
Explanation:  
This created a copy of plan.txt named plan_copy.txt.

Command: mv documents project_documents  
Output:  
(No output)  
Explanation:  
This renamed the documents folder to project_documents.

Command: mkdir project_documents/archive  
Output:  
(No output)  
Explanation:  
This created a subfolder named archive inside project_documents.

Command: mv project_documents/plan_copy.txt project_documents/archive/  
Output:  
(No output)  
Explanation:  
This moved the copied file into the archive folder.

Command: ls -R project_documents  
Output:  
archive  
plan.txt  

project_documents/archive:  
plan_copy.txt  
Explanation:  
This shows the full folder structure of project_documents.

Command: realpath project_documents/archive/plan_copy.txt  
Output:  
/Users/shobbu/linux_project/project_documents/archive/plan_copy.txt  
Explanation:  
This shows the full absolute path of the copied file.

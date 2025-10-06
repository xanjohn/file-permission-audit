# File Permission Audit — project_x.txt

## Objective
To ensure that the file permissions for `project_x.txt` align with the principle of least privilege by allowing only the necessary read access for the user and group.

## Initial Permissions
rw-rw-r--

## Action Taken
Updated file permissions using the command:
chmod u-w,g-w project_x.txt 

## Result
r--r--r--

##Verification
User: Can read file, but cannot write and execute.
Group: Can read file, but cannot write and execute.
Write permission has been removed from both user and group

## Conclusion
The file permissions were successfully updated to minimize unauthorized modification risks while maintaining necessary read access for the research team.



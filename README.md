
![image](https://github.com/user-attachments/assets/09fb938b-03bf-4fb0-aca2-99b2b21024b0)
# Linux: Manage authorization
This lab outlines how to manage permissions for files inside of Linux.


# Environments and Technologies Used</h2>
- Google Cloud Virtual Machines.
- Various Linux commands.

# Operating Systems Used </h2>
- Linux.

# Actions and observations

In this scenario, we are going to examine and manage the permissions on the files in the /home/researcher2/projects directory for the researcher2 user.
The researcher2 user is part of the research_team group.
we must check the permissions for all files in the directory, including any hidden files, to make sure that permissions align with the authorization that should be given. When it doesn't, we must change the permissions.

![image](https://github.com/user-attachments/assets/d197897c-e548-4253-ac7c-736c29818b56)

- First, use the pwd command to see our current directory.

![image](https://github.com/user-attachments/assets/69714908-3c82-4e9d-a397-e99f6dcaf0b7)

- Using the cd command to travel to the project's directory.

![image](https://github.com/user-attachments/assets/673d6472-ff34-4e74-9fad-2c4dbc89e62d)

- Using the ls -la command to list all hidden files and their permissions, and observing that only the project_x.txt file has write privileges for others and that project_m.txt has read permissions. 

![image](https://github.com/user-attachments/assets/91b4d5a9-7794-4931-92aa-8dd032a273dc)

- Using Chmod to change permissions for the project m.txt file.

![image](https://github.com/user-attachments/assets/b3322bcc-4e9b-4963-948a-8472a953f767)

- Removing all permissions from the project_m.txt.

![image](https://github.com/user-attachments/assets/1c423a97-faf0-482d-a527-b0087283f910)

- Using ls -la to verify that the permissions have been updated, and seeing that the hidden project_x.txt has user read permissions but the group does not.

![image](https://github.com/user-attachments/assets/376f85e2-2bf0-49bd-b5d7-cd359f19c8e1)

- Giving project_x.txt group read permissions.

![image](https://github.com/user-attachments/assets/5196c7af-c6e2-4bbb-a7b9-84df0c280568)

- Observing that the draft directory has group access.

![image](https://github.com/user-attachments/assets/a8b7a7c7-23db-49e4-b73e-3560dafdd635)

- Removing group execute permissions from the write folder.

                                          ![image](https://github.com/user-attachments/assets/5e975abe-4f83-4ab2-9c47-96520bc38d24)
  


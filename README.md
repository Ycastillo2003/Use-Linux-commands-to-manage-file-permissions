
![image](https://github.com/user-attachments/assets/e09a3aae-4049-47c2-a8d0-82f9d0ab1ee3)


# Linux: Manage authorization
This lab outlines how to manage permissions for files inside of Linux


# Environments and Technologies Used</h2>
- Google Cloud Virtual Machines.
- Various Linux commands.

# Operating Systems Used </h2>
- Linux.

# Actions and observations

In this scenario, we are going to examine and manage the permissions on the files in the /home/researcher2/projects directory for the researcher2 user.
The researcher2 user is part of the research_team group.
You must check the permissions for all files in the directory, including any hidden files, to make sure that permissions align with the authorization that should be given. When it doesn't, we must change the permissions.

![image](https://github.com/user-attachments/assets/d197897c-e548-4253-ac7c-736c29818b56)

- First, use the pwd command to see our current directory.

![image](https://github.com/user-attachments/assets/69714908-3c82-4e9d-a397-e99f6dcaf0b7)

- Using the cd command to travel to the project's directory.

![image](https://github.com/user-attachments/assets/673d6472-ff34-4e74-9fad-2c4dbc89e62d)

- Using the ls -la command to list all hidden files and their permissions. 


### Background
E4-Integrated Project exercices whole objective is to show how you can modularize content from one automation to another automation. 

In this series, 

1. We will create a new automation that includes both of our Outlook and Excel Project. 
2. To this new project, we will create an environment variable where all file processing needs to happen. we will call this variable as baseFolderPath.
3. We will search a specific folder and read each email in that outlook, save its attachment to the baseFolder with subFolder as timeStamp per email.
4. We will modify excel project to read this basePath and folders and dynamically read files, for each file, it will activate the first sheet and do the rest of excel operation from E3-Excel exercices. 

### Pre-requisites
1. SAP Process Automation service is setup in your SAP BTP Subaccount
2. User running the automations have required roles
3. You have access to a Windows System and all the required on-premise components are installed in that windows system
4. Microsoft Office (Outlook, Excel) is installed in that windows system, with at least one mailbox configured
5. You will need a sample excel. Any excel will do with few rows/columns of data. You will use it as a sample to execute the exercises in this workshop. I have used customers
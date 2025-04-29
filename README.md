Nutanix Monitor:

To download and constantly update the Nutanix-Monitor tool, you can download only the Update.exe file from the dedicated GitHub repository ( https://github.com/balduz84/NX-Monitor) and place it in a dedicated folder:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/e39e7f41-315e-48fd-b1a1-c1f0aa875bc6" />

By launching Update.exe, you will be asked if you want to download the Nutanix Collector 5.3 package (the latest currently available) from the Nutanix portal. Pressing “Y” will automatically unload and unpack the package in the correct position:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/fc85fc4f-f06d-4e1a-9f0b-5906f57ad543" />

<img width="482" alt="image" src="https://github.com/user-attachments/assets/916d12c6-e2e1-44c5-9bdd-e370dbd092e8" />

At the end of the Nutanix Collector download, you will be asked if you want to update the files necessary for the Nutanix Monitor tool to work, updating any previous versions previously downloaded. Press “Y” to start downloading files from the project's GitHub repository:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/935c2bbb-d4eb-4228-b32b-012f1f0269b2" />

The tool will not overwrite user-customized files (especially logo.png and Config.xml files).

<img width="482" alt="image" src="https://github.com/user-attachments/assets/2f037bf2-7499-47e2-90ef-12dd86d8b0dd" />

At the end of the download, Update.exe will close automatically, and you will have all the files necessary for the tool to work, updated to the latest release:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/8eb8e1fc-6637-45a1-82af-8c870c292088" />

Start Nutanix-Monitor.exe to run the tool:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/4172a598-0aaa-46d5-a2de-ea1f910ff61b" />

The first time you run it, you will be notified that the Config.xml file is missing, which will contain the address and credentials for accessing your Nutanix cluster. Press OK to proceed anyway.

<img width="482" alt="image" src="https://github.com/user-attachments/assets/86a5d4a6-625d-46a5-86e4-5c4025e73cc1" />

When the tool has started, you will be able to move to the "Logs & Export" tab, where you will be able to view the logs of the tool and enter the access data to the Nutanix cluster:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/e447410e-e68c-4444-ad67-d0df184333bd" />

By filling in the required data and clicking on "Save credentials" the Config.xml file will be automatically generated which will contain the necessary information for the next executions of the tool.

<img width="482" alt="image" src="https://github.com/user-attachments/assets/8bd83231-6dd7-4d1e-9155-76486f50483e" />

Press the "Export" button to start extracting information from the Nutanix cluster. This process is based on the functionality of the Nutanix Collector and will save the extracts in the Exports folder (which will be automatically created by the tool).
During the export, the Nutanix Monitor tool will intercept the Nutanix Collector logs, showing them in the log window.

<img width="482" alt="image" src="https://github.com/user-attachments/assets/43120419-caed-44d8-86cb-49e29efae6b8" />

When the export is finished, the generated files will be available in the "Exports" folder:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/0b5369c7-15a6-4dd1-a85f-38b824c0a11b" />

Now you can select the export from the right section of the tool (or load more than one manually or by date range) to view the cluster statistics, the cluster properties and the statistics of the individual virtual machines:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/8d1205cf-c66b-41e7-b798-7da6481b2f4a" />

<img width="482" alt="image" src="https://github.com/user-attachments/assets/53f35c8a-990c-4869-89ed-86c18bc197ed" />

<img width="482" alt="image" src="https://github.com/user-attachments/assets/3fb43d74-f5bf-40cc-8b9d-bfa4ebe37021" />

Cluster statistics can be exported to PDF using the dedicated button in the "Cluster statistics" tab. Before you can do this, however, you need to upload a "logo.png" file with your company logo to the folder:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/6668651c-38b1-4176-bdf8-fdbdf0b6ad1f" />

In the textbox to the left of the "PDF" button, the title that will be written on the first page of the PDF is shown:

<img width="482" alt="image" src="https://github.com/user-attachments/assets/de4fd02b-ed7d-44eb-a3ff-6953fd60accf" />

Change the title if it is not the one you want and press the PDF icon to generate the file.

Exporting to PDF will generate a file in the "PDF" folder with the name "NomeCluster-DataOdierna.pdf"

<img width="482" alt="image" src="https://github.com/user-attachments/assets/ebd526eb-9f0e-4428-b233-430b3bd3e067" />


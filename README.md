# VM Migration Lab

## Assessmemt Report:
- The VM is compatible with Azure, and the Windows Server 2019 OS is supported in Azure.
- The VM met the minimum resource requirement including the VM's memory at 4gb for better performance.
- The networking configuration of the VM was correct for migration.
- The dick I/O and CPU usage were withing the acceptable limit for the migration.

## Migration Outcome:
- Azure Migrate was unable to identify the virtual machine for replication. Unable to resolve issue with Mobility Service Agent not installing.

## Screenshots:
Shows the web appplication Hello World on the VM
![Screenshot 2024-11-17 194743](https://github.com/user-attachments/assets/ead613c8-5d72-4169-93b5-53d79e503a4d)
---
These show that the project was successfully created and was able to finialize registration for the replication appliance.
![Screenshot 2024-11-17 201850](https://github.com/user-attachments/assets/4d5a74f0-f506-4bbb-984a-238a4e6274f2)
![Screenshot 2024-11-17 222803](https://github.com/user-attachments/assets/97207f4c-0d61-4a85-8cbf-09e15311b394)
---
Shows that the Agent is configured however the VM wouldn't appear in the Replication phase.
![Screenshot 2024-11-17 225255](https://github.com/user-attachments/assets/6d1a9911-ea6a-413a-a71d-e34422a35ee3)
![Screenshot 2024-11-17 225357](https://github.com/user-attachments/assets/1b996711-e874-4a53-a06d-230442cef22c)
![Screenshot 2024-11-17 225405](https://github.com/user-attachments/assets/116dd811-53e4-4ea6-bb4f-2fee055891a2)
![Screenshot 2024-11-17 230847](https://github.com/user-attachments/assets/863fd114-2b23-43aa-a7bf-79f6dbafcde3)
---

## Reflection:
Migrating a workload to Azure requires careful planning and verification at every step, like testing network connectivity. Designate more time because creating the project took multiple attempts of multiple hours before Azure let me create it.

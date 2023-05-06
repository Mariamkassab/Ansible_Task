# Ansible_Tasks
---
## Tasks:
* Create your first role with name (web)
* The task book will include:
* 1. installing a package
      * (get the package name from vars)
* 2. Copying a file from controller to host using template
      * (get the template name & template message from vars)
      * (the actual template file will be stored in ./roles/web/templates)
      * (will also notify the restart handler)
* 3. copying a list of files from controller to host using loop
      * (get the list of file names from vars)
      * (the actual files will be stored in ./roles/web/files)
      * (will be executed using Handlers)
* Restart the service of the installed package
      * (will be executed using Handlers chaining)
      
---

      
![Screenshot from 2023-05-07 02-27-53](https://user-images.githubusercontent.com/123699968/236650378-8d6304f5-4acb-4695-bb42-3964392aa8fd.png)

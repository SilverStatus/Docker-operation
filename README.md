# Docker-operation
Operate docker using ansible

--> docker_operation.yaml file contains script to install & manage docker on centos 7. == main script.                                    
--> default_var.yaml file contains variable used for main script == variable file.

How to use this script:
- download all file (docker_operation.yaml & default_var.yaml)
- to execute this script use command 
  " ansible-playbook docker_operation.yaml "
- to change variable, open file default_var.yaml
  
To edit variable pay attention to these remarks:
- container_name = name of container that want to create
- container_image = name of docker image that will be downloaded
- container = name of container that will be checked
- delete_container = name of container that will be deleted
  

  

# RunYourCodeOnAWS
This repository contains example playbooks to help you run your code on AWS EC2 instance.
A breief, motivation and concrete instructions can be found in the attached post.

To run the playbooks:
ansible-playbook prepare_nexus_images.yml --extra-vars {"user_name":"my_name", "password":"W3a$!GHY6re$%^H","nexus_user":"my_username", "nexus_pass":"my_nexus_pass"}

ansible-playbook ec2_handler.yml --extra-vars {"aws_access_key":"AKIA3G4WER3451", "aws_secret_key":"W3a$!fsdffsdfsdf354$%^H", 
  "nexus_user":"my_username", "nexus_pass":"my_nexus_pass", "profile":"my_source_profile", "image":"my_image", "group":"my_group", "vpc_subnet_id"="my_subnet_id"}
 

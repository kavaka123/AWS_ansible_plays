1. My local installation is using python3 as the default ansible python module ( see ansible --version command)

2. So, for installing any python modules for using in aws, use this command. for ex: pip3 install boto boto3

3. This playbook is for creating and/or gathering facts about running ec2 instances.

4. Usage: ansible-playbook playbook.yml --ask-vault-pass --tags create_ec2   ( for creating ec2 instances )
		  ansible-playbook playbook.yml --ask-vault-pass   ( for gathering facts like instance ids, status, public dns names )	 

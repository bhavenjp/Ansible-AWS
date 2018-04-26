# Ansible-AWS (Ansible Playbooks for AWS Cloud)



Setup:
1) CentOS 7 Server
2) Install Python, pip
4) Install boto, boto3, botocore
5) Install Ansible


Playbook-01 (Creat AWS VPC): create-vpc.yml
# ansible-playbook create-vpc.yml

PLAY [Create AWS VPC] *************************************************************************************************************

TASK [Create AWS VPC in Singapore Region] *****************************************************************************************
changed: [localhost]

PLAY RECAP ************************************************************************************************************************
localhost                  : ok=1    changed=1    unreachable=0    failed=0

#


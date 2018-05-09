Role Name
=========

Ansible playbook to create a basic <a href="https://infinitypp.com/ansible/create-vpc-ansible-aws/">AWS VPC in Ansible</a>


<img src="https://infinitypp.com/wp-content/uploads/2018/04/Untitled-Diagram-2.png">

Requirements
------------

* AWS credentials to create resources.
* AWS Configured in console

Role Variables
--------------

* region: The region which the resources will be created https://docs.aws.amazon.com/general/latest/gr/rande.html#vpc_region
* vpc_cidr: CIDR Block of VPC
* subnet_cidr: CIDR Block of Subnet
* igw_name: IGW Name
* route_name: Route Name
* securitygroup_name: Security Group Name
* ec2_tag: EC2 Name


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
        - aws
        

License
-------

MIT / BSD

Author Information
------------------

<a href="https://infinitypp.com">Atarod</a>  <s.atarod@infinitypp.com> 

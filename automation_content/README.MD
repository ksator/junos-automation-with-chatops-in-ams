This directory has the automation content you can ask to the bot to execute (ansible playbooks, jinja2 templates. python scripts ....):  
- **jinja2 templates** - These files are names **xxx.j2**
- **python scripts** - These files are names **xxx.py**
- **ansible playbooks** - These files are named **pb.xxx.yml**
- **ansible inventory** - [**hosts**] (https://github.com/ksator/junos-automation-with-chatops-in-ams/blob/master/automation_content/hosts) file
- **variables definition** - They are defined under the directories **host_vars** and [**group_vars**] (https://github.com/ksator/junos-automation-with-chatops-in-ams/blob/master/automation_content/hosts)   

Note: the ansible configuration file [**ansible.cfg**](https://github.com/ksator/junos-automation-with-chatops-in-ams/blob/master/ansible.cfg) is NOT under this directory. It is at the root level of this reposirtory.    




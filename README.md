# juniper_BGP_auto

Router's confiuration is store in yaml files.
https://github.com/krispigeau/juniper_BGP_automation/tree/main/host_vars

Jinja 2 template is tamplated to resproduce a juniper devices configuration
https://github.com/krispigeau/juniper_BGP_automation/blob/main/templates/template.j2

Configurations can be generated then copied to devices

To run playbook

ansible-playbook jinja2-render.yml

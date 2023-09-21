# ansible-project

` creating ansible docker role ####use ansible-galaxy init docker` 
`ansible-galaxy install -r requirements.yml`
 ## test stage
 ` yamllint
   ansible-playbook --syntax-check
   ansible-lint
   molecule test(integration)
   ansible-playbook --check(against prod)
   Parallel infrastructure`

   ## how to create ansible config global
   ansible-config init --disabled -t all > ansible.cfg
   

   # Ansible Automation events.

   ```3 keys for taking automation to the next level```
   1. ` we had to chnage our mindset in how we're managing and deplouing our global networok, which included not only modernizing our platforms but modernizing our skill sets.`
   2. `how to autmomated`
   `Standardize >>> Codify >>>  Operationalize`
   3.`need a platform make all these operational`

   ## Event-Driven Ansible
   ## Generative AI

   C culture
   A automation
   L lean it
   M measurement
   S sharing

   look at the ansible and servicenow integration.
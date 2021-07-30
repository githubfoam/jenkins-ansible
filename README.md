# jenkins-ansible

vagrant, packer template, travisci,ansible role
~~~~
del Vagrantfile
vagrant init --template Vagrantfile.erb 
vagrant up vg-compute-10

Browse
http://192.168.20.18:8080/



administrator password from ansible playbook output

TASK [print init password jenkins] *********************************************
ok: [vg-compute-10] => {
    "result.stdout": "fcb019a49b844983881cab76f47493d0"
}

PLAY RECAP *********************************************************************
vg-compute-10              : ok=24   changed=9    unreachable=0    failed=0    skipped=2    rescued=0    ignored=0

~~~~

~~~~
https://www.jenkins.io/
Official Jenkins Docker image
https://hub.docker.com/_/jenkins
~~~~
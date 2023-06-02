# animated-octo-sniffle
Ansible Playground

## Ansible: used to automate configuration for almost anything you can remote into (ssh)

### Steps taken to configure lab:
1. Installed Ubuntu on WSL using wsl --install -d ubuntu
2. Once installed I added the ansible repo using sudo apt-add-repository ppa:ansible/ansible
3. Then I was able to update the package info and then install the ansible package
4. tested ansible connection to hosts stored in the host file using: ansible -i hosts servers -m ping --user andrew --ask-pass



## Resources used to learn:

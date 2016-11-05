# Ansible role L2TP VPN
Ansible role for VPN L2TP installation

## How to
1. Install or copy the role.
2. Include the role in your playbook
3. Set variable in vars role folder or in your playbook.
    - public_ip: public ip of the server
    - private_ip: local ip of the server
    - { username: "username1", password: "password1" }
4. Run playbook
5. Configure VPN using username and password provided

## Links
[Cloudformation with bash script in userdata used as base script](https://www.webdigi.co.uk/blog/2015/how-to-setup-your-own-private-secure-free-vpn-on-the-amazon-aws-cloud-in-10-minutes/)

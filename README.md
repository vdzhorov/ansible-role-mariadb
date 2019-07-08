# ansible-role-mariadb

Install and configure MariaDB

### Prerequisites

** none **

## Deployment

Example playbook:

```
- hosts: sql_servers
  roles:
    - 'ansible-role-mariadb'
```

Configure your vars in vars/main.yml. After that simply run your playbook:

```
ansible-playbook -i '<TARGET_HOST_IP>,' playbooks/mariadb.yml
```

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/2.8/index.html)

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company

* **Delta.BG**

## License

This project is licensed under the MIT License.

# Ansible server configuration

Server configuration with ansible.

There are multiple tasks, you need to specify the hosts
 file to your hosts and change the variables on the playbook.yml
 file, there you can uncomment your tasks.

## Use

You should copy example vars to a vars dir

```sh
cp -r ./example/* .
```

And edit both hosts and group_vars files
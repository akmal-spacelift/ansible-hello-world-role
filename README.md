Role Name
=========

Just a hello world role for use in Ansible.

Role Variables
--------------

Available variables listed below with the default values (`defaults/main.yml`):

```
hello_world_message: Hello World!
```

```
hello_world_dir: /tmp/shared/hello-world
```

Example Playbook
----------------

```
  - hosts: all
    roles:
      - akmal-spacelift.hello_world
```

License
-------

MIT

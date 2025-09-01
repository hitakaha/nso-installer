# NSO auto installer
This is a YAML playbook to execute NSO local install.

# How to use
Just execute following.

```
$ ansible-playbook nso.yml
```

# Requirement and customization
- NSO and NED packages are located in the same directory
- Prepare devices.xml to load and sync-from devices

# Customization
Edit vars in the YAML file.


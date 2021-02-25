# Ansible sample playbooks

## Description

## Roles

### linux
|Playbook|Desctiption|Module|
|:--|:--|:--|
|selinux.yml|SELinux configuration|selinux|
|hostname.yml|Hostname configuration|hostname|
|hosts.yml|/etc/hosts configuration|copy|
|repo.yml|Local repository configuration|template|
|dnf.yml|Packages installation|dnf|
|systemd.yml|Service configuration|systemd|
|parted.yml|Partition configuration|parted|
|filesystem.yml|Filesystem configuration|filesystem|
|dir.yml|Directories configuration|file|


#### selinux.yml


- Description

    SELinux configuration


- Variables

    Set variables to group_vars/ or host_vars like below.

    |Variable|Range|
    |:--|:--|
    |linux_selinux_state|disabled<br>enforcing<br>permissive|


- Example

    ```yaml:all.yml
    linux_selinux_state: disabled
    ```

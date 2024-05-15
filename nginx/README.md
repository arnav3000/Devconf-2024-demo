# Nginx Role

This Ansible role installs and configures Nginx on target hosts.

## Role Variables

- `nginx_port`: The port on which Nginx will listen. Default is `80`.
- `nginx_config_file`: The path to the Nginx configuration file. Default is `/etc/nginx/nginx.conf`.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: web_servers
  roles:
    - nginx

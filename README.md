# [Dokku Alternative](https://github.com/dokku-alt/dokku-alt) Role for Ansible

Install [Docker](https://www.docker.com/) and [dokku-alt](https://github.com/dokku-alt/dokku-alt) using official PPAs and perform initial setup for Dokku.

**Warning:** This role is still very experimental and not finished yet! Use at your own risk!

## TODO

- [] Support for plugins installation
- [] Initial pubkey configuration for ACL
- [] Working Vagrant configuration (probably with Landrush)
- [] Travis / Wercker configuration
- [] Use an existing Docker role (?)
- [] Allow automatic reboot on Aufs install

## Example

    - hosts: servers
      roles:
         - { role: jnv.dokku-alt, dokku_vhost: 'dokku.docker.dev' }

## License

MIT

# Ansible Role: Users

Because I'm lazy creating users manually, I automated it and then adding them to sudo.

## Requirements

Host should be able to:
 * useradd
 * userdel
 * usermod

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    users: 
        - johndoe

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-users }

## License

MIT / BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

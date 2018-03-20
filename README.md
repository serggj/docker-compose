Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - { role: docker-compose, compose_version: 1.18.0 }
        - { role: docker-compose, compose_version: 1.19.0 }


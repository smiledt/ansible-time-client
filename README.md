# Time-Client

A role to set up NTP on my ubuntu servers.

## Requirements

Sudo access to the server. 

## Required variables

Required variables are listed here, along with default example values. Any of these defaults can be overwritten by using the vars role directory. 

    ntp_servers:
      - 0.us.pool.ntp.org
      - 1.us.pool.ntp.org
      - 2.us.pool.ntp.org
      - 3.us.pool.ntp.org

    timezone: America/Chicago
## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - name: Configure the ntp client
      hosts: linux
      become: true
      roles:
        - role: time-client

### License

MIT

### Author Information

Derek Smiley - Network Analyst, avid homelabber, and aspiring Systems Administrator.

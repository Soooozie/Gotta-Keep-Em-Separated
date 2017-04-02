New project to separate major services to separate servers.

Going to be starting out with mysql. 3.9.2017
Moving on to varnish cache. 4.2.2017

NOTES TO MYSELF:
ansible host variables:
{{ hostvars[groups['web-server'][0]]['ansible_eth0']['ipv4']['address'] }}

# nagios-plugins-openldap
Docker image which include LTB Project Nagios plugins for OpenLDAP

Please see:
http://ltb-project.org/wiki/documentation

for documentation 

## example:
```
docker run leonkyneur/nagios-plugins-openldap perl check_ldap_monitor.pl -H ldap1.example.org -p 389 -D cn=monitoring,cn=Monitor -P monitoringpassword -c 10 -w 1 -T currentconnections -c 605480 -w 100000 -f
```

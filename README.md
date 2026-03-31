# LDAP-Brute-Force
nmap -p 389 --script ldap-brute \
--script-args ldap.base="cn=users,dc=CEH,dc=com" <Target-IP>

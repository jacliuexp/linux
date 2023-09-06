# linux

```
# lsattr /etc/audit/auditd.conf
----i----------- auditd.conf    # immutable

# chattr -i /etc/audit/auditd.conf
# lsattr /etc/audit/auditd.conf
---------------- /etc/audit/auditd.conf

### file can be changed now
```

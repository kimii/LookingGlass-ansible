# USAGE
```
ansible-playbook <*.yml>
```
# command common used in LookingGlass
- traceroute:
    - v4: traceroute -4 -A -w 2 ip_address
    - v6: traceroute -4 -A -w 2 ip_address # A: as-path-lookups
- ping:
    - ping -c 4 -i 1 -w 8 ip_address # c: count i: interval second w: timeout
- host:
    - host ip_address
- mtr:
    - mtr -4 --report --report-wide -c 4 ip_address


# CAM
Learn Basic of CAM in switch

1. You need 2 VPC and 2 switch.

```
show mac address-table
```

2. ping each other and show the mac address-table.

```
show mac address-table
```

3. compare the result for mac address-table

```
show mac address-table interface Ethernet 1/1

show cdp neighbors
```

4. show the aging-time
```
show mac address-table aging-time
```
6.  changeing the aging time example in seconds

```
mac address-table aging-time 600
```

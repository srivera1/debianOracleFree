## Virtual Box image

1) git clone https://github.com/srivera1/debianOracleFree.git

2) cd debianOracleFree/ova

3) 7z x debianOracleFree.7z.001

4) $ md5sum debianOracleFree.ova

12e78956b2738d528c3bc1452448d769  debianOracleFree.ova

5) Import debianOracleFree.ova in VirtualBox


### Machine details
debian-12.2.0-amd64


ORACLE FREE 23c

24/11/23


### SO login details
debianoracle:debianOracle


### DB login details
sys:debianOracle


### Config hostname and IP (!)
add IP hostname at

/etc/hosts

or just execute 

$ sudo dhclient

$ /home/debiaoracle/add_hostname_to_hosts.sh


### DB Server port
1521


### Useful scripts included
/home/debiaoracle/sqlplus.sh

/home/debiaoracle/add_hostname_to_hosts.sh




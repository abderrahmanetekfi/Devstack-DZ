# Devstack-DZ
Hello, this is a VM with devstack installed on it, enjoy.
here you find the OVA file : https://mega.nz/#F!RNcD2YpS!cfz0cO1YBdo8btq45o9j7g
user : atekfi
password : root

USER: atekfi
password: root

history
    1  git clone https://git.openstack.org/openstack-dev/devstack
    2  cd devstack
    3  nano local.conf
    4  ./stack.sh 

[[local|localrc]]
ADMIN_PASSWORD=root
DATABASE_PASSWORD=$ADMIN_PASSWORD
RABBIT_PASSWORD=$ADMIN_PASSWORD
SERVICE_PASSWORD=$ADMIN_PASSWORD


=========================
DevStack Component Timing
 (times are in seconds)  
=========================
run_process           50
test_with_retry        5
apt-get-update        10
osc                  146
wait_for_service      29
git_timed            256
dbsync                29
pip_install          910
apt-get              711
-------------------------
Unaccounted time     510
=========================
Total runtime        2656



This is your host IP address: 192.168.132.131
This is your host IPv6 address: ::1
Horizon is now available at http://192.168.132.131/dashboard
Keystone is serving at http://192.168.132.131/identity/
The default users are: admin and demo
The password: root

WARNING: 
Using lib/neutron-legacy is deprecated, and it will be removed in the future


Services are running under systemd unit files.
For more information see: 
https://docs.openstack.org/devstack/latest/systemd.html

DevStack Version: stein
Change: a61b4704871e7b0ae88a50932576e961eca615e4 Merge "Remove cgroup natty or less block" 2018-11-02 15:29:37 +0000
OS Version: Ubuntu 18.04 bionic


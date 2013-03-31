ucs-openstack-cimc-expect
=========================

CIMC Expect script to set up a standalone UCS server for Cisco OpenStack Edition installation

setup.exp sets up the RAID controller, VIC for PXE boot, and boot priority.
cimc\_update.exp loads the CIMC firmware (to be done before bios)
bios\_update.exp loads the BIOS
setup\_slot.exp sets up the system assuming SLOT-2 RAID and 8 disks in RAID6
setup\_mezz.exp set up the system assumign MEZZ RAID and 5 disks in RAID5
Based on the description found here:

http://www.cisco.com/en/US/docs/unified\_computing/ucs/c/sw/cli/config/guide/1.4.1/b\_Cisco\_UCS\_C-Series\_CLI\_Configuration\_Guide\_141\_chapter\_01101.html#task\_25869FBB5C9D41A597D17912DAF1BCFD

or google for ucs cimc cli bios firmware


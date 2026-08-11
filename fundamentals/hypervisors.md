**Rooms:** Hypervisor Internals | Hosted Hypervisors



**Theory:**



Types of Hypervisors:

* Type 1 (Bare metal)
* Type 2 (Hosted)



Hypervisor Tech:

* Hyper-V
* VirtualBox
* VMware ESXi
* VMware Workstation
* QEMU



VM Investigation commands:

```C:\\ProgramData\\VMware\\logs``` = VMware logs

```volatility3```

```$ python vol.py -f ../exercise.mem windows.pstree``` = for PID

```$ python vol.py -f ../exercise.mem windows.netscan``` = for IP




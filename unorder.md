```shell
grep -E 'svm|vmx' /proc/cpuinfo
lsmod | grep kvm
virsh capabilities
virsh cpu-models
virsh cpu-models x86_64
virsh cpu-models ppc64
cat /usr/share/libvirt/cpu_map.xml

yum install qemu-kvm qemu-img libvirt
yum install virt-install libvirt-python virt-manager libvirt-client
yum install python-vir*
yum groupinstall "Virtualization Tools"
yum install subscription-manager
yum install virt-who
subscription-manager register --username=admin --password=secret --auto-attach --type=hypervisor
cat /var/log/rhsm/rhsm.log

```

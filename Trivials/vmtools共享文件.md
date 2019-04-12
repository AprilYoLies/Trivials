# Vmtools共享文件
ubuntu则先执行  sudo apt-get install open-vm-dkms
然后再执行3

centos7则先执行 yum install open-vm-tools

然后再执行vmhgfs-fuse .host:/ /mnt/hgfs 不过我还是做不到让它启动后自动挂载，每次启动需要重新执行这个命令。
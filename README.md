'''
Установлена система CentOS 7
Весрия ядра:

enis@DDA-VirtualBox:~/hometask_vm$ vagrant ssh
[vagrant@kernel-update ~]$ uname -r
3.10.0-1127.el7.x86_64

Выполенено обновление ядра:

Transaction test succeeded
Running transaction
  Installing : kernel-ml-6.5.9-1.el7.elrepo.x86_64                          1/1 
  Verifying  : kernel-ml-6.5.9-1.el7.elrepo.x86_64                          1/1 

Installed:
  kernel-ml.x86_64 0:6.5.9-1.el7.elrepo 

Версия ядра после выполенения обновления:

[vagrant@kernel-update ~]$ uname -r
6.5.9-1.el7.elrepo.x86_64

'''

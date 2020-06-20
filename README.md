# easy-openstack-installation-from-host-images

You can download disk images of an educational controller and network nodes of OpenStack from the following links. 
<ul>
  <li><a href="https://tuipied-my.sharepoint.com/:u:/g/personal/ckasidit_staff_tu_ac_th/EfsX37sk6GFAuZ4feDP067QBfZI_Ni0EMtD67advsXn3lg?e=YBJhM4">controller node</a></li>
  <li><a href="https://tuipied-my.sharepoint.com/:u:/g/personal/ckasidit_staff_tu_ac_th/EV2qYz-eep9HgE3ghFEyk0sBYVM8-F8mFvvbll3POQeF-w?e=CQsHDC">network node</a></li>
</ul>
<p><p>
Note that if you cannot use tools like wget to download these files directly to a linux box, you may have to use a browser to download them first and then use tools like sftp pr winscp to transfer them to your target computers later. Please send an email to kasiditchanchio@gmail.com if you are unable to download these files. 
<p><p>
After you download these image files and tranfer them to a target host computer, you can use qemu-kvm software to run a controller and a network node of OpenStack as virtual machines (VMs). 
<p><p>
<h1>Configurations of the host computer</h1>  
<p><p>
We assume that the host computer is an Ubuntu 16.04 server box. The CPU must have hardware virtualization supports and can run QEMU with KVM enabled. 
<p>
In terms of ths sizes of RAM and storage, it depends on what kind of study you want to do. 

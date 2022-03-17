# LAB 2
## Create an EC2 instance with type t2.micro (in a public subnet)

![0.create-2-instance](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/0.create-2-instance.png)

##Task 2: Connect SSH to the EC2 instance, remove the authorized_keys then disconnect the SSH
###Connect to LostSSHKey
![1.ssh-to-instance-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/1.ssh-to-instance-lostsshkey.png)
![2.rm-authorized-keys-then-logout](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/2.rm-authorized-keys-then-logout.png)
![3.detach-volume-of-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/3.detach-volume-of-lostsshkey.png)
![4.stop-inst-lostsshkey-and-launch-recoversshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/4.stop-inst-lostsshkey-and-launch-recoversshkey.png)
![5.attach-volume-of-lostsshkey-to-recoversshkey-inst](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/5.attach-volume-of-lostsshkey-to-recoversshkey-inst.png)
![6.attach-volume-of-lostsshkey-to-recoversshkey-inst-with-device-name-sdf](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/6.attach-volume-of-lostsshkey-to-recoversshkey-inst-with-device-name-sdf.png)
![7.ssh-to-instance-recoversshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/7.ssh-to-instance-recoversshkey.png)
![8.mount](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/8.mount.png)
![9.copy-authorized-key-then-logout](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/9.copy-authorized-key-then-logout.png)
![10.detach-volume-of-lostsshkey-again](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/10.detach-volume-of-lostsshkey-again.png)
![11.attach-volume-of-lostsshkey-to-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/11.attach-volume-of-lostsshkey-to-lostsshkey.png)
![12.attach-volume-of-lostsshkey-to-lostsshkey-inst-with-device-name-xdva](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/12.attach-volume-of-lostsshkey-to-lostsshkey-inst-with-device-name-xdva.png)
![13.start-lostsshkey-instance](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/13.start-lostsshkey-instance.png)

##Task 3: Delete SSH access from the EC2 security group

![14.IAM-roles](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/14.IAM-roles.png)
![15.Select-trusted-entity](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/15.Select-trusted-entity.png)
![16.Add-permissions](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/16.Add-permissions.png)
![17.Role-name](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/17.Role-name.png)
![18.Session-manager](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/18.Session-manager.png)
![19.Start-session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/19.Start-session.png)
![20.Choose-LostSSHKey-then-start-session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/20.Choose-LostSSHKey-then-start-session.png)
![21.Session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/21.Session.png)
![]()
![]()
![]()
![]()
![]()


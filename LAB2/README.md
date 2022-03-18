# LAB 2
## Task 1 :Create an EC2 instance with type t2.micro (in a public subnet)

![0.create-2-instance](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/0.create-2-instance.png)

## Task 2: Connect SSH to the EC2 instance, remove the authorized_keys then disconnect the SSH
### Connect to LostSSHKey
![1.ssh-to-instance-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/1.ssh-to-instance-lostsshkey.png)
### remove authorized-keys then logout 
![2.rm-authorized-keys-then-logout](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/2.rm-authorized-keys-then-logout.png)
### detach volume of lostsshkey
![3.detach-volume-of-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/3.detach-volume-of-lostsshkey.png)
### stop LostSSHKey instant then launch RecoverSSHKey instance 
![4.stop-inst-lostsshkey-and-launch-recoversshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/4.stop-inst-lostsshkey-and-launch-recoversshkey.png)
### Attach LostSSHKey instance to RecoverSSHKey instance 
![5.attach-volume-of-lostsshkey-to-recoversshkey-inst](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/5.attach-volume-of-lostsshkey-to-recoversshkey-inst.png)
### Set device name : /dev/sdf
![6.attach-volume-of-lostsshkey-to-recoversshkey-inst-with-device-name-sdf](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/6.attach-volume-of-lostsshkey-to-recoversshkey-inst-with-device-name-sdf.png)
### SSH to RecoverSSHKey instance
![7.ssh-to-instance-recoversshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/7.ssh-to-instance-recoversshkey.png)
### Mount
![8.mount](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/8.mount.png)
### Copy authorized key then logout 
![9.copy-authorized-key-then-logout](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/9.copy-authorized-key-then-logout.png)
### Detach LostSSHKey volume
![10.detach-volume-of-lostsshkey-again](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/10.detach-volume-of-lostsshkey-again.png)
### Attach LostSSHKey again to LostSSHKey instance 
![11.attach-volume-of-lostsshkey-to-lostsshkey](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/11.attach-volume-of-lostsshkey-to-lostsshkey.png)
### Set device name : /dev/xvda
![12.attach-volume-of-lostsshkey-to-lostsshkey-inst-with-device-name-xdva](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/12.attach-volume-of-lostsshkey-to-lostsshkey-inst-with-device-name-xdva.png)
### Start LostSSHKey instance 
![13.start-lostsshkey-instance](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/13.start-lostsshkey-instance.png)

## Task 3: Delete SSH access from the EC2 security group

### Go to IAM-Roles 
![14.IAM-roles](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/14.IAM-roles.png)
### Select trusted entity 
![15.Select-trusted-entity](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/15.Select-trusted-entity.png)
### Add premissions
![16.Add-permissions](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/16.Add-permissions.png)
### Set Role Name
![17.Role-name](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/17.Role-name.png)
### Go to session manager 
![18.Session-manager](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/18.Session-manager.png)
### Start session
![19.Start-session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/19.Start-session.png)
### Choose target instance : LostSSHKey 
![20.Choose-LostSSHKey-then-start-session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/20.Choose-LostSSHKey-then-start-session.png)
### Session CLI 
![21.Session](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/21.Session.png)

## Task 4 : Install nginx on the EC2 instance (not using docker)

### 
![28.attach-new-policies-to-ec2-roles](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/28.attach-new-policies-to-ec2-roles.png)
### 
![29.find-CloudWatchFullAcesss-then-click-on-Attach-policies](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/29.find-CloudWatchFullAcesss-then-click-on-Attach-policies.png)
### 
![30.Policy-has-been-successfully-attached-to-role](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/30.Policy-has-been-successfully-attached-to-role.png)
### 
![31.install-awslogs](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/31.install-awslogs.png)
### 
![32.install-nginx-service](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/32.install-nginx-service.png)
### 
![33.curl-localhost80](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/33.curl-localhost80.png)
### 
![34.install-awslogs](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/34.install-awslogs.png)
### 
![35.go-to-awslogs.conf-and-edit](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/35.go-to-awslogs.conf-and-edit.png)
### 
![36.edit-awslogs.conf](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/36.edit-awslogs.conf.png)
### 
![37.restart-nginx-and-awslogs](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/37.restart-nginx-and-awslogs.png)
### 
![38.find-s3](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/38.find-s3.png)

## Task 5 : Create an S3 bucket
### 
![39.click-on-create-bucket](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/39.click-on-create-bucket.png)
### 
![40.type-bucket-name-then-create](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/40.type-bucket-name-then-create.png)
### 
![41.successfully-created-bucket](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/41.successfully-created-bucket.png)
### 
![42.go-to-roles-and-attach-policies](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/42.go-to-roles-and-attach-policies.png)
### 
![43.find-amazons3fullaccess-then-click-on-attach-policies](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/43.find-amazons3fullaccess-then-click-on-attach-policies.png)
### 
![44.add-cloudwatchlogsfullaccess](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/44.add-cloudwatchlogsfullaccess.png)
### 
![45.find-html-address](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/45.find-html-address.png)
### 
![46.create-.sh-file](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/46.create-.sh-file.png)
### 
![47.sync_to_nginx](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/47.sync_to_nginx.png)
### 
![48.chmod-and-set-crontab-sync-at-0-minutes](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/48.chmod-and-set-crontab-sync-at-0-minutes.png)
### 
![49.check-sync-nginx](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/49.check-sync-nginx.png)

## Task 6 : Create a CloudWatch dashboard that includes the following Metrics of all EC2 instances in Auto Scaling Group

### 
![50.go-to-cloudwatch-and-create-dashboard](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/50.go-to-cloudwatch-and-create-dashboard.png)
### 
![51.type-name-then-create](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/51.type-name-then-create.png)
### 
![52.amazon-cloudwatch-agent-config-wizard](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/52.amazon-cloudwatch-agent-config-wizard.png)
### 
![53.saved-config-file-to-config.json-successfully](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/53.saved-config-file-to-config.json-successfully.png)
### 
![54.start-the-cloudwatch-agent-on-a-server](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/54.start-the-cloudwatch-agent-on-a-server.png)
### 
![55.Install-required-packages](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/55.Install-required-packages.png)
### 
![56.set-cron-schedule](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/56.set-cron-schedule.png)
### 
![57.go-to-dashboard-and-add-widget](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/57.go-to-dashboard-and-add-widget.png)
### 
![58.select-widget-type](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/58.select-widget-type.png)
### 
![59.add-metric-graph-and-create-widget](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/59.add-metric-graph-and-create-widget.png)
### 
![60.cloudwatch-dashboard-after-added-widget](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/60.cloudwatch-dashboard-after-added-widget.png)

## Task 7 : Create CloudWatch log filter for 404 error from nginx
### 
![61.go-to-loggroups-logs-and-create-metric-filter](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/61.go-to-loggroups-logs-and-create-metric-filter.png)
### 
![62.test-pattern-with-filter-pattern-404](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/62.test-pattern-with-filter-pattern-404.png)
### 
![63.metric-details](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/63.metric-details.png)
### 
![64.review-and-create-metric-filter](https://github.com/thaivinh99/AWS-Vinh-Feb-13th/blob/main/LAB2/64.review-and-create-metric-filter.png)

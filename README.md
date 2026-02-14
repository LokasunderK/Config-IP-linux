# Config-IP-linux

1.คลิกขวาที่icon computer Web console in new tab
2.enter แล้วใส่ login:ubutu pass:ubuntu
  2.1.(ลอง ping 8.8.8.8 ได้)
3.sudo nano /etc/netplan/50-cloud-init.yaml พอenterใส่รหัส ubuntu
  จะมีip address เครื่องเรา, dns server(8.8.8.8), via คือip gateway
4.แก้ ip address ,gateway แล้วกด ctrl+o แล้ว ctrl+x เพื่อออกไฟล์
5.sudo netplan apply แล้ว enter
6.ลอง ping 8.8.8.8

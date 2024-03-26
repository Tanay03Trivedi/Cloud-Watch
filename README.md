# Cloud-Watch
### using cloud-watch when CPU usage on the ec2 instance surpasses the limit
## Create a EC2 Instance

![Screenshot 2024-03-27 035225](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/9f47c667-b636-444d-b09c-2d1b741e549f)

## Opean CloudWatch
### Go to Alarm -> create alarm -> in select matric  browse for CPU utilization and select the created instance

![Screenshot 2024-03-27 041052](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/07ace379-bb30-4316-adb1-8e8a481c1035)

### set threshold static to >= 50%

![Screenshot 2024-03-27 041200](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/079a9193-2806-41c2-8205-445e1260fb84)

### Create a notification add email where you get an alert

![Screenshot 2024-03-27 041349](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/b7b31df3-91a3-49d5-a3a9-1043fcc64cf2)

### Check the mailbox and confirm the subscription

![Screenshot 2024-03-27 041908](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/bdc17228-461a-4280-9cbc-6d81df80c07f)

### Give alarm name and description

![Screenshot 2024-03-27 041831](https://github.com/Tanay03Trivedi/Cloud-Watch/assets/160705084/a0e7a6ee-198c-409a-ac52-0e5067a7b2bb)

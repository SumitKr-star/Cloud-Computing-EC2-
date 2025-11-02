# Cloud-Computing-EC2-
## I. Launch instance
## Launch EC2 Instance on AWS
1. Go to AWS Console, then EC2, then Launch Instance.
2. Choose Ubuntu as the operating system.
3. Create and use a key pair for SSH access.
4. Use PuTTY to connect to the instance.
5. Allow the following inbound ports in the security group:<br>
&nbsp;&nbsp;=>HTTP (80)<br>
&nbsp;&nbsp;=>HTTPS (443)<br>
&nbsp;&nbsp;=>SSH (22)<br>
6. Launch the instance.<br>
<img width="1014" height="503" alt="image" src="https://github.com/user-attachments/assets/88f8b6a8-50f3-4833-a1ce-8c9fdb15e959" />
<br>

```
# II. Connect to EC2 Instance (Using PuTTY/SSH) 
1. Download the putty.exe file and install it on your device.<br>
2. Open PuTTY.<br>
3. Go to Connection > SSH > Auth.<br>
4. Choose the key pair file (.ppk) you created while launching the instance.<br>
5. Connect to your EC2 instance using the instance’s public DNS or IP address.<br>
```
login as username: ubuntu
```
```
<br>
# III. Install Apache<br>
Check in browser → http://yourpublicip
<br>
An Apache page will be shown at your public IP.<br>
```
cd /var/www/html <br>
sudo rm index.html <br>
 sudo vi index.html<br>
```
Press I to insert your own html code.<br>
Write your own code.<br>
After writing all code, Press Ctrl+C and then write ":wq" and Press Enter.

# ssh-remote-server
Setup a remote linux server and configure it to allow SSH connections.

##Steps
1. Create an account on DigitalOcean 
2. Launched a remote Linux server (EC2 or Ubuntu)
3. Create two new SSH key pairs on your local machine (Windows, Mac or linux)
4. Add the public keys generated to the server's authorized keys
5. Connect to your remote server using both keys like this:

```bash
ssh -i <path-to-private-key> user@server-ip
```
(optional) Install and configure Fail2Ban to prevent brute-force login attempts.




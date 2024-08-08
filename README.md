# HTB I can't access to web pages after connect vpn 
if you can't access to web pages just reload without display anything in Hack The Box machines <br>



# Their are many solutions : <br>
1. you can try another vpn region and try to switch between TCP and UDP too.
2. if the first one doesn't work try this : <br>

### you see i can ping it but why can't access to web page the problem maybe be localhost issue <br>

![Screenshot from 2024-08-07 19-22-34](https://github.com/user-attachments/assets/dfcc7339-29e0-4e5c-bf20-87227fdd4270) <br>

so type `sudo nano /etc/hosts` be careful hosts not host , necessary `sudo` command to get permission to write this file <br>

![Screenshot from 2024-08-07 19-41-04](https://github.com/user-attachments/assets/2a3686c8-bb0b-4ebf-8b43-e4b9dcea38bd) <br>

Now type `ip_machine`  `website_domain` between of them tab (you can see 10.10.11.221  2million.htb)

![Screenshot from 2024-08-07 19-41-48](https://github.com/user-attachments/assets/011a0dbd-94bb-4264-8933-13e5dcd6a8fd) <br>

you can get the `website_domain` from url after stop reload the website 

![Screenshot from 2024-08-07 20-05-55](https://github.com/user-attachments/assets/1a1c8f1a-415c-4c54-ad28-9855537f9389)


Then press `Ctrl+x` , type `y` or `yes` and `Enter` <br>


### you can see the website now 

![Screenshot from 2024-08-07 20-09-00](https://github.com/user-attachments/assets/fbae0d96-d733-4ebc-bc86-053fb6530dac)





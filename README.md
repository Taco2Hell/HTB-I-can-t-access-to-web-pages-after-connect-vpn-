# HTB-I-can-t-access-to-web-pages-after-connect-vpn-
### if you can't access to web pages just reload without display anything <br>



# Their are many solutions : <br>
1. you can try another vpn region and try to switch between TCP and UDP too.
2. if the first one doesn't work try this : <br>

### you can see i can ping it but why can't access to web page the problem maybe be localhost issue <br>
![Screenshot from 2024-08-07 19-22-34](https://github.com/user-attachments/assets/24be9bb4-e209-483d-8934-d070ccf0c697) <br>

### so type `nano /etc/hosts` be careful hosts not host  <br>

![Screenshot from 2024-08-07 19-41-04](https://github.com/user-attachments/assets/2a3686c8-bb0b-4ebf-8b43-e4b9dcea38bd) <br>

Now type <ip>  <domain>

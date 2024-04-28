1. Run in command prompt to generate SSL key:

    ```
    ssh-keygen -t rsa -b 2048
    ```
   We can find this command in gitlab (User Icon/preference/SSH keys/add new key in that --> click learn more.)

2. After click enter we will asked for password ect..., put empty and click enter.

3. You will find the key saved location.
   EX: Your public key has been saved in C:\Users\Vijaykumar_Guntreddy/.ssh/id_rsa.pub.

4. Open id_rsa.pub file in notepad editor. We will get key. Copy from "ssh-rsa......" and paste in gitlab ssh key box.

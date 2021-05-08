## kali linux GUI setup in WSL

1. Enable windows insider
2. update
3. Update wsl `wsl --update`
4. Install kali `wsl --install -d kali-linux`
5. *in kali*
6. `sudo apt update`
7. `sudo apt upgrade -y`
8. `sudo apt install -y kali-desktop-xfce`

You can try `apt install kali-win-kex` but not been able to get it to work 'connection refused 16001' errno=11

use `sudo apt install xrdp -y`

`sudo service xrdp start`

find ip address `ip add`

see [https://www.youtube.com/watch?v=AfVH54edAHU](https://www.youtube.com/watch?v=AfVH54edAHU) for a nice video. 

mstsc -the ip address.

`sudo apt install -y kali-linux-everything` to install the world.

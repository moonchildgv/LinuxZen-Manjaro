# Linux-Zen on Manjaro

Maybe you don't know that to install the Linux-zen on manjaro it is not possible through the mirrorlists of the distro (neither through Pacman nor through Yay). But it is possible to circumvent the problem with simple steps.

***Why install zen kernel?***

- It a kernel tuned for performance, aimed at improving performance of 
  desktops at the cost of throughput and power usage. It is also sometimes
   considered the best kernel for gaming. It has a low latency and 
  high-frequency scheduling. The kernel facilitates faster speeds and features a more optimized scheduler.
1. to install it you need to go to: 

    https://pkgs.org/search/?q=linux-zen

![linux-zen](https://user-images.githubusercontent.com/34889283/233870450-6cd083f0-48ff-448c-bd42-30b994a49d59.jpg)

2. click on it and go down to the item Download:

![linux-zen1](https://user-images.githubusercontent.com/34889283/233870493-54d09202-de28-4cdf-950d-fbee517812ea.jpg)

3. now write on terminal: wget + link just copied (in this case):
   
   ```bash
   wget https://ftp5.gwdg.de/pub/linux/archlinux/extra/os/x86_64/linux-zen-6.2.12.zen1-1-x86_64.pkg.tar.zst
   ```

4. once concluded you will have a file that you will have to install using the command:
   
   ```bash
   sudo pacman -U linux-zen-6.2.12.zen1-1-x86_64.pkg.tar.zst
   ```

5. finished the installation reboot, and check with the following command if the installation was successful:
   
   ```bash
   uname -r
   ```
ENJOY!! 😜


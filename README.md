![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/f696abf5-ea5c-42f5-b481-28c5a0b8a5fe)

![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/64ac641a-369b-48bf-a380-649a3916683e)


<h1>Installing Software in a Linux Distribution</h1>
This tutorial outlines how to install and uninstall applications in Linux, using Linux commands in a Bash shell, and using APT package manager to install Suricata and tcpdump.<br />

<h2>Exercises for the lab.</h2>

- 1 Ensure that APT is installed.
- 2 Install -and- uninstall Suricata.
- 3 Install tcpdump.
- 4 List installed applications.
- 5 Reinstall suricata.
- 6 Show new list of applications.


<h2>The ($) is your prompt, ths is where you will enter your commands.</h2>

Step 1: Enter apt and then press enter, then press enter again.  
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/03c60731-c668-49d3-a8e2-a3dae4ca6034)

Step 2: 2a) Enter sudo apt install suricata press enter, then press enter again.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/b86b82a9-4178-44e2-9ec4-24b2812707e8)



2b) Enter suricata and press enter.  This verifies the installation of suricata.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/0df6ca24-14f3-4c52-8174-46535953e205)


2c) Enter sudo apt remove suricata press enter, then press enter again.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/226dbac1-0f78-45ab-981e-dbb1fb5b9735)

2d) Verify that suricata is uninstalled.  You will know suricata is uninstalled when you see -bash:/usr/bin/suricata: No such file or directory.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/a43b92ca-3621-4d5b-8832-c71c414db8a6)


Step 3: Enter sudo apt install tcpdump and press enter, then press enter again.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/e8c95676-6624-43a3-9e56-6f6f13848547)


Step 4: Enter apt list --installed then enter.  This will allow you to view the installed files.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/3610b893-5493-4d2c-bac2-33c4566ee57e)

Step 5: Enter sudo apt installs suricata then enter, then enter again.  This reinstall suricata.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/231ef3a9-4ab9-447c-b774-fa14eb24a3f0)


</p>
<br />

<p>


Step 6: Enter sudo apt List --installed then enter to display the installed labs.
![image](https://github.com/TDCybersecurity/osticket-prereqs/assets/142702123/cec62bf4-e756-4f3e-aabd-cfefd27f985c)

</p>
<br />

<p>

</p>
<p>
We have explored how to use APT to install and uninstall packages, verify an installed app, remove an installed app, and list all apps.  Understanding APT is essential for maintaining a healthy Linux system, ensuring you have the right software at your fingertips, and keeping your system secure and up-to-date.</p>
<br /># Linux APT Application Package Tool

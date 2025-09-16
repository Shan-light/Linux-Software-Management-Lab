# Linux-Software-Management-Lab
Experienced in APT package manager Installing, Updating, and Removing Linux Software.
## Objective

Gain hands-on experience using the Advanced Package Tool (APT) and sudo in a Debian-based Linux environment to install and uninstall applications utilizing the Bash shell.
Practical experiance managing software packages by working with network security tools such as Suricata and tcpdump, using a virtual environment ensuring controlled and safe space.

## Skills Learned

- Experienced in APT package management.
- Installation, updating, and removal of linux software packages over Debian based system using APT.

## Tools Used

- APT
- Bash Shell
  
## Steps
### 1. Confirmed that APT package manager was installed in the Linux environment.
<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/7c70f9efa8f9030ba8d38b5d5a16dcd91f047801/images/task1.1.1-ensure%20apt%20installed.png"/>
*Image 1: Task 1*

- When apt is installed, it will display basic usage information by typing the command "apt". Information such as the version information and the description of the tool as seen above in the image. APT is the recommended         package manager for Debian-based systems, and is usually installed by default in the Linux Bash shell.

### 2. Use the APT package manager to install and remove Suricata application.
  - To install and uninstall software on Linux systems elevated privileges are required, and can be done by using the "sudo", if the user have these privileges.
<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/a5d422b5120a5f5f9b00dd44b87eaf640d07c533/images/task2.11%20install%20suricata.png"/>

*Image 2.1: Task 2*

<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/fab93dacb2df6a0b65d54406b54326fed63dc307/images/task2.2%20verify%20suricata%20installed.png">
*Image 2.2: Task 2*

<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/1ae63b656930005bf469af5719957c50ef846810/images/task2.3%20remove%20suricata.png">
*Image 2.3: Task 2*

  - Suricata is a network analysis tool used for intrusion detection and prevention. Suricata was installed by typing the command "sudo apt install suricata" in image 2.1. Installation was verified typing the command "suricata" in image 2.2. And suricata was uninstalled typing commands " sudo apt remove suricata" in image 2.3 can be seen the image above. When Suricata is installed, the version and usage information will be listed by running "suricata"


### 3.Install tcpdump application

  - The APT package manager was used to install tcpdump with "sudo apt install tcpdump" command.
<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/1aa92ffead19f1a4c29fe1150f07d009581b6803/images/task3%20install%20tcpdump.png">
*Image 3: Task 3*

  - Tcpdump is a command-line tool used to capture network traffic in a Linux Bash shell system seen in the image above.

### 4. List the installed applications.

  - APT package manager was used to list all installed applications.
<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/83a36dec52b58f02a975dda91e822347cc8f6191/images/task4%20list.png">
*Image 4.1: Task 4*

  - It is important to check that the correct applications are installed and the correct versions are installed as well. A long list of applications will be produced typing "apt list --installed", because Linux has lots of softwares installed by default seen in the image above.

<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/bb247d3a866911af6f6f599913897cad8ac7b42f/images/task4.2%20tcpdump%20in%20list.png">

*Image 4.2: Task 4*

  - The list was searched to find tcpdump application, to ensure it was installed, it is highlighted in the image above.

### 5. Reinstall Suricata application
  - Suricata was reinstalled by typing the command "sudo apt install suricata".

 <img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/5e52f59e3df57ef9d54c12fb04dea15473b7bd4e/images/task5%20reinstall%20suricata.png">
*Image 5.1: Task 5*

  - The application list was searched to confirm that Suricata application was installed using the command "apt list --installed", highlighted in the image below.
<img src="https://github.com/Shan-light/Linux-Software-Management-Lab/blob/5e52f59e3df57ef9d54c12fb04dea15473b7bd4e/images/task5.2%20suricata%20in%20list.png">
*Image 5.2: Task 5*

 

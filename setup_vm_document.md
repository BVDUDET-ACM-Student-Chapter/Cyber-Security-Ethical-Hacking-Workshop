# Setting Up a Virtual Machine for Cyber Security and Ethical Hacking Workshop
In this document, we'll guide you through setting up a virtual machine (VM) environment for a Cyber Security and Ethical Hacking workshop. This setup will provide you with a safe and isolated environment to practice various security techniques without impacting your primary operating system.

## Step 1: Choose a Virtualization Software
You'll need virtualization software to create and run virtual machines on your computer. Popular choices include:

- **VirtualBox**: A free and open-source virtualization platform available for Windows, macOS, and Linux.
- **VMware Workstation**: A commercial virtualization platform with advanced features. Available for Windows and Linux.
- **Hyper-V**: A virtualization platform included with Windows 10 Pro, Enterprise, and Server editions.
For the purpose of this guide, we'll use VirtualBox as it's free and widely accessible.

## Step 2: Download and Install VirtualBox
Visit the [VirtualBox website](https://www.virtualbox.org/) and download the installer for your operating system.
Follow the installation instructions provided on the website or included with the installer.
## Step 3: Download a Virtual Machine Image
There are various pre-configured virtual machine images available for security testing and ethical hacking. One popular option is Kali Linux, a Debian-based Linux distribution designed for digital forensics and penetration testing.

Go to the [Kali Linux downloads page](https://www.kali.org/get-kali/#kali-virtual-machines) `Fast Download via Torrent`. and download the appropriate version for VirtualBox.
Ensure you download the Pre-builts VMs - VirtualBox image specifically designed for VirtualBox.
## Step 4: Import Pre-Made Kali VirtualBox VM
Importing the Kali VirtualBox image is very easy.

We first need to extract the VirtualBox image:
```
kali@kali:~$ 7z x kali-linux-2023.4-virtualbox-amd64.7z
[...]
kali@kali:~$
```
If we are using Windows we can instead use the [official 7z app](https://www.7-zip.org/download.html).

We then launch VirtualBox:

![image](https://github.com/Kamran1819G/Cyber-Security-Ethical-Hacking-Workshop/assets/72748315/772ac1aa-69e8-4b5c-959a-ade850ef241c)


From here we will be wanting to select ‘Add’. We then navigate to the location our VM is downloaded and find the `.vbox` file:

![image](https://github.com/Kamran1819G/Cyber-Security-Ethical-Hacking-Workshop/assets/72748315/fc06a47d-6dbd-4289-97c8-b1acf0f87246)

We select this then we are able to continue forward:

![image](https://github.com/Kamran1819G/Cyber-Security-Ethical-Hacking-Workshop/assets/72748315/95d1d344-fbeb-44a9-86ce-3edd6fbcb564)


We can verify the settings that will be set here, and if we need to change any we can. Once we are happy we can select boot the VM and use it as normal. Remember the `default login is kali for the user and kali for the password!`
## Step 5: Configure Virtual Machine Settings
Before starting the virtual machine, it's a good idea to review and adjust its settings:

Select the imported virtual machine in VirtualBox.
Click on "Settings."
Adjust settings such as memory, CPU cores, network adapters, etc., according to your requirements.
Ensure that the virtual machine's network adapter is configured properly for your workshop environment.
## Step 6: Start the Virtual Machine
With the virtual machine selected in VirtualBox, click on the "Start" button.
VirtualBox will boot the virtual machine, and you should see the Kali Linux desktop after a few moments.
## Step 7: Explore and Secure Your Virtual Environment
Now that your virtual machine is set up, take some time to explore Kali Linux and its tools. Familiarize yourself with the interface and available applications. Additionally, ensure that you understand how to secure your virtual environment, such as updating software, configuring firewalls, and setting up network security measures.

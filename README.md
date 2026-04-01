# Ubuntu-Linux-VM-
## Summary
In this project, I set up an Ubuntu virtual machine on a Windows 11 host using Oracle VirtualBox. The project focused not only on installation, but also on documenting configuration decisions, troubleshooting issues, and validating that the virtual machine ran correctly after setup.
##	Why I Did This Project
I wanted hands-on experience with virtualization and Linux environments. Setting up Ubuntu VM allowed me to practice working with ISO images, VM resource allocation, boot configuration, and installation troubleshooting in a real-world scenario.

##	Environment
- Host OS: Windows 11
- Virtualization Software: Oracle VirtualBox
- Guest OS: Ubuntu Linux
- Installation Media: Ubuntu Linux ISO

## Process

### 1. Prepared the environment
I installed Oracle VirtualBox on my Windows 11 machine and downloaded the Ubuntu Linux ISO from the official source.

### 2. Created the virtual machine
I created a new VM in VirtualBox, selected the Linux operating system type, and assigned memory and storage resources appropriate for the installation.

### 3. Attached the ISO
I configured the virtual optical drive and attached the Ubuntu Linux ISO so the VM could boot into the installer.

### 4. Installed Ubuntu Linux
I launched the VM and proceeded through the operating system installation process.

### 5. Troubleshot setup issues
During setup, I encountered issues related to ISO recognition and VM configuration. I reviewed the file path, confirmed the ISO format, and adjusted settings to get the installation working. I also had an issue with the Graphics controller, where I had to adjust it so the VM could run. 

### 6. Verified system functionality
After installation, I confirmed that the VM successfully booted into Ubuntu Linux and could be used as a functional guest operating system.

##	Key Challenges
- VirtualBox did not initially recognize the ISO file
- VM startup produced installation-related errors
- Resource and configuration settings needed adjustment

##	How I Solved Them
- Verified the ISO download completed correctly
- Confirmed the file was stored in the correct location
- Reviewed and adjusted system settings in VirtualBox
- Changed the graphics controller setting correctly
- Re-tested the machine after each change

##	Outcome
The project resulted in a working Ubuntu Linux virtual machine on Windows 11. More importantly, it gave me practical experience in virtualization, system setup, and structured technical troubleshooting.

##	Skills Demonstrated
- Virtual machine setup
- Operating system installation
- Troubleshooting
- Technical documentation
- Basic Linux lab preparation

##	Screenshots
See the screenshots folder for images of the setup process, errors encountered, and successful installation.

## Author
Jose Aybar

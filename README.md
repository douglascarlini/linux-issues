# Linux Issues FIX
Commands and scripts to fix some issues on Linux

### Problems with VMs (on Windows)

- Shut down the Virtual Machine.
- Press Windows logo key + X, then hit A to run Command Prompt(powershell) as administrator.
- Type bcdedit /set hypervisorlaunchtype off
- When you see"The operation completed succesfully", reboot your windows. After reboot, boot your VM and update/upgrade.

**source:** https://stackoverflow.com/questions/61192026/how-do-i-solve-hash-sum-mismatch-on-apt-get-install-docker-ce

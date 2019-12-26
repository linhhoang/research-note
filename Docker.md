1. Switching between Docker and VirtualBox on Windows 10
  There is a conflict between Docker and VirtualBox.
  ###To use Docker:
  #### Run from elevated prompt (admin privileges)
  > bcdedit /set hypervisorlaunchtype auto

  ###To use VirtualBox:
  #### Run from elevated prompt (admin privileges)
  > bcdedit /set hypervisorlaunchtype off
  A reboot is required in both cases.

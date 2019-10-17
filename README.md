# Ansible-GTAV-LauncherFix
  
Rockstar Games new launcher broke my Steam (Linux) install of GTA-V.  


I saw discussions on Reddit that some people got it working after installing the No_GTAVLauncher mod. 
This playbook downloads and installs the mod while making a backup of the original executable. It should "just work" for lazy folk like me.
  
Run `ansible-playbook Fix-GTVA-Linux.yml` and then you're all set to run the game from Steam as usual.
  
The `{{ installdir }}` variable can be changed if it doesn't match your own

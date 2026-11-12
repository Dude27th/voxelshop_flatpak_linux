# VoxelShop_Flatpak_Linux
<img width="1600" height="900" alt="Captura de pantalla de 2026-11-09 04-13-13" src="https://github.com/user-attachments/assets/232f161b-c873-4b45-b833-d99266c4a34d" />


## What is this?
Unofficial repackage of VoxelShop as a Flatpak and containerized Java Runtime Environment (JRE8).

This approach was chosen because the current version of VoxelShop (1.8.26) doesn't work properly with the stated required version of the JRE.
At the same time setting up Java on Linux is a pain as one size doesn't fit all, so a containerized approach with a tested JRE version should work better.

## Why not upload this directly to Flathub?
This Flatpak doesn't comply with the submit requirements of Flathub.  
I understand their decision.  

So if you, ***the reader*** can do this again and make it comply with Flathub please do, so Voxelshop can be used by more people.

## Why not pushing this onto the official repository?
The official repository has been inactive by almost 8 years at this point.  
The development is presumed abandoned.  
So hopefully this helps someone out there trying to run this program on Linux ^^  

Yes, you can also run an older windows version trough Proton, but this has the latest VoxelShop version released.



# Installation:
Download the "VoxelShop_1_8_26" Flatpak file to a directory with user privileges, your "Downloads" folder should do.  
Install the flatpak by running from terminal:  
- flatpak install --user VoxelShop_1_8_26.flatpak  
or  
- flatpak install --user VoxelShop_1_8_261.flatpak  
  
You can open VoxelShop by running:  
- flatpak run com.vitco.VoxelShop  
  
Or you can just log off and log in from your session.  
The VoxelShop program should at this point be added to your menu ^^

# Uninstall:
If you ever need to uninstall this Flatpak just run from terminal:
-  flatpak uninstall --user com.vitco.VoxelShop

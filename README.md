# FOR PERSONAL USE, USE AT YOUR OWN RISK!!!

# PS4-GPU-DRIVER
Modified drivers for ps4 gpu

Patches are in patches

Driver to compile are inside Compile

ps4-video-drivers

Video drivers required to use 3d hardware acceleration on Arch Linux. Original patches from failoverflow: https://github.com/fail0verflow/ps4-radeon-patches

and   Ps3itaTeam   https://github.com/Ps3itaTeam/ps4linux-video-drivers

Just set up a repository where you can get pre-patched video drivers for ps4

    Add the repository to /etc/pacman.conf
    
    sudo echo -e "\n [ps4-gpu-driver-repo] SigLevel = Never Server = https://bercraft.github.io/$repo/$arch

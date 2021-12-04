# PS4-GPU-DRIVER
Modified drivers for ps4 gpu

Updated on 01/12/2021

Patches are in patches

Driver to compile are inside Compile

ps4-video-drivers

Video drivers required to use 3d hardware acceleration on Arch Linux. Original patches from failoverflow: https://github.com/fail0verflow/ps4-radeon-patches

We just set up a repository where you can get pre-patched video drivers for ps4

    Add the repository to /etc/pacman.conf
    
    sudo echo -e "\n [ps4-gpu-driver-repo] SigLevel = Never Server = https://bercraft.github.io/$repo/$arch

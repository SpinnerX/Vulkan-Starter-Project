# Vulkan Starter project
* For testing if vulkan is fully working
* At least for ubuntu 22.04 it does.

# Installation that works for Ubuntu 22.04
```
wget -qO- https://packages.lunarg.com/lunarg-signing-key-pub.asc | sudo tee /etc/apt/trusted.gpg.d/lunarg.asc
sudo wget -qO /etc/apt/sources.list.d/lunarg-vulkan-jammy.list http://packages.lunarg.com/vulkan/lunarg-vulkan-jammy.list
sudo apt update
sudo apt install vulkan-sdk
```
* Link to the installation `https://vulkan.lunarg.com/doc/view/latest/linux/getting_started_ubuntu.html`

# ubuntu_cloud_init
A sample cloud-init file used for [autoinstall](https://canonical-subiquity.readthedocs-hosted.com/en/latest/index.html) of Ubuntu Server.  

You can find more references on the [autoinstall configuration](https://canonical-subiquity.readthedocs-hosted.com/en/latest/reference/autoinstall-reference.html) page.  

## **How to Run It**  
1. Write a `user-data` file based on your use case.  
2. Rebuild the Ubuntu image with your `user-data`. In our case, we use [PXEless](https://github.com/cloudymax/pxeless/), a powerful Docker-based tool, to build the image.  
3. Create a bootable USB with the image that contains your `user-data`.  

This works on Ubuntu 22.04.5 LTS.  

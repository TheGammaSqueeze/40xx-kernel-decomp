# 40xx-kernel-decomp
The contains the decompiled BSP kernel that ships with the Anbernic RG40xx.

The purpose of this is to make modifications to the joypad driver, as there are hard coded values in the driver built into the shipped kernel, and we have no sources.
I have kept both the modded and stock kernel images in this project for comparison.

The function you want to focus on in this project will be called "sticks".
My knowledge around this driver is limited, but I've made some tweaks to values which can be viewed here.

In order to open this project, you will need to modify the OWNER in 40xx-kernel.rep/project.prp to match your currently logged in username.

Screenshots of the decomp:
![image](https://github.com/user-attachments/assets/d9dbeb73-8800-4f4d-a31d-6cc22a3a70fd)
![image](https://github.com/user-attachments/assets/769eb93a-54a6-4d03-9ac5-000b3ced64e9)

I have modified this to a positive effect as seen here: https://x.com/TheGammaSqueeze/status/1819470408485425411

**Use bord**：RK3566/8    

**OS:** Debian system

**Downloads:**

[nxwitness-client-5.0.0.35745-linux_arm64.deb](https://1drv.ms/u/s!AqvWy-LFD_JhijUws4uXhY2QId7z?e=fu33Cr) 

[nxwitness-client-5.0.0.35745-windows_x64.exe](https://1drv.ms/u/s!AqvWy-LFD_JhijO370vXVbTdSAYY?e=3jRqrJ) 

[NXWITNESS-server-5.0.0.35745-linux_arm64.deb](https://1drv.ms/u/s!AqvWy-LFD_JhijSlUjAT7wAtWPDc?e=gwp27x) 





# 1、First update source

```
sudo apt update
```

# 2、Install client and server

## 	**Install client**

```
sudo dpkg -i nxwitness-client-5.0.0.35745-linux_arm64.deb
```

![image-20230225174507370](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20230225174507370.png)

If you encounter this situation, install [[libxcb-util1](http://ftp.br.debian.org/debian/pool/main/x/xcb-util/)]

![image-20230225175044949](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20230225175044949.png)

After installing **libxcb-util1**,  again install **nxwitness-client-5.0.0.35745-linux_arm64.deb** success

## 	**Install server**

```
sudo dpkg -i NXWITNESS-server-5.0.0.35745-linux_arm64.deb
```

# 3、Nx Witness Quick Start Guide


# linux_fundamentals
This project covers the essential concepts of Linux system setup, package management, and remote server connectivity. Below are the steps taken to complete all required tasks successfully.

## Steps Completed

### 1. Launching an EC2 Instance
- A cloud-based **EC2 instance** was successfully launched.
![amazon_ec2_launch](./img/img1_ec2instance.png)

![amazon_ec2_launchsuccessful](./img/img1_ec2instance2.png)

### 2. Connecting to the Server
- Connected and logged into the **EC2 instance** using **MobaXterm** via SSH. 
![connected_to_server](./img/img3_ec2instanceloggedin.png)

### 3. Installing, Updating, and Removing Software
#### **Updating Package Lists**
- Ran the command:
  ```bash
  sudo apt update
![update_package_list](./img/img4_ec2instanceupdate.png)


- Installing Software:
  ```bash
  sudo apt install tree
![update_package_list](./img/img5_ec2instanceinstalltree.png)

- Verified installation with:
  ```bash
  tree / 1
![update_package_list](./img/img5_ec2instanceconfirmtree.png)

- Updated installed packages with:
  ```bash
  sudo apt upgrade
![update_package_list](./img/img6_ec2instanceinstalledupgrades.png)


- Removed the Tree package using:
  ```bash
  sudo apt remove tree
![update_package_list](./img/img7_ec2instanceremoveinstalled.png)


### 4. Additional Practice - Installing Nginx
#### **Installed Nginx as an additional practice step**
- Ran the command:
  ```bash
  sudo apt install nginx
![update_package_list](./img/img8_ec2instanceinstallnginx.png)

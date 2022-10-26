# RaspberryPi-OS-Monitorless-Setup

Raspberry Pi Installation
The steps that enable Raspberry Pi installation to be done via SD Card are explained below.
The SD Card to be used for Raspberry Pi must be at least 8GB in size and formatted.
The SD Memory Card Formatter program is installed by clicking the appropriate link for your operating system on the https://www.sdcard.org/downloads/formatter/ link.

![1](https://user-images.githubusercontent.com/13950138/197998325-67ba37c9-589c-40a7-b94c-651896b90cb5.png)

The SD Card to be formatted is selected and the formatting process is completed.

![2](https://user-images.githubusercontent.com/13950138/197998335-62b9d492-bfd5-438f-9ba2-b2de065f34b7.png)

To install the operating system, the download is provided by clicking the link appropriate to the computer that you use from the link https://www.raspberrypi.com/software/.

![3](https://user-images.githubusercontent.com/13950138/197998337-48af4299-06af-4816-9f68-fcf750d446b0.png)

The installation process of the Imager program starts.

![4](https://user-images.githubusercontent.com/13950138/197998342-d1eef5d4-02b9-4aba-90e6-563e4771ee71.png)
![5](https://user-images.githubusercontent.com/13950138/197998344-3ed5e23f-2abf-460f-ac12-590ec01880b0.png)

Raspberry Pi Image Manager will open automatically.

![6](https://user-images.githubusercontent.com/13950138/197998348-4ec577a8-4f1e-4743-adf2-a70dab2eaa75.png)
 
“Raspberry Pi OS” for Raspberry Pi and the SD Card to be installed are selected as the operating system.

![7](https://user-images.githubusercontent.com/13950138/197998353-a84e7fe8-03ef-4eaa-b198-f16fa8a856bc.png)
![8](https://user-images.githubusercontent.com/13950138/197998355-d11d1167-318e-400c-86d2-7ed94ced9ea4.png)
  
By clicking the Settings button, Username - Password is set and saved, and the "WRITE" button is clicked.

![9](https://user-images.githubusercontent.com/13950138/197998358-73cf3d22-6cbf-4ca8-9462-9e17ac6922a9.png)
 
The operating system starts to install.

![10](https://user-images.githubusercontent.com/13950138/197998360-1e48bb76-849a-46e5-97c7-c194980412f9.png)
 
When the installation process is completed successfully, the "CONTINUE" button is clicked when it gives the warning on the screen.

![11](https://user-images.githubusercontent.com/13950138/197998362-78d1917f-7052-4e0e-ba43-0d133e0ded5a.png)
 
SD Card is removed and reinserted. The file named “ssh”, which is empty and without extension, and the file named “wpa_supplicant.conf”, which contains the wi-fi connection information as shown below, are thrown into it.

![12](https://user-images.githubusercontent.com/13950138/197998365-30fe060a-e066-470b-b33e-c40a524cb778.png)
![13](https://user-images.githubusercontent.com/13950138/197998366-18438be6-7443-44fe-8ea4-b37189840b4b.png)

The SD Card is removed and placed in the slot on the Raspberry Pi. The power adapter is plugged in and powered up. To learn the IP address of Raspberry Pi, download the "Fing" program from the link https://www.fing.com/products/fing-desktop.

![14](https://user-images.githubusercontent.com/13950138/197998370-8fae1042-80fd-4e70-9ac0-ca3f7d82fbc9.png)

From Devices, the information that Raspberry Pi is connected to the network and its ip address will be visible.

![15](https://user-images.githubusercontent.com/13950138/197998373-3de01cf3-672e-4981-b4e3-edaa7c0bdc1e.png)
 
To make Raspberry Pi interface settings, the PuTTY program is downloaded from the link https://www.putty.org/.

![16](https://user-images.githubusercontent.com/13950138/197998376-ded035dc-755a-4443-8716-9b0de5d90685.png)

By opening PuTTY, the IP address we learned with Fing is written in the relevant field and the "Open" button is clicked.
 
![17](https://user-images.githubusercontent.com/13950138/197998379-57f4fbdc-0099-47aa-b09a-14800bd283db.png)
 
Click the "Accept" button in the warning.

![18](https://user-images.githubusercontent.com/13950138/197998384-bb52c29b-6489-4fd1-95ec-d148fc270689.png)
 
On the next screen, first enter the username: pi and click "Enter". Next comes the password field. Enter the password and click the "Enter" button again.
 
![19](https://user-images.githubusercontent.com/13950138/197998389-31c44156-bbd0-4925-830a-c865f56d54b3.png)
 
With the command entered, the steps that will activate accessing the Raspberry Pi's interface will be executed.

![20](https://user-images.githubusercontent.com/13950138/197998391-623be61c-82ff-4873-a399-0a3680a4cad5.png)

Interface Options is selected.

![21](https://user-images.githubusercontent.com/13950138/197998393-216f9b44-c4c7-4e40-9e25-5f9482765315.png)
 
VNC is enabled.

![22](https://user-images.githubusercontent.com/13950138/197998397-76546ed1-0222-4b45-b2d5-5add6d56d92b.png)
 
PuTTY is closed. VNC Viewer program is downloaded and installed from https://www.realvnc.com/en/connect/download/viewer/ to access the interface.

![23](https://user-images.githubusercontent.com/13950138/197998401-ce507301-b192-4b7c-ba8c-3743ccbc014b.png)
 
The VNC Viewer program is run and the Raspberry Pi's IP address is entered in the relevant field.

![24](https://user-images.githubusercontent.com/13950138/197998404-4a00ea55-413a-4d0c-8588-6ac1beb44725.png)
 
Access to the interface of Raspberry Pi is provided. Since it will run slowly at the first boot, a reboot is done once.

![25](https://user-images.githubusercontent.com/13950138/197998407-ccaa7568-aa81-4378-a0cd-8c776ccbcdbf.png)
 
“Raspberry Pi Configuration” opens for language and region settings.

![26](https://user-images.githubusercontent.com/13950138/197998411-29aaab40-fa08-4132-800b-1d9e10bb79c7.png)
 
The Localization tab opens. Locale for language and Timezone for time zone are set and saved. After saving, Raspberry Pi restarts with its current state.

![27](https://user-images.githubusercontent.com/13950138/197998414-b4652f61-3504-476a-af67-ce3020e8ae84.png)
 
Font and size are set with Appearance Settings.

![28](https://user-images.githubusercontent.com/13950138/197998418-b249f448-157e-4d9c-916b-56af5dba1e3f.png)
![29](https://user-images.githubusercontent.com/13950138/197998422-cd89fd65-2ddd-4cf7-a869-2287977f1c2b.png)

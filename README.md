In this lab, I demonstrated remote access to both a Windows Server 2022 virtual machine and a Linux Mint virtual machine from my host system running Windows 11 Home.

Step 1, open VirtualBox and ensure that your WS22 VM is connnected to a Bridged Network with the Host computer.

![Ensure WS22 Connected via Brided network ](https://github.com/user-attachments/assets/2516446c-22ef-4cfa-8436-27d76bfd674a)

Step 2, in WS22 Allow Remote connections and ensure that Remote Desktop Protocol (RDP) is checked.

![Allow Remote Connections](https://github.com/user-attachments/assets/747eca43-7e3c-488f-abbb-f0eeb7e2da87)
![Ensure RDP](https://github.com/user-attachments/assets/e20f501d-028a-49c6-8f9d-95cb0b48e2c9)

Step 3, open Remote Desktop Connections on the host computer. 

![Open Remote Desktop connection on Host ](https://github.com/user-attachments/assets/57528994-d5fd-4aa8-83cf-e404eaf4daec)

Step 4, Remote in to the WS22 VM.

![Remote in](https://github.com/user-attachments/assets/5a11e696-805b-49ab-8320-655ffb8b6bd1)

Remoting into Linux Mint

Step 1, install openssh server in terminal. Linux does not use RDP, therefore SSH will be needed to remote in.

![Install openssh server](https://github.com/user-attachments/assets/c340d47d-600f-4df5-8ae2-d8060a0fee68)

Step 2, start ssh.

![Start ssh](https://github.com/user-attachments/assets/1406bcd7-03dd-4f32-90e3-ec439659ef24)

Step 3, install PuTTY. This will be used to connect to the Linux VM.

![Install PuTTY](https://github.com/user-attachments/assets/1acece59-bae7-4888-b6bc-4319e86f5984)

Step 4, finally remote into the Linux VM.

![Remote into Linux](https://github.com/user-attachments/assets/47176bc9-1851-4a4d-ad07-1f47f1b359a3)




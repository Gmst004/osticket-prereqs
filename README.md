<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- 1. Create Virtual Machine.
- 2. Install Windows 10.
- 3. Remote Desk into Virtual Machine.
- 4. Enable IIS features. 
- 5. Confirm that localhost is working.

<h2>Installation Steps</h2>


<p>
<img src="![2](https://github.com/Gmst004/osticket-prereqs/assets/155221840/df81be85-796d-4a87-8a10-c89166a260da)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>In the course of setting up a Virtual Machine (VM) and a resource group in Microsoft Azure, the initial step involves creating a resource group to serve as a logical container for the related resources within the Azure environment. Once the resource group is established, the focus shifts to configuring and deploying the Virtual Machine. This process entails specifying key parameters such as the operating system, disk size, and network configurations. Once the Virtual Machine deployment is initiated, Azure takes care of provisioning the required resources and orchestrating the setup based on the specified parameters. Upon the successful completion of the VM creation, the next step involves establishing a remote desktop connection to the machine. 

![Capture](https://github.com/Gmst004/osticket-prereqs/assets/155221840/34521ccc-f9ae-4d0a-ad6a-d1e4f046f6e5)




<p>


</p>
<p>
 In the picture I've already established a remote desktop connection to the Virtual Machine, the focus has shifted to the configuration of essential features within the Internet Information Services (IIS). IIS plays a crucial role in hosting and serving web applications, and in this instance, I am enabling specific features that are integral to running the osTicket system. 

![Capture JPG1](https://github.com/Gmst004/osticket-prereqs/assets/155221840/bb146266-c1f3-44fa-9efc-852af3964d09)


<p>

</p>
<p>In the context of the image, the current focus is on verifying that the required features have been correctly enabled. To confirm the accuracy of the configurations, I entered the IP address 127.0.0.1, representing the localhost, into the system. This step serves as a validation check to ensure that the enabled features are functioning as intended within the local environment. By accessing the localhost, I can directly examine and validate the operation of the configured features, confirming that they align with the prerequisites for the intended use.

![Capture JPG3](https://github.com/Gmst004/osticket-prereqs/assets/155221840/47e1cd8b-565b-4f45-b530-9520a06cbbbf)


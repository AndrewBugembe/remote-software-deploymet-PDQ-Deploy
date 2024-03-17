<p align="center">
<img src="https://i.imgur.com/XXlcupg.png"/>
</p>

<h1>PDQ Deploy: Remote Software Deployment</h1>
This project demonstrates how to remotely deploy software on a server using PDQ Deploy. PDQ Deploy is a powerful tool for system administrators, allowing them to efficiently manage software installations, patches across multiple servers silently.

## Use Case
- PDQ Deploy allows you to deploy new software to end-user computers. This is especially valuable when working remotely, as it streamlines the installation process.

## Challenges
- **Customization**: Administrators must handle user context installations effectively.
- **Maintenance**: Misconfigured settings may cause deployments to hang.

<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to deploy software remotely using PDQ DEPLOY](https://youtu.be/LGjsXd10vxc)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines: Windows server 2022 and Windows 11 Pro)
- Active Directory Domain Controller
- Remote Desktop
- PDQ Deploy software

<h2>Operating Systems Used </h2>

- Windows 11 pro</b> (21H2)
- Windows server 2022

<h2>Steps</h2>

- Configure Active Directory; create a domain controller and add a user server
- Download and Install PDQ DEPLOY on the domain controller
- Configure PDQ DEPLOY:
  - Check the PDQ Deploy Package Library for a prebuilt package
  - If available, use the prebuilt package for faster deployment
  - Deploy the package to the targeted computers
- Create a custom deployment package:
  - Download required software onto the DC server
  - Check the PDQ Deploy Package Library to select the package and targeted computers, deploy package.


<p>
<img src="https://i.imgur.com/xsfPkqO.png"/>
</p>
<p>
Configure Active Directory; create a domain controller and add a user server.
</p>
<br />

<p>
<img src="https://i.imgur.com/uJXsTqj.png"/>
</p>
<p>
<img src="https://i.imgur.com/yJdWmbW.png"/>
</p>
<p>
<img src="https://i.imgur.com/m68e9Tu.png"/>
</p>
<p>
Download and Install PDQ DEPLOY on the domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/zFJYsQO.png"/>
</p>
<p>
<img src="https://i.imgur.com/2INgZMp.png"/>
</p>
<p>
Post installation configurations 
</p>
<br />

<p>
<img src="https://i.imgur.com/bGAxZtD.png"/>
</p>
<p>
Configure PDQ DEPLOY: Check the PDQ Deploy Package Library for a prebuilt package.
</p>
<br />

<p>
<img src="https://i.imgur.com/1D5w6zm.png"/>
</p>
<p>
Configure PDQ DEPLOY: If available, use the prebuilt package for faster deployment.
</p>
<br />

<p>
<img src="https://i.imgur.com/MJszN2o.png"/>
</p>
<p>
<img src="https://i.imgur.com/7x2jshW.png"/>
</p>
<p>
<img src="https://i.imgur.com/qF7V3Xv.png"/>
</p>
<p>
<img src="https://i.imgur.com/EHf1172.png"/>
</p>
<p>
Configure PDQ DEPLOY: Deploy the package to the targeted computers.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a custom deployment package: Download required software onto the DC server.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a custom deployment package: Check the PDQ Deploy Package Library to select the package and targeted computers, deploy package.
</p>
<br />


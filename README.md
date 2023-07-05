<p align="center">
  <img width="600" height="300" src="https://github.com/mmanzoor825/configure-ad/assets/138532574/f0104599-f417-42c5-a46f-b09e07e0a7f7">
</p>

<h1>Group Policy</h1>
This tutorial outlines using Group Policy withing the AD domain to force a desktop wallpaper for all domain users.<br />

<h2>Environments and Technologies Used</h2>

- Oracle VM VirtualBox

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 Pro</b> 

<h2>Installation Steps</h2>

<p>
  <img width="377" alt="image" src="https://github.com/mmanzoor825/configure-group-policy/assets/138532574/d5f95933-2dbf-491e-aeab-b817fc5e7a53">
>

</p>
<p>
In Server Manager, click Tools > Group Policy Management. On the left pane, drop down to Forest > Domains > click your domain > right click Default Domain Policy and click edit. A new window will be opened that will allow you to edit the current group policy.
</p>
<br />

<p>
<img width="341" alt="image" src="https://github.com/mmanzoor825/configure-group-policy/assets/138532574/c08a66cf-f571-46cd-82e2-c33dd196a820">

</p>
<p>
Click User Configuration > Policies > Administrative Templates > Desktop > Desktop > Desktop Wallpaper. Double click Desktop Wallpaper. Choose enable and type the file path for a image that is shared in the network. Click Apply and OK. Now log into a computer that is a part of the domain. The desktop wallpaper should be set.  </p>
                                                                                                                                                     
</p>
<br />

<br />

<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Creating Azure Virutal Machines</h1>
In this tutorial, we cover the basics of how to create a virtual machine in Azure <br />


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2 Steps</h2>

- Create a resource group
- Create Windows VM
- Create Linux VM
- Use NetworkWatcher to analyze
<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/5oWhPNH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once in your Azure portal, type in "resource groups" in the search bar, or simply click the Resource Groups tab on the home page. 
</p>
<br />

<p>
<img src="https://i.imgur.com/09uBntR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After selecting the resource groups option, you will need to give it a name. For this example, I used RG-LAB_02. Once named, you can select review + create at the bottom of the screen. Congrats! You just created your first resource group in Azure! That was pretty easy.
</p>
<br />

<p>
<img src="https://i.imgur.com/7Jya9TY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it's time to create your first Virtual Machine. Go back to the home page of your Azure portal. Type in virtual machines in the search bar or click the virtual machines tab. First, you're going to choose to store this VM in the resource group we just created. Then we need to give our virtual machine a name. To keep things as simple as possible, we will name this VM1. After we name the VM, we will choose the Windows 10 option. When choosing the size, you want it to be able to handle all of the work you're going to be doing in the Virtual Machine, so select 16gb option. Lastly, you're going to need to create a username and password in order to get into the VM using the RDP protocol. Everything else can be left untouched, so you can go ahead and hit review + create!
</p>
<br />

<p>
<img src="https://i.imgur.com/lYHuQHS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you're seeing this screen, congrats! you're first virtual machine is being deployed! While your first virtual machine we can proceed to the next step, which is creating our second virtual machine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bTvettt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you have created your first virtual machine, the second one will be a piece of cake. You're going to follow the same steps as the previous one. Except this time, you're going to name it VM2, and change the operating system to Ubuntu. And instead of using an SSH pubic key, you can choose the password option. To make things easy use the same username and password as you did for the first virtual machine. Once everything looks good you can hit review + create! 
</p>
<br />

<p>
<img src="https://i.imgur.com/uKevTHe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you have finished creating your second virtual machine, you can go into your resource group called RG-LAB-02, and it should look a little something like this. Here you can see everything that was created in order to deploy both virtual machines. For example, the hard drive disk, the virtual NIC, firewall, and network id.
</p>
<br />

<p>
<img src="https://i.imgur.com/gXUouIU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once both of your virtual machines finish deploying. Type in network watcher in the search bar. Then, on the left side click the topology tab. This tab will give you a visual on what you just made. Now that you have a visual it will make it easier to understand the next project. In the next project we will be communicating between both of our virtual machines! 
</p>
<br />

<p align="center">
<img src="https://k21academy.com/wp-content/uploads/2020/10/Diagram-02-1024x531.png"/>
</p>

<h1>Azure Crash Course</h1>
This tutorial outlines the implementation of on-premises storage accounts and containers within Azure.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Resource groups
- Storage accounts
- Containers
- Notepad

<h2>Operating Systems Used </h2>

Windows 10, additionally, any modern operating system capable of accessing the azure portal. 

<h2>High-Level Deployment and Configuration Steps</h2>

- Go to the azure portal and create a resource group.
- Create a storage account in that resource group.
- Create a container within the storage unit.
- Create a text file on your desktop and upload it into the storage account.
- Edit the file in the storage account and then download it to note the difference.

<h2>Video Demonstration</h2>

- ### [YouTube: Crash Course video demonstration](https://www.youtube.com/watch?v=nbSmK-oA1bQ)

<h2>Deployment and Configuration Steps</h2>

Using a valid email address and credit card create a free azure subscription, you wont get charged on that card and you will get a 200$ free credit to use within azure for a full month. After your account is created you will get access to the Azure portal. 

The portal has the same function that the user interface has to operating systems, It provides a user-friendly way to access and interact with Azure's features and functionality, eliminating the need for coding or the use of highly complex actions to achieve your goals within the Azure environment.

<p align="center">
<img src="https://i.imgur.com/Ka9bdEp.png" height="80%" width="80%" alt="img"/>
</p>

This is the Azure portal. To proceed with this lab, we will click on "Resource groups" to create a new one. You can also use the search bar at the top to navigate to the same location.

<p align="center">
<img src="https://i.imgur.com/DewkbRn.png" height="80%" width="80%" alt="img"/>
</p>

Resource groups serve as logical containers that Azure uses to manage resources within a project. Although they have more complexity, let's keep it simple for now. In the resource groups tab, click on "create," fill out the requested information, then click on "review and create," and finally, click "create" again.

After the deployment is completed, return to the Azure portal, and now let's create the storage account. Azure will prompt us to provide additional information to create this resource. Two important things to note here are:

1. Ensure that you place your storage unit in the same resource group that we just created. It should be available to choose from the options in the subscription > Resource group tab.
2. Keep in mind that storage account names need to be unique. So, don't worry if you initially enter a common name and it doesn't allow you to create the resource. Simply try typing a unique and complex name for it, and it should work.

<p align="center">
<img src="https://i.imgur.com/PePGwK5.png" height="80%" width="80%" alt="img"/>
</p>

Once you've finished filling out the information, click on "Review and create," and then click "Create" again. After the deployment process, your storage account should be ready to use.

What are storage accounts? Think of them as if they were hard drives, but in Azure, a closer comparison would be to other virtual storage solutions like Google Drive or Dropbox. Essentially, it's an online storage service for your digital data.

Continuing with the lab, let's access our newly created storage account. You can do this by clicking on the "Storage accounts" icon in the Azure portal and selecting the one we just created. Within our storage account, you'll find a menu of configuration options on the left. In the "Data storage" section, click on "Containers," and then select "+Container" at the top left of the webpage.

<p align="center">
<img src="https://i.imgur.com/DxM0BwK.png" height="80%" width="80%" alt="img"/>
</p>

Think of containers as similar to folders on your hard drive. They provide a way to store and organize your information in a structured manner within your Azure storage account.

<p align="center">
<img src="https://i.imgur.com/sf1fJgA.png" height="80%" width="80%" alt="img"/>
</p>

Now that we've created our container, let's switch to our desktop and create a text file. Inside the file, write a few words and save it. Afterward, return to our container in the Azure portal. Click on the "Upload" button to upload the text file we just created. Then, click on the three dots at the end of that file's line and select "View/Edit."

<p align="center">
<img src="https://i.imgur.com/1DYX3c1.png" height="80%" width="80%" alt="img"/>
</p>

Edit the file again, add a couple of words, and save the changes. Afterward, download the file to your local computer.

To conclude this lab, open the file on your computer and observe that the changes made in Azure are reflected in the file.

<p align="center">
<img src="https://i.imgur.com/0mzHjLJ.png" height="80%" width="80%" alt="img"/>
</p>

If everything has gone smoothly, the crash course is now complete. To finalize it and ensure you won't incur any additional charges, return to the resource group and proceed to delete it. This will clean up the resources used during the lab.

<p align="center">

</p>

<h1>Setting up Resource Groups and Storage Accounts</h1>
In this tutorial, I will Show you how to properly set up Resource Groups and Storage Accounts. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)


<h2>Operating Systems Used </h2>

- Windows 11 (21H2)
- 

<h2>High-Level Steps</h2>

- Step 1
 -Setting up A resource Group
- Step 2
  - Setting up a storage account
- Step 3
 -Setting up Virual Machines 
- Step 4
 -Confirming the virtual machine works properly  

<h2>Actions and Observations</h2>

<p>
<img width="715" height="645" alt="Screenshot 2026-10-19 170212" src="https://github.com/user-attachments/assets/fb6f01f3-bcc8-460c-8a4c-4e9e6f2a230b" />

</p>
<p>
To start you must first locate the resource groups tab it looks like a square between two brackets. When on the Resource groups screen you must go to create resource groups and this should bring you to a screen where you must fill out the name of the group and what type of region the groups is based in, this will be important later on when trying to make other things within the Resource group. Depending on how your account is set up is how the resource group will be paid for, Azure is a subscription based system that you can pay as you go or pay monthly, for this we had a free subscription so we used that. In a normal case we would use pay as you go or whichever your company that you work for prefers. With Pay as you go you only pay for the amount of time the resource group is actively using the server, so when done using a group make sure its deactivated so you are not charged.
</p>
<br />

<p>
<img width="1000" height="654" alt="Screenshot 2026-10-19 174441" src="https://github.com/user-attachments/assets/150b1c72-2ab7-495a-8fb4-7b7cb85fa7c0" />

</p>
<p>
Once created you should see a screen that looks like this showing your created resource group
</p>
<br />

<p>
<img width="816" height="854" alt="Screenshot 2026-10-19 171620" src="https://github.com/user-attachments/assets/57180e11-38c4-4cb7-88fe-cc28497a00c0" />

</p>
<p>
Next is setting up a storage account, this is done by finding the storage account tab in the home screen of azure, once you click create storage account it should bring you to this screen, make sure that you find the resource group that you created before and select the form of subscription that you would prefer and fill out everything else as default.
</p>
<br />

<p>
<img width="1020" height="755" alt="Screenshot 2026-10-19 174319" src="https://github.com/user-attachments/assets/806a9eb6-97b1-4b9d-bf3f-18c6e09e5dda" />

</p>
<p>
 When Done correctly your storage account should show up here ready to be used, just remember that as long as the storage group is active it gets charged so make sure to disable the account when you are done using it so it doesn't charge you.
</p>

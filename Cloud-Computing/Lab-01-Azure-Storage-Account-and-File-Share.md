# Lab 01 – Create an Azure Storage Account and File Share

## Objective

Practice creating and configuring an Azure Storage Account and creating an Azure File Share using the Microsoft Azure portal.

## Skills Practiced

* Microsoft Azure portal navigation
* Cloud storage configuration
* Azure Storage Accounts
* Resource group management
* Storage redundancy configuration
* Azure File Shares
* Cloud file storage
* Resource deployment

## Environment
* Microsoft Azure portal
* Azure Storage Account
* Azure File Share
* **Subscription:** CorpNet Production
* **Resource Group:** CorpNetCloud
* **Region:** West US 2

## Scenario

In this lab, I created an Azure Storage Account and configured cloud-based file storage for the CorpNet environment. I configured the storage account with geo-redundant storage and created a file share within the new storage account.

## Tasks Performed

### 1. Created a Storage Account

* Opened the Microsoft Azure portal.
* Navigated to **Storage accounts** under Azure Services.
* Selected **+ Create**.
* Configured the storage account with the following settings:

  * **Subscription:**
  * **Resource Group:** 
  * **Storage Account Name:** 
  * **Region:** 
  * **Redundancy:** Geo-redundant storage (GRS)
* Selected **Review** to verify the configuration.
* Reviewed the configured options.
* Selected **Create** to deploy the storage account.
* Waited for the deployment to complete.
* Selected **Go to resource** to access the newly created storage account.


### 2. Created an Azure File Share

* Opened the newly created storage account.
* Navigated to **Data Storage** in the left navigation pane.
* Selected **File shares**.
* Selected **+ File share**.
* Verified that the file share was successfully created.
* Confirmed that the file share currently contained no files.

## Best Practices Followed

* Used the correct Azure subscription and resource group.
* Configured the storage account according to the required specifications.
* Selected geo-redundant storage (GRS) to provide data redundancy across geographic regions.
* Verified configuration settings before deploying the storage account.
* Confirmed successful resource deployment.
* Created and verified the Azure File Share within the storage account.

## What I Learned

This lab provided hands-on experience with Microsoft Azure cloud storage services. I learned how to create and configure an Azure Storage Account, select an appropriate region and redundancy option, and create an Azure File Share for cloud-based file storage. I also gained experience navigating the Azure portal and managing cloud storage resources.

## CompTIA A+ Objectives

* **4.1** – Explain basic cloud concepts and client-side virtualization.
* **4.2** – Identify common cloud models and services.
* **4.3** – Explain basic cloud storage concepts and technologies.


## Outcome

* Successfully created the **storageaccount** Azure Storage Account.
* Configured the storage account with **Geo-redundant storage (GRS)**.
* Successfully created the **fileshare** Azure File Share.
* Verified that the new file share was accessible and contained no files.
* Demonstrated hands-on experience configuring cloud storage resources using the Microsoft Azure portal.

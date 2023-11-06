# Windows Features

## Windows at Work

1. **Large scale support :** Thousand of devices
2. **Security concerns : -** Mobile devices with important data and Local file shares
3. **Working on spreadsheet like MS excel**&#x20;
4. **Media support -** Watching a movie&#x20;
5. **Geographical sprawl:** Effecient file transfers in wide area networks (cache data between sites)

## Domain services

1. **Active Directory Domain Services :** Large database of your network
2. **Everything documented in one place** : User accounts , servers , volumes , printers&#x20;
3. **Distributed architecture :** Many servers & Not suitable for home use
4. **Many different uses :** Authentication and Centralized management&#x20;

## Organizing network devices&#x20;

**Windows Workgroups for managing home environment :**

1. Logical groups of network devices&#x20;
2. Each device is a standalone system , everyone is a peer which allows us to connect multiple devices on same network and be able to access resources across multiple systems&#x20;
3. Every machine would have seperate usernames and passwords&#x20;
4. **In large environments we need a way to centeralize all the operations and provide everyone access to resources regardless where they might be , so we will use `Microsoft Active Directory in a windows domain`  this centeralzed database provides users  a single login to access any resources they might need , it is commonly used in business environments , it supports thousands of devices across many networks so its best for large infrastructures .**

## Desktop styles

1. Your computer has many different uses : Those change depending on where you are&#x20;
2. Work : Standard Desktop , common user interface , customization very limited & you can work at any computer .
3. Home - Complete flexibility , change background photos , colors , UI sizing&#x20;

## Availability of RDP

1. **Remote Desktop Protocol :** View and control the desktop of a remote device&#x20;
2. **RDP client :** Connects to a Remote Desktop Service . Clients available for almost any operating systems .
3. **Remote Desktop Service :** Provides access for the RDP client , Available in Windows 10 Pro and Enterprise . Not available in Windows 10 Home .​
4. Windows 10 include remote assistant availability which allows users to temporarilty enable  someone to connect to your local machine&#x20;

## Ram support limitations&#x20;

1 . **Ram support varies between editions**&#x20;

2 **. More advanced editions allow additional RAM**&#x20;

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

## BitLocker and EFS&#x20;

**EFS**&#x20;

1. **Data confidentiality**&#x20;
2. **Encrypt important information**
3. **EFS - Encrypting File System :** Protect indiviudal files and folders and build in to the **NTFS file system**&#x20;

**BitLocker**

1. **Full Disk Encryption (FDE)**
2. **Everything on drive is encrypted**
3. **Even the operating system**

## Group Policy Editor&#x20;

1. Centerally manage users and systems&#x20;
2. Policies can be part of Active Directory or a local system
3. Local Group Policy for local device without using active directory  : Manages the Local Device - **run-** `gpedit.msc`
4. **But in a business or enterprise environment you will use `Group Policy Management Console`  : it is integrated with Active Directory and provides powerful management system**&#x20;
5. **To run Group Policy Management console you would run `gpmc.msc`**

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p><strong>Local group policy editor</strong> </p></figcaption></figure>


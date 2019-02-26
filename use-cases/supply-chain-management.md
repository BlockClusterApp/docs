# Industry Overview

A supply chain of any business involves a vast number of stakeholders. There is an exchange of information between different partners which makes it prone to human errors. Once the asset leaves the manufacturing facility, there is less or no visibility into its whereabouts in the supply chain. The tracking information itself can be tempered with. Moreover, unauthorized access to this information can prove to be dangerous for the integrity and safety of the asset. 

 

# Challenges

The biggest challenge the supply chains are facing today is the data flow. There are many roadblocks in the smooth data flow among the stakeholders such as the absence of ways to track & trace the assets, unavailability of near real-time location of the shipments, lack of interconnecting network, unauthorized data access/changes, etc.

**Lack of means to track & trace the assets**

Since the large organizations have a lot of elements to deal with, it becomes impossible to track the assets as they move between different nodes in a supply chain. It is also difficult to determine and trace the origin of products. 

**Determine the accurate location of the asset**

Another major challenge for a supply chain is near real-time tracking of the asset. Inability to pinpoint the location of the asset makes it difficult to find the loopholes and the real cause behind any hold-ups in the delivery process of the asset.

**Lack of interconnected network**

The data in a supply chain is usually centralized and stored in silos. There is no interconnectivity between the systems of different stakeholders/participants in the supply chain. Another reason for the irregular data flow is the non-matching data formats. Different stakeholders use various formats to store data that might not be supported by the system of other stakeholders.

**Unauthorized Access**

With so many users handling the process, preventing unauthorized accesses is difficult. It is almost impossible for the organizations to pinpoint the fraud in the vast pool of users of the system.

 

# How does Blockchain help?

Blockchain with its features like immutability, transparency, distributed database, and security can solve a lot of issues in the supply chain management. 

**Secure sharing of data between stakeholders**

Since Blockchain is based on distributed ledger technology, each stakeholder has a copy of the database. Any changes made in one copy get distributed to different copies that can only be accessed with the correct credentials.

The origin of any data changes can be traced back. Since all the data is stored in a single Blockchain network, there is a single uniform data format throughout. 

**Real-time tracking of the asset**

As the asset moves between various nodes, the information can be stored in the Blockchain with the time-stamp and lat-long coordinates information. Stakeholders can determine the accurate arrival time of the asset and make preparations in advance to avoid any hold-ups. The transfer of ownership of the assets can also happen on the Blockchain as the physical custody of the asset is transferred. The chain of custody thus formed can also be back-traced to the assets origin including the information about the raw material/parts used in it.

**Prevent unauthorized access**

Any data on the Blockchain network is encrypted, time-stamped, and stored in a distributed database. This reduces the chances of any data breaches. In Blockchain, transactions can be executed only by a user with the right Public and Private keys. Even, the information can be accessed only by the user with the right Private keys.



# How to Track & Trace Assets in Supply Chain using BlockCluster

To explain the process step by step, let us take an example of the supply chain of car manufacturing. 

Here is a list of participants that could be a part of such a supply chain:

*Participant 1* – The supply chain starts from the **Original Equipment Manufacturers (OEMs)** who produce various equipment and parts for the car manufacturer.

*Participant 2* – Parts from different OEMs are assembled at the **manufacturing plant** to build the commercial model of the car.  

*Participant 3* – Through different modes of transport, the car reaches the **custom clearance ports**.

*Participant 4* – After clearing customs, the car is handed over to the **third party logistics provider (3PL)**.

*Participant 5* – The 3PL further contract the delivery of the car to the **trucking company**.

*Participant 6* – The car gets finally delivered to the destination **dealership**.

 

![img](images/supply-chain-management/Participants%20Screen%20Shot%20no.1.png)

 

To build a Blockchain-based solution on BlockCluster to track & trace assets in such a supply chain, the manufacturer (in this case, car manufacturer) would follow below mentioned steps. 

[**Note:** the term ‘user’ and ‘manufacturer’ has been used interchangeably]



**1.**    **The** **manufacturer** **needs to create a  Blockchain network**

![create network](images/supply-chain-management/New%20SS.2.png)

- The manufacturer will first create a BlockCluster account by visiting **app.blockcluster.io**. 

- After successfully logging in to the BlockCluster account for the first time, the first screen that appears is 'Create Your Blockchain Network.'

- The user needs to enter the Blockchain network name in the 'Network Name' box. For example, Car_Demo

- Other values would be pre-selected. However, the user can select 'Node Type.' There are two types of nodes available in the BlockCluster i.e. 'Light Node' and 'Power Node' that offer different no. of CPUs, RAM, and Disk Space. 

- After entering the details, the user will click 'Create.'

- The node will be created and the user will be redirected to the 'control panel' of the Blockchain node.

Note: It will take 40 - 50 seconds for the node to initialize. 



**2.**    **The** **manufacturer** **needs to invite other participants to join the Blockchain network created in step 1.**

Once the network is up and running, the user will be redirected to the BlockCluster Dashboard.

The manufacturer needs to invite other participants of the supply chain with whom transactions need to be done, i.e. issue/exchange assets. The user needs to click invite user icon (second icon) in the top icon bar.

![Invite member](images/supply-chain-management/Invite%20members%20ss%20no.3.png)

On this screen, the user needs to select the second option ‘invite user to network.’

- Enter email id of the participant, select node type as ‘Peer’ and click 'Invite.' The participant would receive an email containing link to join the network. Similarly, the manufacturer needs to invite each participant separately. 

- After clicking the link, the participant would be asked to create a BlockCluster account. 

- If the participants already have an account on BlockCluster, they would receive the invitation in the 'manage invitation' section as shown the figure below.

  ![receive invitation](images/supply-chain-management/Accept%20Invitation%20Screen%20shot%20no.4.png)

- After Clicking on 'accept' button, the participant would be asked to create a node as shown below

  ![accept invite, create node](images/supply-chain-management/New%20no.5.png)

  

**3.**    **Manufacturer** **will create assets on the Blockchain network.**

![Create Asset](images/supply-chain-management/Create%20Asset%20ss%20no.8.png)

Once all the participants have joined the network, the manufacturer will create assets (in this case, cars) on the Blockchain network. The user will click on 'Create Asset Type' from 'Control Panel.'

 User will enter 'Asset Name.' For example, Car_Model. Select ‘Asset Type’ as ‘Solo.’ Keep ‘issuing address’ as ‘Default.’ And will click ‘Create.’



**4.**    **Manufacturer** **will take ownership of the assets by issuing the assets to his account.**

To issue assets:

User will click on the 'Manage Assets' from the 'Assets' section.

![Manage Asset](images/supply-chain-management/Manage%20Asset%20ss%20no.9.png)

In issue ‘Solo Asset’ section, the user will type the asset name, and in the ‘to account’ the default manufacturer account address, and finally click ‘issue asset.’ An identifier can be added to the transaction that can be the registration number of the vehicle. [The address can be copied from the ‘Accounts’ section in the dashboard]

![Issue Asset](images/supply-chain-management/New%20Issue%20asset%20ss%20no.14.png)

**Note:** Different kind of information can be attached to the asset like color, manufacturing year, etc. from the ‘ADD/UPDATE SOLO ASSET INFO’ option available in the ‘Asset management’ section. See the image below.

![Add Asset Info](images/supply-chain-management/Add%20asset%20info%20ss%20no.13.png)

The unique identifier here can be anything, like VIN number of the vehicle. 

After adding all the information, the user can see the information attached with the asset by clicking 'get asset info' option. The user will first select 'asset name' and then type the unique identifier to get the details of the asset. See the below image. 

![Get info](images/supply-chain-management/Get%20Asse%20info%20ss%20no.12.png)

# Process Flow

Once all the steps as mentioned above is successfully executed, the whole supply chain process would get replicated on the BlockCluster’s Blockchain ecosystem.

The manufacturer can see the numbers of nodes connected, in the 'node peers' option available in the control panel. See the image below.

![Peers Connected](images/supply-chain-management/Connected%20Peers%20ss%20no.6.png)

Similarly, the different participants can see from which Blockchain nodes they are connected with via graphical map representation in the 'static peers' option. See the image below.

![Map](images/supply-chain-management/Map%20SS%20no.7.png)

Now whenever an asset will move from one participant to another, two steps are required to be performed:

1. **Transfer of ownership:** This will happen through API call integrated with the apps used by each participant in the supply chain. As soon as they give the custody of asset to other participant, they need to transfer the ownership of asset on BlockCluster too, via the API integrated with the apps. This will be captured with time and geo-location information.

 

2. **Issue receipts:** The participant who has received the custody of the asset (transferee) would issue a receipt to the transferor in the form of a new asset on the Blockchain. The assets info (receipt) would contain important information such as lat-long, status, asset id, etc. (See the figure)

![img](images/supply-chain-management/Final.png) 

 

The receipt would act as a **declaration** by the receiving participant that he has taken the custody of the goods. The lat-long details in the asset info would help in tracking the location of the asset in real-time.

The information on transfer of ownership would be stored in blocks, one after another, forming a chain of custody. Based on both these information, it is easy to trace back the asset to its origin and know the custodian of the asset at a specific time. Only the authorized members can access the information about whereabouts of the assets.  


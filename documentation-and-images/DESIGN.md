# Overview of Technical Architecture

![](XLM-wallet-for-Salesforce-thumbnail.png)

## Core Data Objects

Salesforce Objects are database tables that store data related to your organization.

Each [Salesforce Product](https://www.salesforce.com/products) has its own set of Standard Objects, which are built into that Cloud by default. An Account is a Salesforce Standard Object, which stores information about an organization with which an organization running Salesforce transacts.  This could, for example, be a customer, prospective customer, supplier, empires or contractor.  An Account in XLM Wallet for Salesforce can have an associated wallet from which it can view assets and view or create transactions in XLM. 

Similar to our [Blockchain Payments app](https://appexchange.salesforce.com/appxListingDetail?listingId=ee4c011b-7a5b-4a50-91fb-f28049390858), XLM Wallet for Salesforce will also include custom objects that are specific to sending and receiving payments in XLM. 

The following diagram shows the Core Data Objects in the Salesforce user interface, using the XLM Wallet for Salesforce app. 

![](Core%20Data%20Objects.png)

Alex Hochberger, Founder and CEO of Web3 Enabler, describes some of these features in this [explainer video](https://youtu.be/a-ditM_XxoU).  You can also refer to the following screenshots of some of our other Salesforce wallet projects to get a better sense of what these Objects look like and what they do.


##  Library Architecture

The following diagram shows how the Stellar-SDK and Salesforce Apex and Lightweight Web Components will be used in XLM Wallet for Salesforce. 

![](Library%20Architecture.png)


## Performance Considerations

The following diagram outlines how we plan to optimize the way we integrate Stellar network data into Salesforce to ensure speed and availability for users. 

![](Performance%20Considerations.png)

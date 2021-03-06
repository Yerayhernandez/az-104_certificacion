
# Azure Storage Accounts
- An *Azure Storage account* can be used to store data objects such as blobs, files, queues, tables and disks.
- The data in an *Azure storage account* is durable, highly available, secure and scalable.
- There are different types of *storage accounts*:
    - ***General-purpose v2 accounts***: This is the most recommended storage option. These types of accounts provide services for blobs, files, queues and tables.
    - ***General-purpose v1 accounts***: This is a legacy account type. This account type also provides services for blobs, files, queues and tables, but Microsoft recommends that instead of using **general-purpose v1**, use **general-purpose v2** because new features when they're made available for storage accounts, they are made available in **general-prupose v2** storage accounts.
    - ***BlockBlobStorage accounts***: These are storage accounts that provide premium performance when it comes to storing block and append blobs.
    - ***File Storage accounts***: These are storage accounts that provide premium performance when it comes to storing files.
    - ***BlobStorage accounts***: This is a legacy Blob-only storage account.
    Now, let's have a quick understanding of the different services that we have in **storage accounts**. 
    
    As part of the exam, we have to focus on only the blob and the file service. But let's just have a quick understanding on all the services which are available in **storage accounts**:
    - ***General Purpose v2 account - Blob service***
        - This is used for storing objects on the cloud, so that means you could go ahead and store objects on the internet via the Azure platform
        - This is used for storing large amounts of unstructure data.
        If your application has a need to store datasuch as images, video or audio files, log files, then consider using the Blob service.
    - ***General Purpose v2 account - File service***
        - This service can be used for creating files shares on the cloud.
        - Here the files shares can be accessed via the SMB protocol (Server Messag Block)
        - You can mount these files shares from *cloud-based* or *on-premise machines*
        - The machines could be runing on a variety of platforms (Windows, Linux, macOS).
    - ***General Purpose v2 account - Table service***
        - This is a service that can be used to store structured NoSQL data in the cloud.
        - It's ideal for storage accessed by web applications.
        - It's ideal for datasets that don't required complex joins, foreign keys or store procedures.
        - Here you just get fast access to your table data.
    - ***General Purpose v2 - Queue service***
        - This a service that can be used for storing large number of messages.
        - This is an ideal store for exchange of message between comopnents of an application.
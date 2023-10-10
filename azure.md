
#### Q86. You use Azure Table storage to store customer information for an application. The data contains customer details and is partitioned by last name. You need to
create a query that returns all customers with the last name Smith. Which code segment should you use?

- [ ] TableQuery.GenerateFilterCondition("PartitionKey", Equals, "Smith")
- [ ] TableQuery.GenerateFilterCondition("LastName", Equals, "Smith")
- [X] TableQuery.GenerateFilterCondition("PartitionKey", QueryComparisons.Equal, "Smith")
- [ ] TableQuery.GenerateFilterCondition("LastName", QueryComparisons.Equal, "Smith")

Explanation:
Retrieve all entities in a partition. The following code example specifies a filter for entities where 'Smith' is the partition key. This example prints the fields of each
entity in the query results to the console.
Construct the query operation for all customer entities where PartitionKey="Smith". TableQuery<CustomerEntity> query = new
TableQuery<CustomerEntity>().Where(TableQuery.GenerateFilterCondition("PartitionKey",
QueryComparisons.Equal, "Smith"));

[Ref](https://docs.microsoft.com/en-us/azure/cosmos-db/table-storage-how-to-use-dotnet)




#### Q87.You develop an app that allows users to upload photos and videos to Azure storage. The app uses a storage REST API call to upload the media to a blob storage
account named Account1. You have blob storage containers named Container1 and Container2. Uploading of videos occurs on an irregular basis.
You need to copy specific blobs from Container1 to Container2 in real time when specific requirements are met, excluding backup blob copies.
What should you do?



- [ ] Download the blob to a virtual machine and then upload the blob to Container2.
- [X] Run the Azure PowerShell command Start-AzureStorageBlobCopy
- [ ]  Copy blobs to Container2 by using the Put Blob operation of the Blob Service REST API.
- [ ]  Use AzCopy with the Snapshot switch blobs to Container2.

Explanation:
The Start-AzureStorageBlobCopy cmdlet starts to copy a blob. Example 1: Copy a named blob
C:\PS>Start-AzureStorageBlobCopy -SrcBlob "ContosoPlanning2015" -DestContainer "ContosoArchives"
-SrcContainer "ContosoUploads"
This command starts the copy operation of the blob named ContosoPlanning2015 from the container named ContosoUploads to the container named
ContosoArchives.



[Ref](https://docs.microsoft.com/en-us/powershell/module/azure.storage/start-azurestorageblobcopy?view=azurermps)


#### Q88. (Exam Topic 3)
You are a developer for a SaaS company that offers many web services. All web services for the company must meet the following requirements:
Use API Management to access the services Use OpenID Connect for authentication Prevent anonymous usage A recent security audit found that several web services can be called without any authentication.
Which API Management policy should you implement?



- [ ] jsonp
- [ ] authentication-certificate
- [ ] check-header
- [X] validate-jwt

[Ref](https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-protect-backend-with-aad)


#### Q89.You are developing an Azure Cosmos DB solution by using the Azure Cosmos DB SQL API. The data includes millions of documents. Each document may
contain hundreds of properties.
The properties of the documents do not contain distinct values for partitioning. Azure Cosmos DB must scale individual containers in the database to meet the
performance needs of the application by spreading the workload evenly across all partitions over time.
You need to select a partition key.
Which two partition keys can you use? Each correct answer presents a complete solution. NOTE: Each correct selection is worth one point



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()


#### Q90.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()


#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()

#### Q91.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q92.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q93.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q94.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q95.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()
#### Q86.



- [ ] 
- [ ] 
- [ ] 
- [ ] 

[Ref]()



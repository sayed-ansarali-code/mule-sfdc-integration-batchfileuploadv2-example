# mule-sfdc-integration-batchfileuploadv2-example

1. Import the project in Anypoint Studio
2. Update /src/recources/global-properties.yaml with your Salesforce Basic Auth credentials.
3. Start the Mule App
4. Create folder D:\temp\src
5. Create Folder D:\temp\dest
6. Create a few files under 'D:\temp\src' folder with file name matching pattern like this 'One-1111.txt''
7. Start the batch job by issuing HTTP GET request to http://localhost:8081/start
8. Observe that the files are moved from src folder to dest folder.
9. Observe that the numerical portion of the filename is printed in the logs.
10. Observe that the files are uploaded to your Salesforce.com account in batches of 211. 

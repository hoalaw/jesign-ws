## The services provide the following functionality:
- Document mail merge and converting a .DOCX template with merged data, into a .PDF
- Signature autolocation which parses the .PDF document to find signing locations for signers by name and by token
- Signature stamping to place .PNG signature images into the locations provided by signature autolocation function
- Certification which attaches a signing certificate to the document

The project files are for Intelli-J and will create both .JAR and .WAR artifacts. The JARs can be used to run as stand-alone web servers.

## Future plans:

[ ] Implement Grizzly  
[ ] Implement CLI mode for AWS Lambda  
[ ] Drop .WAR file build  
[ ] Switch from SOAP to REST  
[ ] Switch to maven project (use pom.xml)  
[ ] Add tests  
[ ] Add Dockerfile  
[ ] Deploy to Docker Hub  

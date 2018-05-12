
# Web-Service Assertions with SoapUI - Open Source Platform!
Now we are in world of micro-services where everything is gets connected with different APIs which will make easy to do communications between systems and because of they are loosely coupled, they are also easy to maintain in future. Micro-services architecture is becoming very popular and preferred way among architects and developers to creating enterprise applications. Because of it is scalable, this is ideal candidate when there is need to enable support for a number of platforms and devices - Ranging from web, mobile, Internet of Things(IoT), and wearable. There are difference between SOA and Micro-services architectures, this article not intended to provide benefits of one over another. This article is more focus on how we can validate and automate APIs and web services with help of SoapUI open source version, and utilize the assertions more effectively.
## Let&#39;s start with What is Web Service or API?
As per below diagram, Web services are loosely-coupled containers of application functionality. Web Services allow applications to communicate directly with each other. As per below diagram you can see that there is SERVICE REQUESTOR who sends the request and there is SERVICE PROVIDER who accepts the request, process it as per defined rules and provide back processed response toSERVICE REQUESTOR.Web services allow applications to exchange data, and it communicates primarily XML based markup language.
![alt text](screenshots/1.png "Web-Services Architecture")

## Tools used:
## SoapUI - Open source 
SoapUI is most common and popular web service tool in the industry, it provides GUI to test functionalities that does not have GUI interface. Open Source version is good for automation validation but need Pro version to get more versatility and simplicity to get automation faster. it can be downloaded from below URL.
https://www.soapui.org/downloads/soapui.html
once it is downloaded then install it with default settings.
## Create project in SoapUI:
Open SoapUI and and go to File > New SOAP Project and enter below wsdl url in "initial WSDL:" field, it will automatically fill "Project Name"
http://ws.cdyne.com/phoneverify/phoneverify.asmx

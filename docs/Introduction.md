# Introduction

![](../assets/images/rsz_iris_api.png)

**Integrate with GEODIS using the IRIS API integration platform**. The IRIS API is intended only for clients of GEODIS and access to the services offered through the API need to be approved and activated by GEODIS before they can be utilized.

The use of the IRIS API is not intended to drive data provisioning to other applications, reporting and/or BI purposes. GEODIS will not allow large bulk data extraction in a batched fashion and that type of use of the web service will be enforced by capping of the number of requests done per account or in severe cases by discontinuation of the user accounts involved in such usage patterns. 

<!-- theme: warning -->
> GEODIS reserves the right to enforce abuse and user of the web service that may be affecting performance of IRIS or surrounding sub systems.

For the full IRIS application, please access it via [IRIS Web Application](https://iris-demo.geodis.com/).

Available API operations:

- **TRACKING - List and get shipment details:** This request should be used to get a complete list of shipments for the defined period looking at the selected date type in the request.
- **BOOKINGS - Create and update bookings:** All booking functions.
- **MILESTONES - Add milestones and events:** The main purpose for this script is for GEODIS agents to update milestones on shipments via the IRIS API instead of doing this manually via Milestone Entry in IRIS.

#### Note about IRIS API version 1.0

<!-- theme: info -->
> The IRIS API version 1.0 is a web service.

Web services use SOAP over HTTP protocol. The IRIS API is following the standard W3C Web Services
Architecture with the interface described in the machine-processable format WSDL. Other systems
interact with the Web service in a manner prescribed by its description using SOAP (Simple Object
Access Protocol) messages, conveyed using HTTPS with an XML serialization in conjunction with other
Web-related standards.

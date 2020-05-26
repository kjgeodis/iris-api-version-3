# Security & Authorization

The use of the IRIS API is not intended to drive data provisioning to other applications, reporting and/or BI
purposes. GEODIS will not allow large bulk data extraction in a batched fashion and that type of use of the
web service will be enforced by capping of the number of requests done per account or in severe cases by
discontinuation of the user accounts involved in such usage patterns.

GEODIS reserves the right to enforce abuse and user of the web service that may be affecting performance
of IRIS or surrounding sub systems. GEODIS hereby reserves the right to add functionality for
capping/limiting the allowed number web service calls per user account.
The IRIS API is using encrypted communication point to point (HTTPS and User Authentication).

<!-- theme: success -->
> ### Authentication
>
> For all web service requests authentication of the user credentials are required. The
username and password will be provided by GEODIS. Please be aware that the username and password
required for the IRIS API is not the same as an IRIS user account. Likewise, the username and password
for the IRIS API cannot be used to login to web interface of the IRIS eSolution platform.

<!-- theme: danger -->
> ### Blacklisting of IP addresses
>
> Please be aware that the IRIS API system will automatically block access
from any IP address using the services and where usage is considered as misuse. IP addresses will also
automatically be blocked for a period of time if incorrect username and/or password is being used
multiply times.

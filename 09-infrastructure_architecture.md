While most of the documentation is focused on the software itself, we do also need to consider the infrastructure because software architecture is about software and infrastructure.

# Intent
This section is used to describe the physical/virtual hardware and networks on which the software will be deployed. Although, as a software architect, you may not be involved in designing the infrastructure, you do need to understand that it's sufficient to enable you to satisfy your goals. The purpose of this section is to answer the following types of questions:

Is there a clear physical architecture?<br>
What hardware (virtual or physical) does this include across all tiers?<br>
Does it cater for redundancy, failover and disaster recovery if applicable?<br>
Is it clear how the chosen hardware components have been sized and selected?<br>
If multiple servers and sites are used, what are the network links between them?<br>
Who is responsible for support and maintenance of the infrastructure?<br>
Are there central teams to look after common infrastructure (e.g. databases, message buses, application servers, networks, routers, switches, load balancers, reverse proxies, internet connections, etc)?<br>
Who owns the resources?<br>
Are there sufficient environments for development, testing, acceptance, pre-production, production, etc?<br>
# Structure
The main focus for this section is usually an infrastructure/network diagram showing the various hardware/network components (servers, routers, firewalls, load balancers, etc) and how they fit together, with a short narrative to accompany the diagram.

# Motivation
The motivation for writing this section is to document the infrastructure and confirm that it supports the software architecture.

# Audience
The audience for this section is predominantly the technical people in the software development team along with others that may help deploy, support and operate the software system.

# Required
Yes, an infrastructure architecture section should be included in technical software documentation because it illustrates that the infrastructure is understood and has been considered.
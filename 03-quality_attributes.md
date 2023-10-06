With the functional overview section summarising the functionality, it's also worth including a separate section to summarise the quality attributes (also referred to as "non-functional requirements").

# Intent
This section is about summarising the key quality attributes and should answer the following types of questions:

Is there a clear understanding of the quality attributes that the architecture must satisfy?<br>
Are the quality attributes SMART (specific, measurable, achievable, relevant and timely)?<br>
Have quality attributes that are usually taken for granted been explicitly marked as out of scope if they are not needed? (e.g. "user interface elements will only be presented in English" to indicate that multi-language support is not explicitly catered for)<br>
Are any of the quality attributes unrealistic? (e.g. true 24x7 availability is typically very costly to implement inside many organisations)<br>
In addition, if any of the quality attributes are deemed as "architecturally significant" and therefore influence the architecture, why not make a note of them so that you can refer back to them later in the documentation.

# Structure
Simply listing out each of the quality attributes is a good starting point. Examples include:

Performance (e.g. latency and throughput)<br>
Scalability (e.g. data and traffic volumes)<br>
Availability (e.g. uptime, downtime, scheduled maintenance, 24x7, 99.9%, etc)<br>
Security (e.g. authentication, authorisation, data confidentiality, etc)<br>
Extensibility<br>
Flexibility<br>
Auditing<br>
Monitoring and management<br>
Reliability<br>
Failover/disaster recovery targets (e.g. manual vs automatic, how long will this take?<br>)
Business continuity<br>
Interoperability<br>
Legal, compliance and regulatory requirements (e.g. data protection act)<br>
Internationalisation (i18n) and localisation (L10n)<br>
Accessibility<br>
Usability<br>
...<br>
Each quality attribute should be precise, leaving no interpretation to the reader. Examples where this isn't the case include:

"the request must be serviced quickly"<br>
"there should be no overhead"<br>
"as fast as possible"<br>
"as small as possible"<br>
"as many customers as possible"<br>
...
# Motivation
If you've proactively considered the quality attributes and let them influence the software architecture, why not write them down too? Typically, quality attributes are not given to you on a plate and an amount of exploration and refinement is usually needed to come up with a list of them. Put simply, writing down the quality attributes removes any ambiguity both now and during maintenance/enhancement work in the future.

# Audience
Since quality attributes are mostly technical in nature, this section is really targeted at technical people in the software development team.

# Required
Yes, all technical software documentation should include a summary of the quality attributes/non-functional requirements as they usually shape the resulting software architecture in some way.
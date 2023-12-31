The data associated with a software system is usually not the primary point of focus yet it's arguably more important than the software itself, so often it's useful to document something about it.

# Intent
The purpose of the data section is to record anything that is important from a data perspective, answering the following types of questions:

What does the data model look like?<br>
Where is data stored?<br>
Who owns the data?<br>
How much storage space is needed for the data? (e.g. especially if you're dealing with "big data")<br>
What are the archiving and back-up strategies?<br>
Are there any regulatory requirements for the long term archival of business data?<br>
Likewise for log files and audit trails?<br>
Are flat files being used for storage? If so, what format is being used?
# Structure
Keep it simple, with a short section for each element that you want to describe and include domain models or entity relationship diagrams if they help the reader. As with the advice for including class diagrams in the code section, keep any diagrams at a high level of abstraction rather than including every field and property. If people need this type of information, they can find it in the code or database (for example).

# Motivation
The motivation for writing this section is that the data in most software systems tends to outlive the software. This section can help anybody that needs to maintain and support the data on an ongoing basis, plus anybody that needs to extract reports or undertake business intelligence activities on the data. This section can also serve as a starting point for when the software system is inevitably rewritten in the future.

# Audience
The audience for this section is predominantly the technical people in the software development team along with others that may help deploy, support and operate the software system.

# Required
No, but most software systems are not small or trivial, and the data will likely outlive the code that created it.
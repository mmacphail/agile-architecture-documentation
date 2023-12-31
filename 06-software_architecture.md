The software architecture section is your "big picture" view and allows you to present the structure of the software. Traditional software architecture documents typically refer to this as a "conceptual view" or "logical view", and there is often confusion about whether such views should refer to implementation details such as technology choices.

# Intent
The purpose of this section is to summarise the software architecture of your software system so that the following questions can be answered:

What does the "big picture" look like?<br>
Is there are clear structure?<br>
Is it clear how the system works from the "30,000 foot view"?<br>
Does it show the major containers and technology choices?<br>
Does it show the major components and their interactions?<br>
What are the key internal interfaces? (e.g. a web service between your web and business tiers)
# Structure
The container diagram(s) and component diagrams are the main focus for this section, accompanied by a short narrative explaining what the diagram is showing plus a summary of each container/component.

Sometimes UML sequence or collaboration diagrams showing component interactions can be a useful way to illustrate how the software satisfies the major use cases/user stories/etc. Only do this if it adds value though and resist the temptation to describe how every use case/user story works.

# Motivation
The motivation for writing this section is that it provides the "maps" that people can use to get an overview of the software and help developers navigate the codebase.

# Audience
The audience for this section is predominantly the technical people in the software development team.

# Required
Yes, all technical software documentation should include a software architecture section because it's essential that the overall software structure is well understood by everybody on the development team.
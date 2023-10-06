Software lives within the context of the real-world, and the real-world has constraints. This section allows you to state these constraints so it's clear that you are working within them and obvious how they affect your architecture decisions.

# Intent
Constraints are typically imposed upon you but they aren't necessarily "bad", as reducing the number of available options often makes your job designing software easier. This section allows you to explicitly summarise the constraints that you're working within and the decisions that have already been made for you.

# Structure
As with the quality attributes section, simply listing the known constraints and briefly summarising them will work. Example constraints include:

Time, budget and resources.<br>
Approved technology lists and technology constraints.<br>
Target deployment platform.<br>
Existing systems and integration standards.<br>
Local standards (e.g. development, coding, etc).<br>
Public standards (e.g. HTTP, SOAP, XML, XML Schema, WSDL, etc).<br>
Standard protocols.<br>
Standard message formats.<br>
Size of the software development team.<br>
Skill profile of the software development team.<br>
Nature of the software being built (e.g. tactical or strategic).<br>
Political constraints.<br>
Use of internal intellectual property.<br>
...<br>
If constraints do have an impact, it's worth summarising them (e.g. what they are, why they are being imposed and who is imposing them) and stating how they are significant to your architecture.

# Motivation
Constraints have the power to massively influence the architecture, particularly if they limit the technology that can be used to build the solution. Documenting them prevents you having to answer questions in the future about why you've seemingly made some odd decisions.

# Audience
The audience for this section includes everybody involved with the software development process, since some constraints are technical and some aren't.

# Required
Yes, all technical software documentation should include a summary of the constraints as they usually shape the resulting software architecture in some way. It's worth making these constraints explicit at all times, even in environments that have a very well known set of constraints (e.g. "all of our software is ASP.NET against a SQL Server database") because constraints have a habit of changing over time.
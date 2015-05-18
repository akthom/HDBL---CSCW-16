# OUTLINE

## Intro:

*	Describe the pervasivenesss & many roles of relational databases – and briefly note that they have been understudied from a CSCW perspective 
    *	In a world…. Where we can’t stop talking about big data…
*	Databases are inherently a CSCW concern: consider the Relations and relationships quote from Codd 
    *	Mind the Ackerman Sociotechnical gap: the gap btwn what we know we can support technical and what we can support practically
    *	So there’s a big gap still, in Codd’s vision, that hasn’t been closed despite 40 years of innovation
    *	Additionally, just as the divide btwn users and designers of software has broken down, so is the divide between database users and administrators
*	Set up the conceptual/logical framework – and talk about how we’re going to make a connection between what have been 2 domains of concern. 
    *	Domain 1: Logical modeling
        *	This is just as important as conceptual modeling (e.g. systems analysis, requirements gathering) to studies of work
        *	The importance of data independence extends beyond just the physical/logical split – needs to be considered in the logical/conceptual split as well
    *	Domain 2: Studies of work rhythms/work over time –
        *	 Looking at how structures influence work (and vice versa) is something that has to be done over time; the changes accrete slowly, and over the long term, are often (we posit) punctuated by migration to new copmuters/systems
        *	database migration is a largely un-studied thing for data curation and CSCW alike
        *	Preview Brand framework here – his idea of shearing lets us look at this co-structuration in a more methodical way
    *	We contribute to recent work looking at rhythms at work (Steinhardt, Jackson), but by taking a more object-centered perspective.
*	Why we’re looking at NHMs
    *	Difference btwn users and admins is negligible
    *	Databases hold many roles: research tool, digital preservation, transaction processing and tracking
    *	Vested interested in preserving and migrating databases over time
    *	Andrea has 10 years of experience in the field
*	Contributions of this work
    *	Identify issues with logical modeling that are of concern for CSCW
    *	Contribute to studies of rhythms of work, but from a perspective focused on infrastructure (databases)
    *	Show that CSCW can inform data curation
    *	Begin identifying gaps between user needs of relational databases and the technical capabilities of current systems (cite Ackerman?)

## Background theoretical foundations:

*	Codd:
    *	Tripartite model (ANSI)
    *	Logical modeling as a CSCW issue
    *	Relational model as designed for distinct user/administrator roles
    *	Lots of discussion of need for data independence between physical/logical levels – what about logical/conceptual? How do those interact?
	    *	And what about logical structure and day-to-day work practices? How do those interact?
    	*	Note related work in HCI/CSCW - Batra 1993; Topi & Ramish 2003; more
*	Brand: 
    *	Brand gives us a framework to start answering those questions
    *	it's unintuitive that a building learns from its inhabitants and vice versa’ Equally unintuitive is that conceptual and logical levels learn form one another (e.g. that databases and people learn from each other)
    *	Brand’s 6 S’s as they translate to databases
		*	Include figure showing table growth over time
*	Other related work in CSCW 
	*	Work rhythms
	*	Other databases studies
	*	Data curation?
* Background on NHMs and natural history information work
    * Include background on Specify and Arctos and the growing move toward these systems
*	We seek to contribute to this work by bridging these existing studies of infrastructure and work with databases with analysis of how database structures affect work over time – and what steps users take to maintain and curate data structures over time.  In short, we will show the mutual constitution of data models and work practices.

## Method (4 paragraphs)

**Case study design**

* Multiple cases, but a holistic (single unit of analysis)
* Context: Natural History Museums
* Cases: Departments within Natural History Museums 
    * Unit of analysis: A Database
    * Units of observation: Instance of database at a particular point in time. 
* Study Questions: 

    1. In NHMs, how do collections managers manage, curate and migrate their databases over time?
    1. In NHM databases, how do logical schemas change over time?
    1. In NHM databases, how do logical schemas impact work, and vice versa?
    1. In NHMs, how do changes in databases impact collaboration? 

* Propositions: 
    * Like buildings, databases learn -- that is, their structure changes in response to their users, their data and the software used to house the database
    * NHM CMs may not have a large amount of formal training in database design or management, but they do consider database management and maintenance an important part of curatorial work (\cite{Marty_2005}; \cite{Marty_2006})
    * Databases will tend to become denormalized over time, and ad hoc work arounds may be used to make them work.
    * This denormalization can have a long term detrimental effect on data quality, but may ease collaboration, at least in the short term
    * Denormalization over time is ironically at least partially a side effect of the relational model, which aims to focus users on relationships rather than relations (in mathematical sense). In practice, the separation between relations and relationships is predicated on an administrator vs. user role distinction. However, in many places of cooperative work, those roles are blurred 
    * So, to summarize, this research will help us begin to understand how relational databases learn in a context of use in which there is no clear cut distinction between administrators and users? That is, what work needs to be done to make these designs "work"?

## Cases
* 1-2 paragraph demographic summary describing cases; may be edited into Methods later
* Themes:
    * Laying foundations: origins of databases
    * up to code: normalization and denormaliztion
    * migration as retrofitting: the emergence of specify and arctos
    * integration/convergence/additions/add-ons/ingest - additions & guest houses

## Discussion

*	So what does this tell us about how we study these things? And conceptual / logical levels in datbases in general? Where should we study this again? Does conceptual and logical have differentiation in other platforms (e.g. social media platforms, hypertext)
*	Curation as a concern for CSCW and vice versa
*	Kinds growth & kinds of collaboration w/databases: Synchronic and Diachronic


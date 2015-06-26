---
title: SESYNC profile
layout: default
---

# SESYNC profile

## IT/Mission
Please provide an overview of the scope of support, and to whom you provide it.

**Who do you serve?**

* We primarily serve the environmental and social science research communities. Our research is organized around a set of working groups (roughly 50 simultaneous) and in-house postdocs (6 current, 10 in the fall). While working groups are comprised primarily of academics, a non-trivial portion also originate from the non-profit and government sectors. 

**What services do you provide?**
* We support a variety of working groups by providing programming, collaboration services, and access to storage and software resources hosted at SESYNC and UMIACS. 
* In house postdocs have access to high end computing resources hosted on site adn at UMIACS.
* On site services for working groups include fully equipped conference rooms, high end workstations, wifi and teleconference facilities.

## Center Overview

Please provide a high level overview of the services your center provides, who you serve, and the overall environment in which your center operates. Please consider the following items

**Please give a brief overview of your center’s CI offerings, both hardware, software, programming and consultative services**

* SESYNC provides primarily virtualized machine, file storage, and data base access/support to our groups and postdocs. 
* Our standard group offering currently consists of:
  * A drupal commons workspace for web page creation and an attached document directory for word/xls/ other small documents. 
  * An Ajaxplorer-based file portal to access their directory (bulk upload) and access to larger data stores as requested.
  * A sympa-backed mailing list for group communication
  * Common authentication to all services backed by a dedicated LDAP/Active Directory
* Services available by request include
  * ArcGIS desktop (virtual desktop) and server instances
  * Alfresco document management
  * Access to MS-SQL, MySQL, and Postgres (gis) database servers
  * dedicated phone conferencing or Adobe Connect host accounts
  * Virtual desktop support
  * Large (10's of TB) project storage

**What percentage of your researchers utilize your provided resources?**


**What new capabilities are you planning to introduce in the next 12-18 months?**

* Enchanced group collaboration tools to allow google-docs style editing of documents, based on sharepoint 2013.
* Remote access to database and computational resources.
  * Currently research access is acomplished primarily via remote desktop or remote shell.
  * With products like sqlshare, R studio server, R studio Shiny, CartoDB, offering web-based access to computational resources appears much more practical and no longer requires substantial in-house development


**What resources (computational/storage/personal/other) do you need that would assist you/your center?**

* Training resources for researchers would be appreciated. Our community is in need of generic capacity building


What externally supported resources do your researchers/staff rely on?'''
* Many researchers use thier own Dropbox accounts to share data. Occasionally, collaborative whiteboarding tools are used (etherpad, etc)

**What resources would you like to rely on from other centers?**

* We would like to use external, 3rd parties for long term archiving of new digital content. Currently we are oddly positioned in that we do not and will probably not be considered a primary data resource for any one community (social, hydrology, remote sensing, etc) and have been pursuing a strategy of playing matchmaker between the researcher and an archive best positioned in their with respect to their community.

**What evaluation mechanisms/procedures do you have in place to evaluate your center's deployed resources with what your community requires?**

* Internal, yearly review of all deployed services, analysis of usage and evaluation of effectiveness, including 

**What needs analysis procedures do you have in place to evaluate the resources required by your customers/researchers?**

* Prior to each group starting an initial internal review of their CI needs is performed.
* A priming caoncerence call w/ a group's PI's (or postdoc) is performed and computation, data inputs/outputs and group communication strategry is discussed.
* Periodic followup during the life of the project as well as continual evaluation of data products.

## Communications

Please describe the communications capability of your center, and the communication mechanisms in use by your researchers. If possible, please provide approximate percentage of center researchers/staff which use or are impacted by specific technologies.

**What other communications mechanisms do you provide to your researchers?**

* Mailing lists
* Adobe Connect
* Wiki/Drupal Commons
* Conference lines

**What external mechanisms do your researchers use to collaborate/communicate?**

* See above

**What software do you currently use to support video/tele-conferencing?**

* Adobe Connect coupled with a dial-in conference line for > 1 attendee, or uncontrolled entrance/exit
* Skype for point to point/single person. Small meetings will occasionally do multipoint skype depending on participant

**What is your scaling capacity for in-center meetings (# rooms, #participants), do you have specialized hardware/software to support conferencing in these rooms?**

* 3 conference rooms (30, 12, 6 people). All Rooms have full conference coverage and microphone density to allow for conferencing.
* Center can be configured for a single, large event of up to 50-60 people in our open space. Broadcast from this configuration is available, however conferencing is not
* One mobile conferencing cart that can be used our common area for ad-hoc group collaboration. 

**How many remote participants are you able to support (both interactively and webinar/broadcast)**

* Current adobe connect license support up to 25 attendees per meeting, additional seats can be purchased for webinars
* Face to face Adobe connect calls tend to max out at ~6-7 individuals due to end use bandwidth and latency issues

**What new teleconferencing / collaboration requirements or features have you identified that are not met by your current conference offerings?**

* Tools to effectively brdge the gap between remote and local participants are still not easy enough for common use
  * Shared workspaces, documents etc.
  * Given a conference room with 3 whiteboards and a number of large 3m wall-sized post-it pads, how do you share information?

**What difficulties do you currently encounter with on-site and/or remote participants?**

* We see about a 60% flawless meeting join for individuals connecting to Adobe Connect AFTER previously testing connections
  * End user laptops/desktops tend to be highly variable. Headsets, speakers, webcams, devices frequently change between testing and actual meeting
* We've developed a fairly detailed testing procedure for walking remote participants through using Adobe Connect and require testing before meetings
* We're in the process of developing training for on-site participants regarding the best practice for running meetings with remote participants
  * Items such as how to ensure the remote person is included.
  * Document sharing
  * chat, whiteboard, discussion practice.

## Data Management

**Please describe any storage resources you provide for your research groups / postdocs? Including type of storage (object/posix/etc), amount, and how it is accessed.**

* We provide posix-based storage for all research groups. 
  * By default we only provide document storage (small gigs of data), but can allocate TB sized data volumes as necessary
  * All data volumes can be attached (cifs/nfs) to any virtual resources that have been allocated and they are made available for remote access through our Ajaxplorer file gateway.

**Please describe where you deposit data for long term preservation and what types of process are required for deposit**


**Please describe any external data sharing your center or its researchers participates in. Do they use e-mail, use dropbox, iRods, gdocs, S3, etc?**


**What are the characteristics of the source data you deal with? Format, size, count, sources.**


**What are the characteristics of the data products you/your researchers generate?**



## Researcher/User Description

We’d like to get a feel for how similar or different the researchers/center visitors are between each of us. Could you provide a description of your community, its skills and needs. 

**What type of analysis does your community primarily do? Modeling, gis, database development, statistical analysis, etc**


**How technically proficient is your community (programming skill, modeling/scripting ability R,,Matlab, Excel,etc)**


**What tools does your user community use, and where do they access (in center, home organization, 3rd party)**


**What resource requests do you most often turn down?**

* Requests for a full or part time post doc to do data cleaning, harvesting and aggregation.
* Software development

**If you host working groups, what technical resources do your groups use to facilitate collaboration? How comfortable are they in cross-disciplinary collaboration?**



**On average, how much support are you able to provide your researchers in terms of programmer time, consultation, etc.?**

* We are able to provide consultation service, one-on-one or small group training (1-2 days), if requested. 
* During times when we can find interns, we will task them with assisting groups in data-loading tasks.
* Due to the large number of groups and program structure, we do not assign programer time and/or postdoc to projects. 
* Postdocs have full access to all it staff and programmers. We have a focus is on training postdocs/in-house researchers.

**How comfortable are your users with collaborative, sharing technologies (data and document)?**

* Expertise varies widely between groups


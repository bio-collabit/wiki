---
title: Editing 2011 Workshop/Day 2 Unconference
layout: default
---
# Day 2 Unconference

## Track 1

### Domain science reality check  

(see also [raw notes at Google Doc snapshot](DomainSciRealityCheck.doc))

Context: Discussions offline centered on problems getting contributions that would enable answering the big questions.  Domain scientists feel ignored by the C.I. world and this is the path to getting down the entry point challenges and a path to use.

Our problem is demand.  Domain scientists are consuming more infrastructure than we can provide.  There is confusion as to what the issue is.  If we don’t know the infrastructure entry point yet, why is there so much use?

Tools for genomics exist, but we are biologists, ecologists, etc.

Too much blame for domain scientists.  IT community needs to engage DS.  Stop blaming and get more DS involved.  Get more DS involved long term by incentiving it somehow.

Incentive for iPlant: iPlant gives me a summer salary and benefits.

Problem may be that the product does not provide an immediate benefit … benefit must precede CI success.

Need to solve data sharing and get people to contribute before it is useful.

Scientists follow the utility.

Journals require GenBank before it can be published.  It makes the difference in genetics data.

* Agreement - data requirement is transformational.

Genetics is weird.  There is an “ethical” consideration for publishing in genetics.

Phylo - huge benefit and need for CI, but cultural issues prevent penetration.

* TreeBase - but doesn’t do synthesis.  More broad use requires CI.
* Rapid increase in publications in phylo.  TreeBank growth much more slowly.
* Selective publication because inclusion of data is not universally required.

Incentivization: Decision made not to morph into incentizes discussion.  Let’s look for “Aha”.

Tenure path does not require CI.

* But: Path is to make useful CI and use it
* Genetics data resources already exist, I can do big things there.
* CI needs to grow with field, not be up front and imposed.

Is data sharing problem part of CI or is it separate?

Basic issue: How much up front time is necessary?  Do we need an external reward structure, or will the first useful implementation result in a growth.

How much time does new domain faculty need to invest before the get pay back in terms of publications/career.  Do we need external incentives, or not?

Morph{o}bank has an issue because it takes too much time to deposit images there. Very contextual data.

Incentives aren’t necessary.
* But cheaters win in that situation.

Genomics imposed sequence data sharing from outside via high powered coalition (senior researchers) and journals.

* This is missing from ecology.
* Recognition of frustration about not being able to get data behind publications.  

DRYAD, differences exist among specialties.  One of the realizations of DRYAD is that evolutionary and ecology have similarities.  Lots of people doing lots of small stuff and not everyone is working on federal funding.  That explains the push through journals instead of through federal funding agencies.

* No fundamental difference in genomics  - some small science.  The issue is value.  Researchers get value from using genetics CI, so they use it.

Why is Galaxy successful?  Other workflow tools exist, why is this a winner.

* General architecture built on specific case.  Strategy from day one is to help do research and the tools support the research.  When the tool doesn’t fit we change the tools.

Why do documentation?  You don’t need it for your personal use.
* There is some reward structure based on funding and publication that give rewards.

The concern is that CI needs to have domain scientists involved.
* Is this an overstatement - most CI projects do have DS PIs (at least from NSF).
* There are two ways at NSF: (1) Building domain CI for specific questions with CI generalizable.  (2) Also do CI PIs with formal DS evaluation.  Won’t generally fund unless there is a strong DS collaboration, although, not necessarily DS PIs.

iPlant uses biologists talking to CS via translators.  Not completely open.
* Need CS responsive to biologists needs.
* Did iPlant people consider Galaxy? They are now.
* Hard to break into the decision making structure of iPlant.  Can we learn lessons?
* Does anyone use iPlant-generated CI? → Unusable.  Classic problem, giant project, but in the end little progress. Not geared toward a community wide effort.
* iPlant in some ways is an experiment in a software development model.  Paltry amount of support. 
* CIPRES - big NSF investment, we should look back and evaluate success.
* APWeb much more useful.  Peter Stephens has excellent tool for phylo.  Constant use, hand written, needs tech upgrade to give him resources and tech savvy.

What about the iPlant/CIPRES model didn’t particularly work?
* From NSF perspective, imagine iPlant a distributed synthesis center.  Can you tell me what works versus what doesn’t work.
* NESCent gets money and invites the community to contribute.  iPlant is more closed. 
* iPlant has core cyberinfrastruture group that exists to do your work … how is this different?
* We don’t feel that we are invited to participate.
* 2 Grand Challenges (iPlant) versus 1000s of visitors (NESCent).  iPlant is much more closed and focussed.
* iPlant model is not bad, but is controlled by a small group.
* It is a bad model.  Core CS group isolated is a known bad model.  Distributed intermixed CS/DS is a known better model.

We need to figure out what is working and what is not.  NESCent seems to lack direction.  iPlant lacks openness.  How do we get an efficient mechanism.

DS needs to put down aversion to computer programming and not hand it off to isolated programmers.

No integration of small scale tools with larger generic play to develop cyberinfrastructure.  We seem to be talking past each other.

Model has been to build big structure then figure out how to bring it into the lab.  Bottom up should be explored - local practice to central.  Models are being developed but it is not solved yet.

Model is Biological Ontologies center.  Biosharing.org is a resource in this domain.

### What is a minimal CI acceptable / Think about CI bottom-up  

(see also [raw notes](Media:May-19-track1-minimal-CI.doc.html) by Mike Smorul)

Participants: Chris Baron, Shaun Walbridge, David Huyhn, Suzie Allard, *Massimo Di Pierro* , Mike Smorul, *Vladimir Gapeyev*. [All but one are IT people; no domain scientists...] 

Given that this was (almost exclusively) a gathering of IT people, we ended up focusing on what we perceive as basic CI problems, rather than what domain scientists could have perceived as such. 

Major CI issues that we, as IT / Informatics support encounter every day: 

* access control 
* file sharing 
* versioning

We believe that these problems are not domain-specific and should be solved by existing general purpose technologies. 

First approximation of CI for Collaborative Science could then amount to a set of best practices for the above (and other) issues that, ideally, is maintained up-to-date. These best practices would amount to evaluations and recommendations regarding software or services that are known to work well and tips for deploying them. However, we are wary of recommending closed "free" web services (e.g. Dropbox, Google docs) that come without guarantees of service. 

The next approximation would be one or several deployments that follow these best practice guidelines and are available for use by qualified scientists and communities. These could be several installations run at the Centers or a single dedicated installation. 

Two more general themes ran throughout the session: 

* There is a tension between long-term benefits for collaborative science (e.g., data preservation) vs. the immediate benefit for scientists (e.g. visualizations) The immediate benefit could be used as a "carrot" to facilitate CI adoption.
* Effectiveness of the CI effort would probably be improved by establishing regular communication and exchange of experience between the IT personnel of the synthesis centers.

### New Visions of Workforce and Institutions For Developing and Supporting CI 

Round-table: pondering the adequacy of existing solutions, what works and what doesn't. 

#### **Workforce**

* Roles for Information Professionals: Interoperability, Standards, knowing where people were doing work, where data is being stored, where data is being processed. Need people working at all points in the data management lifecycle (data ecology). Need training for people to fill these roles. Need people with the necessary background in the scientific domains, but want to understand and work in the information science. 
* Need more business/corporate skills. Is CI an academic pursuit, or best built by professional developers? What is the career path for these CI people? Do you get a publication? How to get publications? 
* Need for hybridization/specialized staff 
* Computer scientists and domain scientists. When developing CI, how to identify the balance between domain experts for determining the function of the CI. How to educate the next gen hybrid level experts. 
* CI: a metaphor for Journals: get ideas across, maintain high-quality communication 
* Academics identify with a discipline, not an institution. CI is developed by an institution.

#### **Institutions**

* Cross-sector needs: gov, edu, com 
  * Synthesis centers: focused on a discipline or a set of disciplines. Give validity, represent community, enabling framework 
  * Virtual Orgs: additional overhead 
  * CI Domains: supercomputing centers -- focused on technology 
  * Universities: diverse set of disciplines, no cross talk across diverse disciplines 
* Facilitate and enable: XXXX synthesis research. Examples/tools for enabling/integrating did not exist. Need institution to promote a type of synthesis activities. From this, the community can rally behind/become the seeding factor. Institutes/centers have name, impact, and branding. Viewing institutions as individuals.

#### **Support**

* Currently: Minimal support. Need to address who is going to do the support and to whom is the support destined? 
  * Different tracks, different sectors, different "funding" sources 
* Help/documentation: through portal, on-line community groups 
* Need both shallow and deep training -- accounts for different disciplines 
* Support: maintained through a community, but still need to get funding to provide the support. The community is the users and the developers. Want to maintain a natural tension: grass-roots compete to become dominant. Winner gets support to grow. Grass-roots now get to compete against the dominant AS LONG AS there is **an open standard** from which to build their new ideas. 
* What is the elevator speech of "what is CI" to a science domain expert? 
* Need to come up with best practices. 
* Need to develop hybrid domain experts to aid the translations and transitions between fields. Need to make sure they have career path and professional support. 
* Disseminating information to "users".

#### **Development**

* Developing for future needs (what to anticipate) 
* CI: is a **resource to consume and a collection of standards**. Must have **open APIs to permit interoperability**. Must have a set of standards so that CI may talk with one another and others may write apps for and against the technology 
* The need to differentiate between innovations versus using previously built solutions. 
  * Tension between: engineering a system versus creating a system 
  * Tension between: getting a set of functions to work versus getting a set of functions to work robustly (time to deliverable) 
  * Tension between: Short term development and long term support 
* Make sure to keep the distinction between CI and computational technology 
  * CI helps keeps track of the technology

#### **Other** 

(CI) Location of computation: local systems versus distributed platform (web/cloud/portal) 

(General) Keep in mind: Scalability, Adaptability, Extensibility, Usability, Approachability 

## Track 2 

### Development of Standards and Specifications  

Standards and specifications provide utility throughout the technical and scientific communities, but how can we create them, and should they be imposed on the community? If so, should it be community driven, by funders, private industry, or implicit through tool usage? 

#### **identified needs and uses**

We want to develop best practices and standards for phenotypes and knowledge representation. Don't know where those standards will end up. There is a consortium for the gene ontologies, but how will people find them outside of that group? 

* In Physics, standards are about annotating the data, and discovering the processes -- describing the data is straightforward, but not describing the processes. Cluster people based on what they work on so they can communicate to one another, have them work together on a specific problem. 
* Most social scientists aren't aware of standards and how to apply them. Major problems: granularity of descriptions and relationships among datasets. Scientists often look at the individual dataset for a specific location, but when you change the context its often difficult to relate to other data. National Ice datacenter does this in a nice way, how can we propagate out information from scientists? How do we browse and understand a large landscape of data? Data Conservancy; is thinking about things from primarily a semantic perspective, but also lots of metadata which is just contextual. 
* Metadata as needs-based: what do we need to do to push the science forward? We can reuse existing data formats and standards for many things, but sub-domains often don't have specifications. Some ''data'' doesn't lend itself well to standardization, so best practices should be a stand in, or instead take actions which provide value to users by adding value to the data (e.g. ASCII to map on the web or simple summarization and visualization coupled with Storage, API access). Standards ''must'' be coupled with tools. 
* Identify standards based on use cases and needs. What types of data do we need to capture for the external participants to use the data, since internally the processes often already work. How do we find best practices: finding the balance between flexibility and compatibility. How do we get community use and buy-in on a specification we want to be a standard? 
* Standards and specifications are an *essential* part of interoperability. Engineers know the process which goes into the standards and specifications, and how important they are to the internet, among many other pieces of technology. How can we extend this to meet the domain needs? Who needs to participate to these efforts?

#### **formats in use**

Formats in use: NetCDF: useful metadata built-in; GFF, Genebank; ASCII Grids, Shapefiles, plain ol' CSV files (UTF-8 text); auto-generated metadata from GeoTIFF, FGDC; API for services using JSON; a spreadsheet with mappings for schemas and application profiles; Gene ontology, phenotype ontologies (evaluating GO); ISO, EML, Darwin Core. 

EML is a de facto standard, but it isn't certified by anyone -- its just a specification. How do we construct ontologies to be useful? semantics and ontologies is where things are moving, but there isn't an NIH-like organization to push these forward through large block funding, so its the wild-west. 

Massimo: 7-8 yrs ago, all scientists were creating files in different ways and formats; they created a standard for both the data and the file format (for physicists; XML based), but no one used it. However, the files are kept in the national laboratory, and now we can mine the data, and extract out metadata where standard naming and locations are used. 

#### **intentions and needs**

Standards can become so robust that they're impossible to create a specification which implements them. For collaborative data scientists, its the wild west: how you should pull apart the data remains a challenging issue. Scientists need to be involved in the standards bodies, efforts are commonly hijacked, and scientists have to organize to make this happen and engage communities creating standards. 

#### **how can domain scientists and technologists interact?**

We need synthesis centers to pick people and place them into the role of interfacing between scientists and the technology --- this will be critical in the long term. The library scientist may also be a relevant role to get involved. The technologists at synthesis centers are often just trusted to get the technology right, but how do we do this stuff, and do we have the workforce to do it properly? The issue is something which spans the domains and requires coordination. 

#### **wrap-up**

All of these approaches will only really work if we develop the tools to make the life simpler for the user: they won't do it just because it helps science 'in the long run'. We often start with free text, improve it with annotations, and now we're starting with reasoning and smarter data structures -- the things we're doing now are temporary ways of aggregating simple data types and combining them together. Often, you need a 'standard' for your standard, AKA a best practice. 

#### **group report-out**  

Review of what we mean by it: at what depth do we standardize? The engineering community has been highly effective at using the standards process, but how does it apply to science needs? Standards give us a whole lot of value, especially if you look at data formats. On the frontier of semantic utility, but we're lacking content of specific domain uses and proper tools to use them. Individual disciplines have to provide the content for the process to work. 

### Social dimensions of sharing and storage + Facilitating interdisciplinary collaboration  

* Leader: John Parker 
* Session 2: Conference room 2 
* Brainstorming on social dimensions of sharing and storage 
  * data sharing and knowledge sharing are different (former is technical, latter is social) 
  * agree on common tools / low level mechanisms 
  * data trust: previously, based on social networks but this does not scale 
  * tragedy of the commons problem with data sharing: community vs individual good 
  * jealousy and hoarding 
  * living in the moment: taking away from that paper, that grant proposal 
  * making sharing fun / game-like vs need to do serious / important work 
  * standards: hard to define, hard to impose 
  * loss of control over data 
  * provide benefits to data sharing for users 
  * providing storage: not fun, should be highly regulated &amp; serious, militant 
  * sticks (e.g. data management plans) good but making it fun / cultural is better 
  * tenure decisions: could data sharing be a good point; should be at a level above service, as research output 
  * who owns data? if research is funded publicly, how can scientists *own* their data? 
  * incentivization: not just sharing data, but sharing quality data 
  * do we continue to own data after we publish, if we fund our own research? 
  * creating value in data sharing; time required to share data is huge 
  * wide spectrum of attitudes on data sharing 
  * sense of exposure when sharing data, feeling *naked*
  * there are real risks (e.g. tenure) associated with sharing data 
  * misuse of data, harm to science / reputation due to misrepresentation 
  * development opportunity for CI: capture and contextualize data 
  * data is blind without theory, need to collect theory as well as data 
  * future needs and anticipation; build dynamism in workforce and CI 
  * how can we an individual researchers push the community norms for data sharing? 
  * stigma associated with focusing on issues of data rather than being a real practicing scientist'

* Brainstorming on facilitating interdisciplinary collaboration 
  * collaboration across disciplines: norms, language, processes 
  * cultural diversity and misunderstandings; think everyone operates like me 
  * what is data is different across fields 
  * there are skill sets associated with interdisciplinary science, requires training e.g. IGERT 
  * generalists not as well rewarded 
  * publishing difficulties, picking journals that benefit all co-authors 
  * incentives differ across disciplines 
  * what do we want to facilitate? f2f collaboration? virtual? 
  * CI roles: 1. a platform for translating data, concepts and methods between disciplines; 2. different reasons for interdisciplinary work; must develop in light of this 
  * government, academic, industry collaboration - go beyond cross-disciplinary academic collaboration 
    * working mostly with government aides, not elected officials; there is educational issue; do not understand evidence-based approach 
    * reward structure needed at university level; mentoring important 
    * how is is profitable for industry to work with science? 
    * need different metrics for these collaborations 
  * CI building is an interdisciplinary collaboration 
    * CS goals different than those for building CI 
    * CI development goals and PI goals can conflict 
    * DataONE has solved this: CI side and community engagement side; strong communication between the two sides; domain scientists on both sides and have been successful w.r.t publication and grants 
  * be sensitive / careful about cultural differences when building CI 
  * if CI hard codes data sharing workflows, policies, may alienate some communities; need to be flexible

*Common themes 
  * CI should not only be geared to experts 
  * flexibility: must react to different / changing cultures and questions 
  * need for training and mentoring: 1. across disciplines; 2. to change attitudes 
  * sensitivity to different incentives across disciplines (risks and rewards) 
  * timescales over which scientific practices change 
  * resistance to data sharing are both personal and structural 
  * tension between making data sharing / CI fun and making it serious

### Killer app 

Much of goal of cyberinfrastructure 

iPlant was interested for some time in killer app, but seems to have backpedaled. 

One thing you need is right idea. But most people who think they have the killer app idea doesn't become a killer app. 

How do you make it become a killer app. Assume that many ideas could be killer apps, but die due to execution. 

Killer app defined as something so compelling it proves the worth of a technology. 

Should we restrict this to applications per se or or web service. Take broad view. 

Dropbox is an example of a killer app. It solves part of my computer problems. 

Dryad as a potential killer app. Achieves larger goal of encouraging evolutionary biologists. 

Main focus of discussion: killer app something that widely adopted -- killer in its impact. 

A killer app could be limited to within a group. 

There was a tension in bio between reductionist and integrative approach -- maybe software is in the reductive approach. But maybe killer app occurs at more emergent level. But interaction of technology with individuals matters. The ones that win take on the ecoystem approach (facebook, amazon, ebay). Tools that allow us to tap into ecosystem of our peers would do better. 

Mendeley: joins endnote and social stuff 

Does the arc (slow growth vs burst, like angry birds) matter? 

Killer app: are we talking about how to drive adoption of a technology? Or just get a popular software application? 

Argument that successful scientific apps show pattern of killer apps. 

Cytoscape growing as way to visualize interactions, has plug ins, including commercial plug ins. 

If it is truly successful, solves problem well, it is a killer app. 

Mesquite: potential killer, but usability, high barrier for developer entry. 

Before people adopt it for social, it has to be addictive, easily accessible. 

But we care about app becoming addictive because it enables science. 

What is meant by collaborative science? Allow transactions vs interactions. Dropbox allows transactions, videoconference allows interactions. 

There are two sides to a killer app: 1) value for target users, 2) how does it fit into our agenda (what do we want it to do in long term&nbsp;: best practice, drive social network, etc.) 

But issue in this discussion isn’t what to drive, but how to get people to adopt app. What do I need to do next not to fail. 

You want to catch some sense of what value people see to use it. Their decision to use it allows many things. Creates big user base. 

Perhaps focus on what features create early adoption. 

What are the functional requirements of doing collaborative science, how do we support that with cyberinfrastructure 

Initial problem of rapid adoption. If it allows someone to do a new thing, that drives adoption, then you can extend that later. 

Has to be good for users, has to allow for long term cyber infrastructure. 

What is now Google refine started as way to clean data for freebase, then released as open, then got adoption by others. They worked with data so knew the problems and solved the problems for themselves, not for other people. 

Does google have a long term vision: it seems to be acquiring and aggregating successful memes to advance the enterprise of google. Operates like natural selection, local optima. 

Natural selection is the metaphor, but it is like a zoo -- NSF feeds it all. How would NSF change support so that it becomes more like natural selection? NSF tries to fund cutting edge, not most scalable, useful. 

Perhaps use could be part of broader impacts. 

Interaction with users matters a lot in market world. Happens on a quarterly basis. With funding model, it happens on a 2-3 year time scale. Focus on project deliverables, not changing to meet demand. 

Software development: tracking users vs investor. 

Tracking users vs. functionality. 

NSF emphasizes novelty for novelty’s sake. 

Metaphor of NSF as investor in software startups 

NSF doesn’t want to fund next logical step. 

Novelty doesn’t have to be in basic science idea but could be something in deployment strategy. 

NSF needs things to be available, but not necessarily free. So funding through cost recovery by fees is fine. 

Beauty may matter in app uptake. 

Lots of examples in commercial where it was built and they came. But in academic software, we think this doesn’t happen. But maybe commercial services do market research and so know their audience. 

Is it justified to approach academic/science software dev so differently from commercial software dev. 

Most commercial software projects fail -- need that selection. 

In funding for agencies, desire for lower risk, so less variation. 

But a lot of software projects in science aren’t funded, just people scratching itches. Lots of tree visualizers, not a lot of selection. 

Microsoft Research: lots of research, most fails. 

Hard to predict what will fail. 

NSF doesn’t punish for failure, as long as there are projects that come out (publications, methods, ideas), not necessarily finished projects. 

It’s a bit like trying to predict transformative research. Most killer apps (ie. visicalc) weren’t designed to drive adoption of platform, but had that effect. 

**Possible characteristics of killer app (and subsequent wanderings)**

* Killer apps might leave creative decisions to user -- they can integrate it into their workflow. 
* Has to have an attractor: a “honey pot”. Something that drives frequent use. Something compelling. Social software is one such attractor. Think about the environment that needs to be created. 
* But think about facebook vs. myspace, friendster: why did facebook win: 
* Lots of reasons: maybe because the cool people were using it originally (like zune vs ipod). 
* Utility is very important. 
* What value proposition for the target user 
* What is enabled by rapid or wide adoption (“emergent capability”)? 
* Start by solving your own problem, because that is best understood 
* Market forces are being suppressed by NSF funding mechanisms 
* Users vs. functionality 
* Novelty for the sake of novelty 
* mismatch of federal funding priorities to next step needed of cyberinfrastructure 
* Novelty process could be in e.g., deployment process/strategy rather than science or technology. 
* Funding means of popular software could be through cost recovery by fees (e.g., support)

**Lessons learned from Google Refine (f.k.a. Freebase Gridworks):** (added later from the Google Refine tutorial):

* Do one thing well 
* Feature casting 
  * Leading role: clustering, mass editing (value proposition) 
  * Supporting role: faceted browsing, undo/redo 
* Think of providing a canvas for users to get creative (and surprise themselves) 
* Screencasting 
* Amateur social engineering 
  * Unassuming, innocently looking 
  * Small tool shapes big culture (of habits, practices) 
  * Addictive like a game: challenge/reward cycle (e.g., see “The Art of Game Design” by Jesse Schell) 
     * Easy enough to start 
     * Compelling enough to keep going 
     * Hard enough to feel good when improved 
  * Spectrum of expertise-levels among users fosters communication, and role development 
  * OK to be unpolished - encourages feedback
* Prior failures that you don’t see 
* Vision and promises that we didn’t see

## Track 3 

### How to get users? Managing quality vs. community participation  

[https://docs.google.com/present/view?id=dg88m8wm_12c7ck4jcw] 

#### **Major Questions**

* Who are the users? 
* What are the needs of the user classes&nbsp;? ( How do we drive them out&nbsp;? ) 
* How do we give them what they want&nbsp;?

**WHO ARE THE USERS**

* Domain Scientist Users - Create the data 
* Intermediary Users - take the data and manipulate, characterize, put in database 
* Domain Specialist Reusers - dry data users

 Cooperation - Collaboration - Partnership 
 Self-----------------------------------Other 

Career Stage: Distinction between grad students, senior pi, undergrads, young pi, post doc ( Career Stage ) 

Senior PI -> undergrads -> grads -> postdocs -> young pi -> senior pi 

Considerations: 

* Early adopters ( Grad, PostDocs ) 
* Career stage 
* Time commitments 
* Institution type 
* Willingness for Risk / Reward

Data types: Code users - toolkit, app, end users Data users - domain (wet) , intermediary, domain (dry) 

**NEEDS OF USERS (attractants/detractants)**

Like: 

* Easy access to data (import / export / liberal licensing ) 
* Critical Mass of community 
* high visibility 
* leading edge 
* social advantage 
* responsiveness 
* involvement

Dislike: 

* complicated 
* low usability 
* unwelcoming culture 
* culture difference (academic vs geek )

**GIVE USERS WHAT THEY WANT (solutions)** 

* Data access: import / export / liberal licensing 
* involve HCI at the beginning of a CI project 
  * usability 
  * sociability: Its difficult to get CS people to make a useful product for the users because the CS people don't have an interest in the users. 
* solve one problem well, don't be a swiss army knife 
* publications 
* attribution to contributors and users 
* build in time for support

### New technology / New skills 

* Potential growing chasm between domain scientists and technologists with respect to moving into new emerging technologies 
* Need curriculum changes so that domain scientists are better trained in coming up to speed with new collaboration technologies.
* Recognize that new technologies require new skills.
* Programming skills (at least at a basic level) are needed from a much larger number of domain scientists. Programming should be part of the training for relevant domain sciences, such as ecology and evolution.
* As a note of caution, this has been advocated for a while in genomics, with the result that many people now know enough to be dangerous, which has arguably led to a reproducibility crisis.

### Software recommendations  

[Report-out (in the form of slides with tables)](Software.pdf)

Discussion notes:

* iRODS for file sharing? Being explored at iPlant
* Whenever human subjects are involved, legal issues appear with outside and cloud storage.
* Stephen mentioned another technology

### CI Success stories and lessons learned 

#### **Success stories** 

Success stories were limited to the people in the room who felt comfortable reporting on a project.&nbsp; Other success stories can be added to the wiki. We also looked at "successful failures" which we defined as failed activities/projects that provided us with the basis for some of the "lessons learned."&lt;u&lt;/u&gt; 

**Galaxy**- James:

7 years old, grew out of comparative genomics, CS/microbiologists, inefficiency in how we work together. Microbiologists know questions and how to answer but need tech power to get it done. Galaxy provides intervening infrastructure. 

1. it adapts to tools available – add layer on top
2. provide easy to use user interfaces
3. provided as web service, but was self contained and easy to install so it is easy to develop integrate and test tools
4. number 3 reduced barrier to entry
5. easy for developers to participate, easy for scientist to use
6. provenance automated, workflow included
7. layered evolution – simple framework adding functionality as time went along.
8. It is moving away from centralized resource, moving to distributed model.
9. New addition is exchange for tools and work flows, feel they can cultivate best practices this way
10. Leverage existing 

**DataONE** [www.dataone.org](see [www.dataone.org/dataonepedia]; for best practices and tools databases) – Suzie

Emergent organization funded by NSF focusing on environmental science domains

1. use existing tools as basis
2. Domain scientists play a central role and brought others on-board
3. Strong communication between all parties in CI and community engagement
4. CI and CE have iterative relationship during development
5. Partnerships/relationships important – working with Data Conservancy etc.
6. Leverage existing resources
7. Structure lite but plan for increased functionality
8. Involve community via working groups and users group 

**SIGS** - Matt 

Genomics consortium. Online journal Standards in Genomic Sciences. Need lots of contextual data and metadata. Tie incentive to journal – not high impact science but rather a way to recognize standards compliant data. 

1. quick turnaround
2. use existingin incentive systems to our benefit 

**Australian Examples**- Marco **ANDS** ands.org.au

1. encourage institutions to store own data. 
2. Built catalog system and encouraged institutions to send appropriate data by building tools
3. Seeding the Commons – funded programs at each university that would supply the data. 

**Integrated Marine Observatory System** imos.org.au

Includes marine data from Australia. Has lots of data from state agencies etc. Open source software.

1. marine data resource intensive so it was easy to enforce standards
2. People seeking services to put up data
3. Community participation high 

**Data Conservancy** dataconservancy.org – Carol

Discipline agnostic so highly multi disciplinary. Some are resources that only need home for sustainability but also taking in small science that don’t have disciplinary repositories. Will support site based feeds and how to move it into conservancy environment

1. Research library is center which gives landscape view
2. Provides promise of sustainability
3. Provides service orientation that is agnostic but allow search, discovery, use and preservation 

**Kepler/CAMERA** -- Matt

Similar to Galaxy. This is about how CAMERA implements Kepler

1. How do we move things developed to lab into open use
2. Open use can have different levels – lab, community, public etc 

**NESCent** www.nescent.org – Hilmar

It is not a cyber infrastructure but it connects people to do collaborative science
CI is based on following observations: Technical impediments are CI gaps; Little if any interoperability between existing tools; Looking at domain there is sophistication and capability for creating methods and models and even creating software 

1. Focusing on filling tech gaps
2. Nurturing, building, sustaining, bringing people together as community
3. Doing things to mentor students to build collaborative and communication skills to do collaborative science 

**NAMIC** – Stephen

National Alliance for Medical Imaging Computing. 4 driving bio problems that are similar at a level similar for many diseases. Created NAMIC kit which had to be done under licensing for free distribution etc.

1. to participate must agree to licensing
2. Involved computer scientists and radiologists
3. self contained entity to address many issues such as data management etc. 
4. If kit installed then that location became a node in CI so it was easy for labs to set up small networks and do small level grid computing etc.
5. Can participate at national or international level in database that was heterogeneous mix . For example powerpoint that has describes workflows as a training tool.
6. Lots of documentation and strong community for support
7. Has grown beyond funding scope and now has community supporting efforts
8. There are automated tests to match powerpoint descriptions that test software to see that it matches and that software will be high quality
9. Record of who has contributed and who has published. This records impact and helps prove sustainability. 

**NCEAS** – Mark S.

* Initial scepticism about value of Working Group structure: rapidly transformed to belief after stimulating and insightful interactions 
* Initial scepticism about re-using existing data-- belief that these were already intellectually depleted by first pass publications soon diminished after high success publications 
* Many successful secondary collaborations and networks catalyzed by initial NCEAS&nbsp;WG 
* Growing realization about importance of CI to support collaborative, integrative research 
* "unmentored" postdoctoral culture produced outstandingly scientists:&nbsp; unconstrained, and diverse assemblage fosters broad innovative thinking 
* John Parker should add some more perspectives here

#### **Lessons learned**

1. Manage expectations 
2. Be careful what you invest in – don’t invest in something that is not succeeding just because a lot of time and money has been invested
3. Keep technology solution on-task with the scientific problems --KISS
4. Projects do best when they are led and/or road-tested by the domain
5. Consider an epidemiological model of CI – take something that is working even if only in a small group and see how to offer it to larger scale of the same community
6. Balance is important – keep balance between CI and science
7. Reuse existing technology that has been proven as much as possible
8. Minimally modify the scientists’ process
9. Communication between parties/entities is important
10. Community should be invited to participate, a closed community not as successful
11. Disciplinary culture clashes can inhibit CI success or cause failure
12. Seamless interoperability – people’s data/work needs to be able to move across different systems
13. Don’t be afraid of failure, beta-test on users and then fix it. Don’t wait for perfection.
14. Scientists are often uncomfortable working with emerging systems – want it to be robust from the start. Pick a beta-test group carefully.
15. Consider the tension between domain scientists and technologists. Find ways to improve this.
16. One bad experience can sour a user/scientist; trust can be lost quickly. Control expectations and manage relationships carefully. 
17. “micro finance” groups that can add to the CI development (such as students)

## Track 4 

### Reward / Credit for collaboration 

1. Find a way to build CI within the existing rewards system
2. Identify short term and long term value propositions and rewards. 
3. Start with the low hanging fruit
4. Identify: what/who are we rewarding
  * Building CI – software engineering, domain, information specialists
  * Sharing data – domain scientists
  * Collaborating – domain scientists, technologists, info. specialists
5. Embed reward in CI design
6. Data set citation – understand the complexities of different domain citations and create an appropriate reward mechanism, perhaps develop a relevant  reward mechanism based on citation of CI related work (need – automation of citation tracking)
7. Consider sticks vs. carrots (intrinsic/extrinsic  motivations).
8. Prestige – measured via use, download, etc.
9. Ad space – concerns about commercial vs. science tension.
10. Funding/economic rewards
11. Presence in main-stream media 
12. Showcase slackers
13. Improve interface for ease of use
14. Financial penalty – NSF should require data-sharing when funding,
15. Journals should set data sharing standards.

### Cross center IT interaction 

Possibly first time many IT people from different centers have met. 

NIMBios IT: 3 people: 1 web, 1 HPC + computational IT, 1 infrastructure day to day. Wide variety of other projects the IT staff do. Interact with working groups, modeling (programming models), leverage cluster. 

Is there benefit in using same software stack across centers -- similar scientists, some overlap, not negligible, but not most. 

Is it worth training users once -- have same technologies. But questions of technologies seem easier at first. Seems a no-brainer to not introduce new technologies when existing center has tried and true technologies. But tech changes rapidly. There is a risk of missing opportunities in innovation. 

There is an opportunity in starting from scratch. 

Make an umbrella wiki. Not have every center run its own. There’s a cost of administering a media wiki -- need to install and upgrade things. Doing that in a pooled way for multiple centers could reap economy of scale. Also, centers could specialize on particular tasks. Opportunity cost in developing a new technology: while supporting something, you’re not supporting something else. 

Pooling expertise is a good idea. 

MediaWiki, BioPerl, R: specialized skill sets. Centers could support them in the same way they support email. Recognize currently best practices. 

Several models:
A) Have some specialization (but all self-supporting) within centers and know who is good at what
B) Have a separate core group outside the centers
C) Have all mediawiki run out of one center, all R run out of another 

Preferred option seemed to be A: grow social network across IT within centers, learn who is good at what. 

Need infrastructure for exchanging expertise and experience. But not hard to do (versus issues with, say, having all mediawiki run from one center). 

NESCent just lost its sysadmin. You realize how complex the environment is in order to support domain scientists. Perhaps more complex than we need to be. Why not also host things commercially. NIMBioS uses Wiggio -- free. Maybe have NESCent pay for wiki hosting outside. 

A lot of mundane infrastructure that is duplicated: how people apply, how things are reviewed. It’s not machinery that directly helps scientists, just something that has to work. Why not a common package for center setup -- download and install. Could even be a virtual machine image. 

Save work on bootstrapping. 

Dryad is a good example: built off of D-space. 

Could have links between centers more easily: virtual brown bag lunches. 

Sometimes hard to have communication within diverse IT in house, but perhaps more similarity to people doing similar tasks across centers 

One risk is that collaboration infrastructure is complex, and can fail for reasons that are and are not your fault. Users don’t distinguish between failures that aren’t your fault with those that are. 

EVO: virtual teaching: phyloseminar, NIMBioS training in command line 

Can you collaborate on training users. I.e., coordinated push by the centers to get domain programmers online with DataOne. 

At each working group of ~15 people, each center could introduce them to data deposition or pushing cyberinfrastructure. Synchronize message across centers. DataOne training of users is required of NESCent and NCEAS. [note: they are getting subcontract for this] 

Similar to Long term ecological research (LTER) sites. Started 1986. By 1989 had data management committee. Wanted economy of scales. Fly committee together annually. Created a coordinating office to take over some of those functions -- i.e., annual PI meetings. Identify where they had common needs, where they were different enough to diverge. I.e., they made metadata standard. As long as you can show there are leveraging gains, there could be resources available to make that happen. Some challenges when you have a central group: is it leadership (“head office”) or just a service organization? Does it develop its own agenda separate from the component groups? But can effective way to deal with shared needs. Not expensive to do shared collaboration, esp. in centers designed for such. 

There are some differences between the centers and LTER: more turnover in centers, so even more need for shared knowledge. But probably always have synthesis centers. 

Creating joint standards will overlap with DataOne. 

Shared center problems: moving of people, shared need to evaluate performance. 

More challenging to change existing tools than adopt new tools. 

Easy targets are things that a center doesn’t do yet. 

NCEAS just adopted NESCent’s NEAD application to replace its own 1998-era Oracle application. Took more time to convert the NEAD code than to just write from scratch, but now have shared code base. 

Investments in things like NEAD, which don’t produce science, can be immense. $300K worth of people time in NEAD. You vastly underestimate how long this takes when you start. 

What are next steps: 

* Common IT wiki? 
* Common mailing list? 
* Need dedicated time for this -- maybe conference call once a month? 
* Common IRC channel? 
* Maybe one center presents an experience report on technology X -- was it success or failure. Informal cross center brown bag lunch? 
* Prototype set of checklist for new synthesis center -- suggested software stack?

### Mechanisms for encouraging and sustaining collaboration between domain scientists and technologists in creation of CI

**Participants:** Karen Cranston, Lizzie Wolkovich, David Huynh, Eric Carr, Mark Schildhauer 

**Challenges:**

* Agenda is different between fields-- i.e. comp sci vs biology/env sci 
* Domain scientists are not interested in process or testing, but in end products and reliable functionality 
* Software engineers vs computer scientists: must narrow the gap; must learn one another's vocabularies 
* Demos / mockups effective to elicit response 
* Changing expectations 
* Language barriers (demos / mockups can help) 
* HCI person can be invaluable (but can freak out domain scientists - another specialization) 
* Scientists don't have time to test, etc 
* Need "hybrid" (need better word-- polymath?) people who are both domain scientists AND CI people 
* *I wish I had more of a {biology / CI} background*
* Going too far down a particular road / writing code, especially when isolated, can be dangerous 
* Give data to the programmers-- let them "do" the analysis 
* The programmers sometimes have to go to the scientists (*I put on scrubs and go down to the OR to talk to the neurosurgeon I collaborate with*) 
* NIH funding: can never include computer science development, always couched in terms of medical advances 
* What can we do about that challenge (lack of time from scientists)? 
  * choosing the right domain scientists? 
  * who are the right technologists? (noting that they are generally funded to do this task, unlike the scientists) 
* if we train the biologists too much, they don't need CI capabilities (they can do it themselves) 
* the other scientists can't inform the CI development 
* devalued CI as a research field 
* the CI scientists / people passionate about CI are distanced from the other scientists (no longer close to the data)

**Opportunities:**

* build cadre "scientific programmers" 
* must support and encourage those rare people who are proficient in both domains 
* What might be role of industry, e.g. Google, in developing technologies "we" need? E.g. Google Refine...could assist with data confederation issues 
* NSF needs to support training of; "Scientific Programmer/Analysts" who can train and collaborate with domain scientists in CI, as well as inform and potentially co-develop CI for the domains. 
* New incentives must be provided to domain scientists to encourage partipation in CI construction, and a new type of researcher, whose primary role is analytical and informatics service (need better word)-- must emerge,&nbsp; as these people havemajor impacts on quality and producitivity in science. 
* Must change sad perception about CI having only a subordinate service role 
* Synthesis centers are changing the perception about the role of "analysts" in the creative process of science, viz. elevating their status.&nbsp; Is still lingering perception that there is no creativity in that role.

**Report-out discussion notes**

* Concern that adding new non-domain specialties (such as HCI) may be too much for domain scientists who are already having to work with a CI person. This could be more alienating than helpful.

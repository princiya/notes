Light beam

https://docs.google.com/document/d/1V3Oefs7EphiAk7WVFJn9FPTimnYBZ3g8SsklSnmXw44/edit?usp=sharing

https://www.jdsupra.com/legalnews/google-style-gdpr-fines-for-everyone-23609/ Bavarian DPA


Justice being conceptualised in different countries
Scope the global picture
Light beam - when did you hear?
Tools for large scale automated web tracking studies
Looking at website from different country
Get people from worldwide to try light beam 
Mobile tracking

- Should light beam work in mobile
- How will insights be calculated
- 180 native countries
- get a Whitelist, what about user’s privacy about open data (ask Mozilla)
- Input, clean and analyse 
- Input: news trackers, mobile operators
- Containers vs light beam
- Clean: not revealing privacy
- Analyse: ?
- Global tracking trends
- Who owns these trackers (which companies)
- List of skills: 
- List the process
- Context graph
Collaboration with hacktoberfest?
Collaboration with oknf and ecr

HolyJS
- Re-draw some diagrams
- Some highlights in between

Meeting with Experts

Vincent

06.02

- https://techcrunch.com/2018/11/20/how-a-small-french-privacy-ruling-could-remake-adtech-for-good/
- French DPA enforcement
- Pre GDPR ePrivacy cases
    - Accept or refuse cookies - use basic browser extensions
    - When you refuse cookie consent - websites do not give choice 
    - One of the difficulties - 
    - C(Q)ookie fix
    - TIX people - [reconsent]
- Large scale - WPM
    - Enforcement actions from governments
    - There is scope for this
- Any cases of GDPR being not followed
- European court of justice
- Post GDPR
    - There are lot of websites using consent management platforms
- Pre GDPR
- Studies
    - Belgium liven university - strong privacy group - law and tech
    - Dpa data protection authority
    - Inria - French university

Hadi

11.02

- What changes done to openWPM?
- How did you generate vis for paper? Heat maps
- datarights.me project?
- Article 29 working group
- European data protection board
- European DPA
- I don’t care about cookies
- List of css attributes - identifies cookie notices
- List is in Adblock format
- Cookie matching
- Networks science - graph theory
- Legal disagreement about implicit consent 
- Tilburg, universe of ams, universe of Leiden - e law program
- Swiss - privacy engineering strong
- Inter disciplinary work - law, economics and tech
- Max plank university

Rob

20.03

- Deutsche DPA
- Re-ordered the graph
    - Visit a / b / c —> centralise all these nodes. Interested in connected web trackers
    - Collect n/w traffic, save it as json. Go through this json through python or R.
- Working with GDPR
- Smart third party blocker
- Reporting approach to achieve transparency
- no. of third parties grow over time if you delete / do not delete cookies
- Keep collecting more third parties 
- Change layout in light beam
    - Group nodes to not scare user
- https://baycloud.com/bouncer
- https://signatu.com/products/trackerdetect
- https://blog.netograph.io/left-and-right-in-the-midterms/
- http://josepmpujol.net/
- 

Prototype Updates

08.10.2018
- Last week: More research on the data justice project with researchers from Tilburg, Netherlands (I am collaborating my project Lightbeam with these researchers to import tracking data from users from different parts of the world and understand the tracking behaviour and patterns)
- This week: Finalising the visualisations for the community based platform, Talking to folks from Mozilla to get inputs on pros and cons in making the above data set public
- Blockers: None

15.10.2018
Last week: Finalised visualisations for research on web tracking, communication with Mozilla folks and understood pros and cons of making the web tracking data public
This week: Implementing the first view for import data and plotting on the graph
Blockers: none

22.10.2018
last week: started working on the initial data import feature for Lightbeam, was a bit sick as well
this week: I will continue on that
and the best thing: I received my first payment for September from Prototype

29.10.2018
Last week*:
--------------
- import data feature (work in progress)
- deciding on the data structure format
- world map view from d3.js
- slides preparation and talk rehearsal for HolyJS (happening on nov 24 in moscow). I am speaking about Lightbeam

*This week*:
-------------
- create pull request for import data
- map points from imported data location onto the world map view
- sync with researchers from Tilburg and get feedback for the feature
- concept design for the UI

05.11.2018
Last week*
-------------
- given that I am working 50% of my time only on this project, I had few cycles to spare and did not get much things done
- but I did realise that the UI needs lot of polishing and the concept has to be thought through 
- also, we have decided to roll out the features that I build during these 6 month period to be launched as a separate browser extension in the firefox addon store, once we have positive feedback from the test users and community to integrate back into the main web extension

*This week*:
-------------
- concept design
- figure out the process to release a web extension in firefox addon store
- hopefully first data import feature to be live 🤞 
- code polishing and refactoring

12.11.2018
We decided to have the import feature as a standalone application and not integrate it in the web extension for the following reasons:

- Importing data from multiple datasets can implode the browser local storage
- Only researchers are likely to use this feature and not daily users

We decided not to host this application anywhere mainly because we do not want the datasets to be transmitted over internet and potentially misused.

*Last week*
-----------

- Import datasets into Lightbeam almost ready as a standalone application
- Quick sneak peek demo - http://g.recordit.co/ODnZsFoY7f.gif

*This week*
------------

- Get feedback from Tilburg researchers for the import dataset feature
- Decide to work on next steps based on the feedback and help them setup this application

*Blockers*
-----------

- Time is too short and I have so many things to do! 

19.11.2018

*Last week*
-----------

- Import Lightbeam datasets as a standalone web application running using Node.js and Express
- Github repository  https://github.com/princiya/lightbeam-import
- HolyJS talk rehearsal, slides completed

*This week*
------------

- Speak at HolyJS, Moscow on 24th November about Lightbeam
- Bug fixes for the import feature
- Brainstorm additional enhancements
- UI concept for the clock metaphor diagram to visualise third party trackers

*Extras*
------------

- The 6 month funding time period comprised of 2 parts - research and new enhancements
- I am very happy that the research part is almost done, now mainly waiting to gather research insights and present some mind-blowing analytics
- The remainder of this time will go into enhancing Lightbeam’s visualisation capabilities
26.11.2018

I presented Lightbeam (visualizing third party website trackers) at HolyJs, Moscow. I just came back last night and I'm getting back to finishing all the weekend chores at home;) 
So last week is basically preparing for the presentation and rehearsals. 
So, I got feedback for the Lightbeam - import web application. I need to make the Readme friendlier to non-technical people :) 

This week: 
- Read some research papers on trackers 
- Start / Build the clock metaphor diagram

03.12.2018

*Last week*
———————

- Paper prototype ready for the clock metaphor diagram
- I organised the critical tech meet up. Thanks to two people from here who came
- After the meet up I fell sick 🤒 

*This week*
———————

- Progress call with the PTF team
- UI coaching session from Simple Secure and I hope to validate my paper prototype
- Write a blog post on progress made for last 3 months

 10.12.2018

*Last week*
———————

- Progress call with Adriana
- Docker setup ready for the import feature
- More visualisation inspirations from IIB (information is beautiful)
- Blog post draft on progress made so far

*This week*
———————

- Setup a call with Tilburg researchers and help them setup the Docker setup
- Publish blog post
- More visualisation inspirations from IIB

17.12.2018

*Last week*
———————

- Blog post draft ready, now in review. It will be published mid January 2019
- Learn and read, read, read… about online trackers, research papers
- Follow up with community on Github with issues
- Performance enhancements to the force layout visualisation via web workers
- Optimise the data capture and storage phase
- Remove node duplicates

*This week*
———————

- Revisit the clock visualisation and make some improvements
- Improve performance of the existing visualisation

Interconnections between different countries
Detect patterns and trends
Third parties - location, legal entities / owning org

07.01.2019

*Last weeks*
———————

- UI/UX coaching from simply secure
- Implementing new designs
- Implementing new visualisations
- Discovered personally identifiable information (PII) points for each first-party

*This week*
———————

- Validating PII points
- Implementing new designs and visualisations (work in progress)

14.01.2019

- I am on a vacation in India 🌞
- I am working on presenting all the work done over last few months for the demo day

21.01.2019

- Ethics committee approval through from ERC (European Research Council) to officially start running web tracking experiments
- Web tracking test data collected from Austria, Slovenia and Turkey
- Analysing this test data and preparing story telling, building reports for the demo day
- While collecting test data we came across few problems about Lightbeam not being able to collect right trackers when similar add-ons like AdBlock etc. are installed
    - This week: Mainly focusing on how to best tackle this problem

28.01.2019

Last week:

- Analysing test data (part 2) from Austria, Slovenia and Turkey
- Reading lots and lots of research papers
- Trying to come up with a story line to present for the demo day

This week:

- Certificate online course starts - Privacy and Security in Online Social Media
- Story line for demo day
- Docker setup refinement

Blockers:

- Too many ideas for the story presentation!
- I am now looking for resources / articles to understand about the consequences when GDPR terms are not met; example - 
    - what measures are taken to gatekeep websites showing the cookie consent popup but do not adhere to it?
    - are there tools or any work in progress to address the above?
- I contacted few people whom I knew, but nobody wrote back to me. If you have any inputs, please point me to the right direction

04.02.2019

Last week: 
- Research on GDPR - learning the basics, reaching out to university profs and alumni 

This week: 
- Follow up calls on GDPR 
- Story telling for the demo day

11.02.2019

Last week:

- 2 Successful calls with French, Dutch DPA (Data Protection Authority)
- Lot of feedback and new ideas on advancing Lightbeam in the next direction through these calls
- Reading more research papers

This week:

- More research work

18.02.2019

Last week and this week vacation!


Light beam workshop in may - 16,17

Books:

- Chaos Monkeys - when ad machine was introduced in Facebook

Viz map:
https://maps.blueshift.io/public/589bad3a90208c2ee8894214
 



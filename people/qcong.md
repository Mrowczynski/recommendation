# QuynhDao Cong

## Summary

I have had the great pleasure of working with QuynhDao (QD) for 10+ years at eBay Inc.  During this time, it's been a combination of peer, managerial and mentoring.  Her in-depth knowledge of the SCM (Software Configuration / Change Management Process) has grown since CVS and she's forgotten more than most will have evern encountered in the subject matter space.  We aren't simply talking minor projects, but the soup-to-nuts full-blown integration and migration, including support of top notch engineers and their problems.

Her hands on experience with GitHub (Firewall and Enterprise) spans 10+ years of Enterprise level expertise in the support of 2500-10000 software developers, combined with multiple mergers, and divestitures of companies.  She knows software development life cycle, patterns and methods of development and deployment on a massive scale from her time at eBay where the version control and package registry systems are critical towards keeping the lights on, and packages flowing to production.

### Short

At a high level, these are the areas where she has had much practical experience.  

Solutions development, implementation details, and execution in :  

* Version Control : ClearCase, UCM, Git (GitWeb, Gitolite) and most recently GitHub Enterprise (Firewall since 2011 ... 2024 being the most recent Google cloud deployment)
* Package management : In-house tool (Cronus) migrated to 3rd party (Nexus) and adminstrative support (JFrog Artifactory)
* Enterprise solutions : Google Cloud
* Documentation and Issue Tracking : Confluence and Jira
* SOX, Infrasturcture Security and reliability : The typical account management, license & cost recovery, email and pager alerts for notifications, scripts/webhooks (aka triggers), restore-from-backup, region-exit, major and minor upgrades, etc.
* Security and integrations : sorry, not too many details here I can cover :)

Of course, accountability and the need to remain flexible.

Ultimately, when there was a system down, and management needed someone to step in and stem the tide of escalations when things were broken at 4A, work with the vendor to get things back online, and help document what we did, and could do better - there was no better person to have in your corner.  

### Continued

Over the years, we have seen QD grow into various roles.  Iniitally it was as a support engineer helping to deploy a new product, suppor the engineers using it, and acting as an interface between leadership and the vendor in terms of requirements.  We could also count on her to provide support on a quarterly/annual basis for things such as the critical and audit tasks such as the restore-from-backup, account management (and offboarding), plus the major upgrades.  When there were the inevitable disasters due to things like HVAC, weather or PG&E outages, she was there to help pick up the pieces.  

After 20 years at eBay, there may be a question of "what is she qualified for?" and "what role best suits her?"

Obviously, performing typical support is there.  You can train a recent-college-grad to do it, but it comes at a cost of also explaining to them why things need to be done a certain way, and also the understanding that you have to explain to them WHY things need to be done.  No such worries here.

* Support Engineer : Given a typical product, QD can leverge her yeras of experiencine in an enterprise setting to bring rigor and adherance to some of the industries best practices
* Application Administration : Will be able to pick up the administrative task for most if not all products out there.  Because of her hands-on and past-experiences, she would be able to identify, communicate and help plan major milestones (with prioritization given) for the mission-critcal and business needs
* Admin++ : This is the additional value add.  You want to help keep your costs down for licensing?  Want to figure out what to alert on when a system not only fails, but to identify beforehnd?  Maybe you need to have documentation followed and there are people just aren't good at filling in the blanks of a template ... She's done this.  Like I said, she's done and forgotten more than most people have encountered because of her stint at eBay supporting thousands-upon-thousands of dedicated and die-hard engineers


### GLHF

**My fervent and earnest hope is that she would be taking a nice long vacation after putting in all the hours in at a career.  She leaves well-respected, and well-loved.** 

But if that's not the case, hopefully this helps YOU to understand who you're getting to work with in the future.

* A small company (10-100 engineers) then you're going to want to simply help keep the lights on.  Get those new hires ramped up, and ensure that nothing breaks when you have your typical maintenance duties.  If things do break (fix-forward) then you want it fixed quickly.
* Medium company (100-500 software devs) may want to focus more on reproducibility, accountability and process.  She has forgotten about branch topology (ClearCase ... nvieflow) but it is in there.  You will need her to keep the systems alive as you ramp up your production and CI/CD environemnt.  Then when we compute ingress/egress costs, she'll help you mitigate if you can explain what you're trying to do and where your traffic is coming from
* Large company (500-2500 devs) are going to be about RTB (backups, restores, testing on staging, upgrades for features, customizations of workflows including triggers / pre-recieve-hooks) and of course data reporting.  Pick her brain on what she has done in the past, and what she can recommend YOUR company can get to.
* Extra large (2500+) is where we are at now and where she is coming from.  Roles?  TBD but let's say that the GitHub side is taken care of (actions, enterprise runners, SOX requirements) and you're going to need to start looking at supply-chain-attacks, package-name-squatting, SAST/DAST, CI/CD or GHAS level scanning, etc.  
  
##### Background and small-print

<sub><sup>In 2002/20023 I joined eBay Inc. and was a member of the SCM team.  During this time we had completed a migration from CVS to Rational ClearCase as the version control product for the company.  On the team we had people like Derek Lau, Haiping Han, Reza, Mike Morley (who moved to Nevada to open a bookstore in Carson), Joseph Escarcega (20+ years at eBay today), Dragan Milanovich as Director, and Rob Peterson (who moved on to Apple and other great things) as our manager.  

<sub><sup>If you know ClearCase, you will understand the complexity of a migration from a CVS system to one that has dynamic & snapshot views, view config specs (ELEMENT * CHECKEDOUT, ELEMENT * /main/LATEST) and of course the MultiSite that goes with it.  eBay stuck with this system for more than 10 years before we heard about this thing called "git" and began testing and deployment.

<sub><sup>Enter the current conversation.  We, including QuynhDao, began deploying GitWeb (because you need a UI) and Gitolite (because you need RBAC/ACL) in order to get a feel for it.  During 2010-2011 we identifed a best-in-breed company and deployed GitHub Firewall on September 2011.

<sub><sup>At time, I jumped ship to PayPal ;)

<sub><sup>Years later, a eBay Inc split from PayPal (circa 2015) and I became manager of the team including QD. For many years, I would help "manage" (however softly you want to describe it, but on paper I was her manager) her.  As her manager, she was one of the least PITA people I had to deal with.  Becuase of her history and track record, she would be the person our engineers would call, our management team would call when things with south, and after we got the ball rolling on an outage, she would help coordinate with the vendor and our engineers to let them know what was going on, when the problem was complete and resolution actions if any.  

<sub><sup>After that ... no more being a manager (y'all may not know how bad it can be when you're managing a workforce in Chennai, conference calls with Europe and have to try and ramp up a team in Shanghai but the phrase "not my circus, not my monkeys" should come to mind) and I would just be another person on the team ("architect" or something ... responsible for systems but not people, with systems being super reliable by comparison).  So be nice to the managers you have, they often wear the various PM hats (People Manager, Project Manager and Product Manager ... simultaneously)

<sub><sup>As a subject-matter-expert, it annoyed me to no end when the first thing an engineer did when encountering a problem was to reach out to the vendor - indicated a lack of foresight in many cases, research of current issues ("hey google it") and plain laziness.  Now I'm not going to criticize anyone for doing that when they're stuck ... but come on.  Anyhow, she was not like that.  She gave things a good try, worked with the team pre-COVID when everyone was in the office to find a solution, and when explained often went her own way to implement and communicate.  But when she was stuck ("Where is the SOP for this?!?") she didn't have a problem speaking up.
</sup></sub>

All typos, spelng and gramma errors are mine.

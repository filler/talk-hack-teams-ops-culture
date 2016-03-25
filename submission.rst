Session Title:
The DevOps Must be Crazy

Presenter Name:

Nick Silkey and Eric Larson


Presenter E-Mail:

??? and eric@ionrock.org

Presentation Blurb:

Use this one simple trick to get Developers and Ops, working together
in harmony!

Presentation Description *
This is the full, detailed description of the session that the
evaluators will be using to decide whether to include the session. Put
as much information in as you can. Prototypes / Outlines of the
proposed session are helpful.


This talk is the story of a developer and operations engineer. They
transformed the culture of the team through empathy and open ears to
distribute the operational challenges successfully accross everyone on
the team. Here's how they did it!

Outline
=======

We love our team
----------------

We put our team first and concern ourselves with making everyone on
the team better. This empathy inspired tactics to change the
culture, improve the velocity on projects, and handle difficult
challenges without breaking a sweat.


ChatOps
-------

We adopted an environment of using chat to create a positive remote
experience.

 - Using Slack: Easy integrations with powerful software make big wins
   low hanging fruit.

 - Hubot: Powerful and simple to get traction with. We didn't need to
   write a bunch of extra code to make this worthwhile, so the team
   saw the benefit and could make informed decisions about investment
   over time. Devs can focus on getting real work done rather than
   poking bots, yet they still have a platform to enable more indepth
   integrations when necessary.

 - Webhooks: Builds, pull requests, and everything else gets sent to
   chat. It is a way for everyone on the team to keep an eye on what
   everyone is doing throughout the day. This sets context for
   conversations, reference points to clarify confusion and supports
   asynchronous attention spans.


Share All the Things!
---------------------

 - Monitoring: Everyone on the team is on the hook for support, pager
   duty, new relic, and anything else that comes along. Devs feel the
   impact of bad code!

 - Incident Management: IM is happens in chat and an etherpad to
   ensure everyone can follow along. Best practices become the norm
   and folks that know nothing of IM (hi devs!) start to recognize
   the process and how to support it in software.

 - Pluggable Monitoring: ???


Communicate Through Code
------------------------

 - Code Review Everything: Everything goes in source control. We use
   github with pull requests for **EVERYTHING**! You get history,
   visibility and commentary along side easy integrations and a huge
   community of supporting services and tools. This is where you start!

 - Jenkins Job Builder: JJB makes administering jenkins jobs easy
   through code. Ops see devs managing a codebase and can learn. Devs
   see ops mastering software and learn.

 - Cookbooks / Playbooks: We use Ansible and Chef. Everyone works on
   the code! Push early and push often using `[wip]` branches to
   communicate you don't know what you're doing. Ask questions in the
   process for your own edification and everyone level ups, smashing
   misunderstood concepts. TIL is a way of life!

 - Docs: Keep docs with the code. When you try something, write about
   it. When you finish, edit the docs. Use the docs on your machine
   (git grep ftw) or from github (rst formatting for free). We use
   sphinx for this and it is a simple, easy solution.

 - Make for discoverability: We use make as entry point into a single
   repo that starts everyone off for operations and our
   environments. You can `make docs` to build the docs and open a
   browser on you machine.  You `make bootstrap` to get set up and
   `make deploy` to push code. We `make help` to understand how to use
   our Makefile. Users don't have to use make exclusively. It's a
   starting point everyone is comfortable yet. Take the team from 0-60
   using a single command.

 - Docker / Vagrant / Cloud: Use automated virtual environment to test
   reliably. Test kitchen in chef, docker with jenkins and jjb, and
   Rackspace public cloud have been essential in verifying our work
   reliably.


EmpathyOps and a Culture of Trust
---------------------------------

 - Everyone Levels Up: When you learn, you share and teach, all the
   time.

 - Everyone Deploys: Automate everything you can and make it public so
   everyone can do it. Deployment doesn't just mean pushing code! It
   includes running tests, building packages, running maintenance
   scripts, merging code, etc. Even your manager can do it!

 - Make the world a safe place: Expose everything b/c you trust your
   team. Take care to make your work safe and easy in order to make
   your team members succeed.


How do I do this?
-----------------

 - Recruit: Find champions, make friends and work together. If you
   build it with someone, others will follow.

 - Overcommunicate: Advertise what you're doing. If you only get 80%
   of something done, someone else might pick it up. Write docs for
   other people.

 - Use Available Tools: Try to put tools together rather than develop
   them. Prove the value for the cheap, sway the team, then spending
   resources becomes natural and focused.


Thanks!


Existing Presentation?
If you are reusing an existing presentation, you can provide a link to
a prior delivery example (e.g. slideshare), if you would like.

https://speakerdeck.com/filler/the-ops-must-be-crazy-hack-your-teams-ops-culture-with-one-weird


Veteran Presenter Video?
Is there a video somewhere of you presenting? Please feel free to
include a link here, if you would like.


Presenter Bio *
We'd like to know a little more about you! Lead off with a 2-sentence
bio you'd want us to put on our site and other communication. Please
share other conference presentations you've done if any; please add
any links to videos of you presenting or to decks you've presented. We
don't only take veteran presenters, it's OK if you don't have any
priors - in that case we'd appreciate you maybe recording a couple
minutes of you talking on your topic and drop us a link or
something. Also, feel free and explain why you want to present at
DevOpsDays!


Nick Silkey is a systems engineer who has worked on multiple products
within Rackspace Cloud. Prior roles have included ops engineering
roles on Cloud Identity and Cloud Feeds. Most recently he joined the
Cloud DNS product team, where Nick works on driving design and
implementation of release engineering for the control plane for the
Cloud DNS API.

Eric Larson is a software developer at Rackspace and Core committer on
the OpenStack Designate (DNSaaS) project. He is also the author of
CacheControl, the recommended HTTP caching library for the popular
requests library.

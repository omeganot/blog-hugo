+++
date = "2013-09-30T12:00:00-06:00"
tags = ["Scrum", "regulation", "compliance", "audit", "agile"]
categories = ["Process"]
title = "Regulation Compliance with Scrum"
+++

It's always a joy to see individuals whose work involves lots of regulation come through Scrum training with questions around process, timing, documentation and so on.  These questions highlight very well that Scrum is not the waterfall process they're accustomed to.  It makes perfect sense; the language for regulation was written when waterfall was the dominant process.  The great thing is, Scrum and compliance already work together better than you may think.

## Using empiricism to our advantage

Regulation and compliance are complex issues.  There may be contradictory, vague, or incomplete regulations causing confusion as to what needs to be done.  Adding to that, regulations often change over time so understanding the regulation and how to comply with it is continually in flux.  Scrum is a framework designed for doing complex work, so the two naturally fit together.

The empirical nature of Scrum gives companies inspection and adaptation points necessary to assess their progress towards compliance with a regulation.  This applies to regulations implemented in software as well as regulations that apply to how software is developed.  The company can frequently inspect the product and its process to assess compliance.  Testing suites, especially automated ones, help to ensure the software never falls out of compliance with the regulation.  Test driven development can also help ensure compliance from the beginning with built in verification.

## What about auditing?

Modern ALM tools offer extensive history functions for both source code and work requests which can be queried for auditing purposes.  For example, the exact point in time which the software met a specific regulation as proven through a testing suite can be identified.  Work items on the backlog can be linked to high level regulations and traced down to their implementation.

In terms of financial auditing, the traceability offered by ALM tools can be immensely helpful when understanding the capitalization and expenditures of a software development project.  Turns out, agile development practices [are incredibly helpful][1] with financial regulations.  From a capitalization and expenditure standpoint, Scrum can help companies reduce tax liability and free up money for the staff they need to realize their goals.

The US Financial Accounting Standards Board (FASB) guidelines may have been written with waterfall processes in mind, but they give us some guidance that quickly apply to agile software development.  In general, any "Preliminary Project Phase" work, that is, anything before you begin sprinting and actually doing work, is an operational expense.  Work done while sprinting can be capitalized, and maintenance work is expensed.  Since teams may very well work on bugs for a released product in the same sprint that they are creating or enhancing features, some of the cost may need to be expensed.  In this case, the relative point estimates teams assigned to the work can be used to determine the proportion which can be capitalized and which can be expensed.

While software may be released each sprint, it likely isn't being depreciated each sprint.  A quarterly roll up may suffice.  Work with your financial department to come up with a clear set of rules your company will follow for its reporting practices.  From [Dan Greening's article][1]:

> "Auditors recognize that FASB and IASB guidance cannot be routinely applied to new situations. What tax authorities and auditors look for is conformance to law and its spirit, consistent application, and full transparency. We can give them all that, but because agile practice is new, we must understand the law and its motivations, document our capitalization policies and practices, track project work consistently, and be perfectly transparent. This aligns well with agile principles."

Pat Reed summed this up nicely along with Laszlo Szalvay in [a session][2] at Agile 2013 encouraging that we "Re-evaluate the problem that was trying to be solved when the rules were first written."  The rules don't have to keep your company in the waterfall ages forever.  Use the transparency called for by Scrum to your advantage and develop a set of guidelines that will help, not hinder, your company's ability to deliver value while meeting regulations.


[1]: http://www.infoq.com/articles/agile-capitalization
[2]: http://www.slideshare.net/laszlos/2013-scrum-grcfinal728

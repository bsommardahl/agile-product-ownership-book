# Technical debt

When you go to the cash register to pay for your goods, you have to offer something of value before they will let you leave the store. If you pay with cash, then the deal is sealed. Now the store has your $100, and you have their goods. I prefer not to carry much cash, so I will almost always pay with my credit card. After all, I might need that cash at my next stop and my credit card gives me points that I can use on a flight next month. I get certain benefits from using my credit card. For example, if my paycheck hasn't been deposited yet, I can still buy things. Also, I don't have to physically go to the bank to take out some cash. And there's safety... I live in a dangerous part of the world, so it's a bad idea to carry around a lot of moolah. So, when I pay with plastic, I get to reap the benefits of a small loan.

If I pay off my credit cards by the end of the month, the benefits I get from those little loans end up costing me nothing. What a deal! But, if I become undisciplined and I let the month go by without paying, then my small loans turn into "debt". Credit cards have notoriously high interest rates and costly penalties for debt. Get on bad terms with your credit cards, and you won't even be able to to remember the benefits you might have had.

When building software, development teams are constantly taking loans and, potentially, incurring debt. Of course, I'm not talking about financial debt, but about a concept known as "technical debt". The term "technical debt" was first coined in 1992 by Ward Cunningham as he was trying to describe the challenges in maintaining a large, long-lived software project. His metaphor of technical debt effectively explains how short-term loans can empower developers to deliver features faster, and how long-term debt can suffocate a development team. 

You can think of technical debt much like any other type of debt. Many businesses depend on debt to grow or survive. Over time, small loans turn into much larger debt. If loans are paid back quickly, they don't accumulate interest. Sometimes payback is delayed for one reason of another. The longer a debt is allowed to exist, the more interest it accumulates and the more it costs. Left unchecked, debts and their cost can grow out of control and may lead to the debtor's discomfort or even downfall. 

### Short-term Technical Loans 

A technical loan is any beneficial software development activity that is postponed. A natural occurrence in any software development project, small short-term technical loans can be taken in the form of shortcuts, temporarily messy code, or some experimentation. Developers need to think on their toes and take advantage of their creativity while coding. When developers allow themselves to explore and experiment, they can often arrive at a working solution faster than if they had been held to a high engineering standard throughout the process. Even well-known software engineering techniques like test-driven development encourage short-lived technical loans as part of the "red-green-refactor" cycle (see TDD). The red and green stages of that cycle are for experimentation and creating something that "works", taking a small technical loan in the process. The refactor stage is for paying off the technical loan by cleaning up the code. Technical loans offer development teams great benefits, much like my credit cards. Take small, manageable loans, reap the benefits, and pay them off before they are able to incur interest and penalties.

### Technical Debt

When technical loans go unpaid, they convert into debt and incur interest and penalties. Technical debt is created in the same way a development team creates technical loans: shortcuts, experimentation, and "temporarily" messy code. However, when that code is left behind and the team allows that code to stay in the code base, it becomes a first-class citizen of the software. The cost started out as a useful tool to help developers innovate. But, once it gets left behind, it converts into something that actually stands in the way of future innovation. Future features are inevitably built on top of that technical debt which further deepens its grasp on the software. Technical debt accrues interest and penalties, which get paid through velocity reduction, missed deadlines, inability to deliver, endless bug lists, overhauls, re-writes and other consequences. 

Technical debt includes but is not limited to... 

* complex code
* untested code
* brittle tests
* re-invented wheels
* out-of-date code comments
* out-of-date documentation
* hardcoded values
* nested structures
* large conditional structures
* temporary hacks
* unused code
* poorly-named code structures
* unused database tables and columns
* or anything in design or code that must or should be done in a different way or could stand in the way of future modification or innovation. 

### Technical Debt as a Feature

Have you ever used a credit card for a large purchase or expense knowing that you would not pay it off by the end of the month? I wouldn't say it is wise, but it might be the only option you have, especially if you have to pay for an emergency surgery or repair to your house. The benefit is that you can cover the emergency expense. The consequence is that you will end up paying much more down the road. For some situations, it makes sense to intentionally incur technical debt for the good of the company or the product. 

There are plenty of examples of software projects that have tight deadlines and need to meet certain goals before a trade show or a important stakeholder demo. Still other software projects are focused on beating the competition to market. In these examples, the feature set is not really negotiable. Scope is set based on market research and usability studies. That date I mentioned is immovable and everything absolutely must come off without a hitch for that day. Without speeding up efforts and incurring technical debt, the product or company might not survive. 

The canonical example is Twitter. The software that ran Twitter was thrown together as fast as possible in order to get to market at the right time. When Twitter made it to users desktops around the world it was an instant success. Since it's first release, Twitter has become a marker in our culture, not just in the United States where Twitter started, but also around the world. But none of the world's new microbloggers realized that Twitter was sitting on top of a back-end hastily built out of sticks and chewing gum. Twitter worked, and that's all that mattered. The benefits of technical debt allowed the makers of Twitter to get something valuable to market at break-neck speeds. Technical debt is probably why Twitter is now a household name. Without the intentional use of technical debt, Twitter might not exist today.

### Unwelcome Technical Debt

Technical debt is only acceptable when the product depends on it to succeed or survive. Benefits like speed and developer innovation are huge. But constant, unbridled speed is not always the best way to reach your goal. Let's be honest. Most deadlines are imaginary or not nearly as important as we make them out to be. Are we really racing the clock, or do we just want to apply some healthy pressure? If your software is so important to your business, and you have time to build it with care, then "care" that's the standard you should accept from your development team. Technical loans are expected and should be tolerated so long as they are paid off quickly. When your software doesn't depend on speed to market to succeed or survive, then technical debt should not be a part of your team's expectations or standards.

### Consequences of Technical Debt

As mentioned, the benefits of short-lived technical loans are increased innovation and speed. But, once the loans begin to accrue interest, they convert to technical debt. The consequences of technical debt are decreased speed, innovation, stakeholder confidence, and team engagment. 

#### Speed

Technical debt usually results in slower development speeds. Many times we compare technical debt to "mud". As you can imagine, walking in mud is much slower than walking on a firm surface. Your feet get stuck, sometimes you lose a shoe, you're concerned about getting your pants dirty, and you end up having to clean off later on. On the other hand, on a solid surface, you're able to walk, run, skip, flip or jump at top speeds. You can go as fast as you want. Development speed at the beginning of a project is very much like running on a solid surface. It feels great. Everything seems smooth and easy. In contrast, working in a project with heavy technical debt is like trying to run in a muddy swamp. Everything takes way too long. What used to take an hour now takes days or weeks. 

#### Innovation

Writing software is a creative process. Consider an artist painting a tapestry. The painter has paint brushes, various colors and a clean canvas with which she can realize the image in her mind. Artists innovate as they create. They depend on quick feedback loops and responsiveness of their tools and their medium in order to maintain the flow of innovation. Any break down in the process threatens the completion of the tapestry. Getting slowed down by mistakes (technical debt) that have accumulated over time is something that can rob a project of its innovative potential. Software that can no longer flex, bend and respond to innovation quickly is software that is marked for death. 

#### Stakeholder Confidence

Software projects exist because stakeholders want them to exist. As long as they have confidence in the team and development process, the development team has breathing room and freedom which is beneficial to productivity. When technical debt slows down improvements, fixes, and innovation, stakeholders inevitably (and rightfully) lose confidence in the development team. Micromanagement ensues and freedom is replaced with slavery. 

#### Team Engagement

An engaged development team one understands and believes in the vision of the product they are building. Engagement drives better questions which lead to greater ownership and superior decisions. An engaged team is more productive and produces a higher-quality product. As technical debt builds, the software project becomes less and less enjoyable to work with. Developers find friction at every corner. Team leads become frustrated with missed deadlines. Pressure increases and, as a result, the team becomes less engaged. Eventually, teams that deal with technical debt on a daily basis experience high turn-over, which affects engagement even more because of the need for constant training and internal product evangelism. 

### Recognizing Technical Debt

Unfortunately, technical debt is hard to spot. In fact, technical debt it mostly invisible to users. In many cases, for non-developers, technical debt is like the wind. You can see the effects of the wind, but you can't see the actual wind. And worse, many times we can't see even the effects of technical debt until the project is already paying the consequences of it.

You might have technical debt if...

* Your once-performant development team is now releasing features and fixes at a snail's pace.
* Your bug backlog has been your priority for weeks.
* Your developers are pushing for overhauls and re-writes.
* You are hiring new team members to replace the ones who you can't seem to keep.

Though it is nearly impossible to detect technical debt from a user's or stakeholder's perspective, we can certainly lift the hood and see what's going on from a more technical vantage point. There's a lot that the code can say about itself as to the level of technical debt it carries. By running your codebase through tools like static analyzers, compilers, linters, and more, you can get a window into a wealth of information about the health of the stuff under the hood. Of course, the merits of each calculated metric can be argued, so it's best to view them with a grain of salt. Here are a few potential metrics that could help reveal some warning signs:

* Lack of Unit Test coverage
* High cyclomatic complexity
* High Halstead complexity
* High number of lines (compared to similar projects)
* High coupling
* Low cohesion
* High occurrance of duplicate code
* Compiler/linter warnings
* Style & consistency rule warnings

All of these metrics are explained in more detail in later chapters. 

### Who Decides?

As destructive and costly as technical debt can be, wouldn't you think that the decision to incur it falls on the business or product owner? It's true, at times the costs of technical debt can be justified because it allows the team to get to market faster. This results in a business decision, premeditated or inferred, to lay quality aside and push the team to race to the finish line. However, such demands for extreme speed are not the norm. And, if you ask most product owners if they would rather high or low quality, they would choose high quality. So, it seems like it should be a simple business decision, doesn't it? Sadly, most technical debt it incurred by accident. It starts as a small loan in the form of a shortcut, but is left behind and forgotten. Call it lack of skill, lack of experience, or lack of engagement, but technical debt is almost always unintentional. But don't go blaming the programmers. The decision to tolerate technical debt was made before the project began by a lack of communication between the product owner and the team about expectations of quality.

### Technical Debt is Avoidable

It's probably impossible to avoid all technical debt, especially considering larger systems. Software projects that dissolve into muddy swamps of technical debt are far too common, but should not be lifted up as the standard. For systems that include quality as a feature, there's no reason why technical debt should go unchecked and be allowed to grow out-of-control. Constant awareness of technical debt and a team-wide commitment to fighting it will yield a system that is flexible and agile for years to come. 

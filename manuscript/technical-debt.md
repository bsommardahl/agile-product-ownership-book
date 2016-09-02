# Technical debt

When you go to the cash register to pay for your goods, you have to offer something of value before they will let you leave the store. If you pay with cash, then the deal is sealed. Now the store has your $100, and you have their goods. I prefer not to carry much cash, so I will almost always pay with my credit card. After all, I might need that cash at my next stop and my credit card gives me points that I can use on a flight next month. I get certain benefits from using my credit card. For example, if my paycheck hasn't been deposited yet, I can still buy things. Also, I don't have to physically go to the bank to take out some cash. And there's safety... I live in a dangerous part of the world, so it's a bad idea to carry around a lot of moolah. So, when I pay with plastic, I get to reap the benefits of a small loan.

If I pay off my credit cards by the end of the month, the benefits I get from those little loans end up costing me nothing. What a deal! But, if I become undisciplined and I let the month go by without paying, then my small loans turn into "debt". Credit cards have notoriously high interest rates and costly penalties for debt. Get on bad terms with your credit cards, and you won't even be able to to remember the benefits you might have had.

When building software, development teams are constantly taking loans and, potentially, incurring debt. Of course, I'm not talking about financial debt, but about a concept known as "technical debt". The term "technical debt" was first coined in 1992 by Ward Cunningham as he was trying to describe the challenges in maintaining a large, long-lived software project. His metaphor of technical debt effectively explains how short-term loans can empower developers to deliver features faster, and how long-term debt can suffocate a development team. 

You can think of technical debt much like any other type of debt. Many businesses depend on debt to grow or survive. Over time, small loans turn into much larger debt. If loans are paid back quickly, they don't accumulate interest. Sometimes payback is delayed for one reason of another. The longer a debt is allowed to exist, the more interest it accumulates and the more it costs. Left unchecked, debts and their cost can grow out of control and may lead to the debtor's discomfort or even downfall. 

Benefits of Technical Debt

[need paragraph here]

Short-term Technical Loans 

A technical loan is any beneficial software development activity that is postponed. A natural occurrence in any software development project, small short-term technical loans can be taken in the form of shortcuts, temporarily messy code, or some experimentation. Developers need to think on their toes and take advantage of their creativity while coding. When developers allow themselves to explore and experiment, they can often arrive at a working solution faster than if they had been held to a high engineering standard throughout the process. Even well-known software engineering techniques like test-driven development encourage short-lived technical loans as part of the "red-green-refactor" cycle (see TDD). The red and green stages of that cycle are for experimentation and creating something that "works", taking a small technical loan in the process. The refactor stage is for paying off the technical loan by cleaning up the code. Technical loans offer development teams great benefits, much like my credit cards. Take small, manageable loans, reap the benefits, and pay them off before they are able to incur interest and penalties.

Technical Debt

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

[don't know] ****************
Technical debt comes from a few sources: Technical that can come from incomplete requirements. Or simply requirements that weren't completely described to the team and the team so I'm helping to themselves in a corner. Technical that can also come from the team as they're developing the product. Software can become so complex over time that, even small decisions that need correction can build and accumulate into large scale technical debt.

Technical debt exists in many forms. Technical that can be for documentation, unfinished pieces of code, hard-coded values, code that isn't covered by unit tests, unit tests themselves that are poorly designed and needed a lot of maintenance, bugs that have been built on top of making them an inseparable part of the software.
[don't know] ****************

## What motivates technical debt?

As destructive as technical debt can be, it's not actually introduced by malicious people. In fact, technical debt is almost always the result of a desire to ensure team or product success. Technical debt can be caused by any one of the following:

1. rush to market
2. internal team deadlines (ex: demos)
4. changes to requirements
5. inexperienced developers
6. unmotivated developers

## When is technical debt acceptable?

Have you ever used a credit card for a large purchase or expense knowing that you would not pay it off by the end of the month? I wouldn't say it is wise, but it might be the only option you have, especially if you have to pay for an emergency surgery or repair to your house. The benefit is that you can cover the emergency expense. The consequence is that you will end up paying much more down the road. For some situations, it makes sense to intentionally incur technical debt for the good of the company or the product. 

There are plenty of examples of software projects that have tight deadlines and need to meet certain goals before a trade show or a important stakeholder demo. Still other software projects are focused on beating the competition to market. In these examples, the feature set is not really negotiable. Scope is set based on market research and usability studies. That date I mentioned is immovable and everything absolutely must come off without a hitch for that day. Without speeding up efforts and incurring technical debt, the product or company might not survive. 

The canonical example is Twitter. The software that ran Twitter was thrown together as fast as possible in order to get to market at the right time. When Twitter made it to users desktops around the world it was an instant success. Since it's first release, Twitter has become a marker in our culture, not just in the United States where Twitter started, but also around the world. But none of the world's new microbloggers realized that Twitter was sitting on top of a back-end hastily built out of sticks and chewing gum. Twitter worked, and that's all that mattered. The benefits of technical debt allowed the makers of Twitter to get something valuable to market at break-neck speeds. Technical debt is probably why Twitter is now a household name. Without the intentional use of technical debt, Twitter might not exist today.

## When is technical debt NOT acceptable?

Technical debt is only acceptable when the product depends on it to succeed. 


For example,

1) time constraints are so stringent that you believe your product will not survive if the deadline is not met. 

2) 

## What are the consequences of technical debt?

If the benefits of short-term technical debt are innovation and speed, the consequences of long-term technical debt the exact opposite. Most software development teams and even individual software developers are able to leap out of the gate at full sprint and make great progress at the beginning of a software project. For projects that have managed to maintain low amounts of technical debt over months of development, Speed, Innovation, stakeholder confidence and team engagement remain high. But, teams who have not managed to fight back technical debt over the Long Haul Find themselves in an impossible situation.

### Speed

Technical debt Usually results in slower development speeds. Many times people compare technical debt too much. As you can imagine, walking in mud is much slower than walking on a firm surface. Your feet get stuck, sometimes you lose a shoe, you're concerned with getting your pants dirty, and you end up having to clean off later on. On the other hand, you're able to walk, run, skip, flip or jump on a solid surface and do all of those things at top speeds. You can go as fast as you want. Development speed of the beginning of a project is very much like walking on a solid surface. It feels great. Everything seems very easy. Working on a project with heavy technical death is very much like walking in mud. Everything seems very slow and difficult. You don't feel very good after you've done it. 

### Innovation

Writing software is a creative process. Consider an artist painting a tapestry. The painter has paint brushes, various colors and a clean canvas with which she can realize the image in her mind. Artists innovate as they create. They depend on quick feedback loops and responsiveness of their tools and their medium in order to maintain the flow of innovation. Any break down in the process threatens possible failure of the tapestry as a whole. Getting slowed down by mistakes (technical debt) that have accumulated over time is something that can rob a project of its innovative potential. Software that can no longer flex, bend and respond to innovation quickly is software that is Marked for Death. 

### Stakeholder Confidence

Software projects exist because stakeholders want them to exist. As long as they have confidence in the team and development process, the development team has breathing room and freedom which is beneficial to productivity. When technical debt slows down improvements, fixes, and innovation, stakeholders inevitably (and rightfully) lose confidence in the development team. Micromanagement ensues and freedom is replaced with slavery. 
You should never underestimate the power of stakeholder confidence. 

If you or your stakeholders feel confident in the development team, the team will have the breathing room they need to 


### Team Engagement

An engaged development team one understands and believes in the vision of the product they are building. Engagement drives better questions which lead to greater ownership and buy-in. An engaged team is more productive and produces a higher quality product. As technical debt builds, the software project becomes less and less enjoyable to work with. Developers find friction at every corner. Team leads become frustrated with missed deadlines. Pressure increases and, as a result, the team becomes less engaged. 

## How can I recognize technical debt?

Unfortunately, technical debt is usually recognizable only by its affect on team velocity after the fact. A team that was once nimble and agile, will slow down drastically over time as more and more technical that is introduced. 

There are some ways that you and the team can recognize technical debt ahead of time. As long as the team agrees that lack of test coverage represents technical debt, then it is possible that you could study could cover his reports and that will show areas of your code that have technical debt. You can also run tools over your code to analyze code as it's being built. Again, your team needs to agree that lower scores means technical debt. If they can agree on that, then these analytics tools can easily be used to identify parts of your code that have higher technical debt levels. 

Another way to recognize technical debt, he is to track the amount of time you spend on fixing bugs in certain features. If a certain feature is costing you a lot of time in bug fixes, then you can assume that that Peacher has a lot of technical debt. 
## Who typically decides went to incur technical debt?

Intentional technical debt comes as a result of a conscious decision by the business I order to deliver faster. 

Any other technical debt is not technically decided. Instead, it's something that happens through a series of accidents, oversights and misunderstandings. 

On the other hand unintentional technical debt is "decided" by everyone on the team. 
Everyone shares the blame for technical debt. Many times technical debt is incurred because of a conscious decision to go as fast as possible. Other technical debt is incurred because of requirements that were not fully understood before they were implemented. It would be easy to blame software developers, but the evidence shows that most technical debt comes from the requirements, design and architecture phase, before even the  first line of code is written. 

## Should technical debt be expected and tolerated?

Technical debt that is short term in nature should be expected during software development. Technical debt that is short-lived actually enables developers to innovate and solve tough problems faster. However technical death that is allowed to exist for longer than a few hours becomes long term technical debt. Because of the potential cost of that long-term technical debt, The business needs to make a conscious decision of whether or not it can be tolerated. Outside of those parameters, long-term technical that should never be expected or tolerated. Some believe that technical debt is an inevitable truth of software development. Unfortunately, when people say technical debt is in inevitable, they are usually speaking about long-term technical debt. But the real truth is, long-term technical debt is avoidable and, therefore, should not be expected or tolerated. 

## How does technical debt affect overall software quality?

Software quality is most commonly measured by its ability to live up to expectations on delivery day. But quality should also measured by the software’s ability to accept changes after delivery day. While software may do what it was designed to do, it may be all but impossible to extend an upgrade and fix later on. This difficulty is often caused by technical death that has accumulated over time. Therefore software that is difficult to extend after delivery day should be considered low quality. 

## How does technical debt affect the bottom line?

For some projects, technical debt is actually something that can help the product succeed. However any technical debt that is allowed to live for longer than a few hours become something that will affect the project long-term. Even though a product has become successful by making it to Market early, it's likely that the product will need to be Rewritten or will involve major overhaul at some point. Technical debt always cost more then clean code. This affects total cost of ownership, and in some cases,  can cause the death of a product because of lack of ability to extend and flex with new requirements. The bottom line is, long-term technical debt always affects your bottom line. 

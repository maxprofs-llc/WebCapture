# The Three Forms of Waste – Muda, Mura, and Muri

_Captured: 2017-07-29 at 17:35 from [www.cleverpm.com](http://www.cleverpm.com/2015/05/19/the-three-forms-of-waste-muda-mura-and-muri/?ref=quuu&utm_content=buffer57ea6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)_

![The Three Forms of Waste – Muda, Mura, and Muri](http://www.cleverpm.com/wp-content/uploads/2015/05/clocks.png)

With Agile development and Lean practices so popular nowadays, sometimes the history behind these practices and philosophies is overlooked or skipped over entirely. Unfortunately, when people miss the underpinnings upon which these concepts are based, they also tend to distort and remake those principles into something that only barely resembles the original concepts behind them.

Most of what we consider to be modern "Agile" and "Lean" approaches to product design, development, and implementation all stem from a variety of manufacturing principles that coalesced into the [Toyota Production System](https://en.wikipedia.org/wiki/Toyota_Production_System) in the late 1940s. This process was a vast departure from the Western approach to production lines -- the interchangeable parts an always-moving production line, in which people were just another cog in the wheel. Rather, the TPS system focused on several principles designed to implement systemic processes to allow _people_ to provide feedback into the work being done and how it might be improved. The development of these principles, and their application in the "Toyota" way slowly built between the 40s into the 70s, where it became more broadly adopted under the guise of "just-in-time manufacturing."

Many books have been written on the TPS process (with all apologies to _Office Space _fans), and I would encourage people interested in the history to do some research -- but for this article I wanted to focus on what the TPS system views as "waste" and how each is specifically defined, because when we talk about Agile and Lean trying to eliminate "waste", we probably really mean one of these three things:

  * _Muda_ = "Waste" or failures of people or processes to efficiently deliver product.
  * _Mura_ = "Unevenness", or failures related to unpredictable or inconsistent outputs.
  * _Muri =_ "Overburden", or failures of standardization to create efficient process.

## Muda -- Waste

> futility; uselessness; idleness; superfluity; waste; wastefulness

_Muda_ is the term adopted by the TPS system that generally refers to waste introduced by people or processes that result in inefficient delivery of product -- where efficiency is measured by the consumption of resources. _Muda_ assumes that there is some base level of resources necessary to deliver some product, and when we exceed that base level, we are introducing waste into the process. Analyzing a process for _muda_ requires that you segregate out work that is actually being done into two buckets: value-adding work ("actual work") and waste. But you're not done there -- once you have identified "waste," you then have to bucket that work into work that needs to be done but does not add value ("auxiliary work") and work that not only does not need to be done but that also adds no value ("true waste").

The distinction between these three types of work is **essential** to understanding how the TPS system works, and how we as Agile and Lean practitioners should view our current world -- it's **not** sufficient to just shove things into two buckets of "work" and "waste" because it **ignores** the unrelated necessities that influence what we do and how we do it. This is, in my opinion, one of the root causes of the #noestimates movement -- they consider estimates to be "waste" without any additional analysis. And, to be fair, they're right -- but more often than not, estimates fall into the "auxiliary work" category (when they're done right, and for the right reasons) rather than the "true waste" category.

The reason it's important to segregate "auxiliary work" from "true waste" is that you can usually immediately put plans in place to eliminate "true waste" -- someone is highly unlikely to be concerned about getting rid of some amount of work that's neither adding value, nor required by some internal or external dependency. However, when you start to look at "auxiliary work," you have to deal with those dependencies -- and that is where the **real work** of Agile and Lean principles comes into play. The TPS system, and its descendants, require that we **challenge** "auxiliary work" and that we **minimize** its impact on the outcome, but not necessarily **eliminate** it entirely. Thus, with something like estimates which have no real, discernible benefit to the development teams (arguably), but which provide the business side of the house with some basis on which to plan and hold development teams accountable, we shouldn't necessarily seek to **eliminate** it but rather to **reduce** its impact so that the teams can do their work with as minimum an amount of _muda_ as possible.

> The goal is not to _eliminate_ all auxiliary work, but rather to _minimize_ its impact on the process resulting in product.

## Mura -- Unevenness

> unevenness; irregularity; lack of uniformity; inequality

So many people focus on _muda_ when talking about TPS and other lean manufacturing systems -- not to mention Agile and Lean development -- that the other two forms of waste are often completely overlooked. But, they're **just** as important to keep in mind when you're working on delivering a product as "actual waste"! One of these is _mura_, or unevenness, is a key component of "just-in-time" production, a system which relies on predictability and uniformity. The goal of "just-in-time" is to reduce the overhead necessary to maintain inventory of parts, supplies, or anything related to the production line -- as something is needed, it is requested; when it is requested, it is supplied; when it is supplied, it is used. It's a cycle that relies on regularity in the tools being used as well as the outcome being produced. _Mura_ rears its ugly head in software development in a variety of ways, but the most obvious are in testing and in the user story/requirements process.

Unevenness in output can be prevented most clearly by testing the product while it's under development. Whether this uses manual, "black box" testers or automated testing tools is ultimately up to the team and the resources that are available to them. But there **must** be testing in order to avoid _mura_ in the product; it is no excuse whatsoever to skip testing because you're focused on delivery. In fact, doing so simply pushes off the cost of your waste into future work, or onto customers who are relying on your product to be effective, efficient, and predictable. There can be no "cowboy coding" or "testing in production" if you intend for your product to live up to the goals of lean processes.

Another place where unevenness shows up is in requirements definition and the use of user stories. Much as the "just-in-time" production line relies on predictable inputs and predictable components to achieve its goals, an active development team needs to know what they can expect from their Product Managers in terms of requirements, acceptance criteria, and how user stories will be developed throughout the development process. Having unpredictable, irregular, or randomly-dropped user stories is a primary cause of _mura_ in many companies -- similarly, writing strict requirements that are so detailed that they hem in the developers to a specific implementation that may or may not be acceptable given the tools and capabilities available to the team can also cause _mura_, as the team now needs new "parts" to build the product.

> Agile software development, like manufacturing, relies on just-in-time principles that expect regular, predictable, and reliable inputs to create a known and expected output.

## Muri -- Overburden

> unreasonableness; impossible; beyond one's power; too difficult; by force; compulsorily; excessive; immoderation

The final, and perhaps most overlooked, of the concepts of waste that the TPS production process identifies and attempts to reduce, is _muri_ -- the lack of standardization or clear expectations placed on the people who actually **build** the product. The attempt to reduce _muri_ in a TPS-based system, is evidenced by the standardization of processes into clearly defined, repeatable, and teachable components; the identification of tools and technology to make the repeated tasks easier and less burdensome on the people required to do them; and a **reasonable** expectation of the time and effort required to deliver their piece of work along the production line. All of these things -- which generally focus around having clear, reasonable, and stated expectations -- tend to have an overall positive effect on the morale of employees, and tend to decrease both other types of waste, _muda_ and _mura_. People who know what they're expected to do simply do a better job and create better, more predictable outputs; the opposite is also true, when expectations and processes are unclear, people often struggle to perform and care less about the outcome.

While it is **absolutely** true that one of the fundamental principles of Agile (and through inheritance, Lean) that we value "_Individuals and Interactions_ over _Processes and Tools_", far too many people forget that there's an "over" statement there, and neglect to recall that "**while there is value in the items on the right**, we value the items on the left more." Agile, as it has grown from the [Agile Manifesto](http://www.agilemanifesto.org), does not require that we have **no** process; rather, it wants us to **minimize** process in favor of interactions between people. This means, further, that **where **we have processes, if we wish to reduce _muri_ in our workplace, those processes must be clearly defined, teachable, and followed to the extent that they produce value -- and **alterted** if they are **not** producing value. I've worked in many companies where their biggest problem was not waste in the product or the process, not in the regularity or predictability of their inputs and outputs, but rather in the inability of their teams to follow anything resembling a predictable, reliable process. Nobody knew what their responsibilities were, so nobody had any accountability for the final product. While rarely the most** obvious** of the forms of waste, _muri_ is, in my opinion, one of the most harmful and insidious.

> Agile doesn't require that we have _no_ process; it requires that we value interactions _over _process -- but where we _do_ have process, it should be clear, defined, and teachable.

## Reducing Waste as a Product Manager

Now that we understand a little more about the types and forms of waste that the TPS system, and -- through time -- Agile and Lean practices, have attempted to identify and reduce, what can we as Product Managers do to improve the processes, inputs, and outputs of the teams we work with on a daily basis? Here are a few things:

  * Be cognizant of the "overhead" work that you're doing with your teams -- and ensure that you're not imposing any "real waste" or too much "auxiliary work" on them or yourself.
  * Work with your stakeholders to help them better understand what it is that the development teams actually do, why they do things the way that they do them, and how the stakeholders can work **with** you to improve relationships and understanding.
  * Watch for irregularities in the inputs, outputs, and processes of your teams; if you see something, say something -- ask honest and open questions to understand why something is being done the way it is…what looks like "waste" to you might actually be an improvement for other teams to model.
  * Constantly push your teams to improve themselves and their processes -- hold retrospectives whether the team wants them or not, and hold them accountable for identifying things that didn't work. There's **rarely **a sprint or iteration that goes perfectly, and there's always room for improvement.

The Clever PM has been a B2B product manager for over 10 years in a variety of industries, and is a passionate advocate for agile, effective Product Management. This blog is devoted to providing tips, tricks, and hacks to make people better, more clever Product Managers.
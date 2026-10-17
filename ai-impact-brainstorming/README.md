## AI Impact Brainstorming <!-- omit from toc -->

>> Written by human, reviewed by AI. AI also helped find citation sources.

Mini-dive into multiple AI topics.

- [What Happens When Open Source LLMs Advance?](#what-happens-when-open-source-llms-advance)
- [Does AI Equate to More Company Output?](#does-ai-equate-to-more-company-output)
  - [Suh and Oh](#suh-and-oh)
  - [Dillon and colleagues](#dillon-and-colleagues)
  - [Humlum and Vestergaard](#humlum-and-vestergaard)
- [Digital Low-Hanging Fruit](#digital-low-hanging-fruit)
- [Workflows and Work Tiers](#workflows-and-work-tiers)
- [I Love Me Some Diagrams Still](#i-love-me-some-diagrams-still)


## What Happens When Open Source LLMs Advance?

- [Stanford AI Index, 2025](https://hai.stanford.edu/news/ai-index-2025-state-of-ai-in-10-charts)

Businesses want control over AI spending. Tokens don’t translate neatly into “X tokens gets you Y amount of useful work.” Open models could help reduce dependence on providers who could increase cost-per-token in the future. Give open models some time and I’d expect them to handle much of what today requires premium frontier models.

Right now, subscriptions for things like Claude and ChatGPT are running at huge losses. These companies are betting on other profit making strategies for the long-term, though that doesn't prevent them from increasing subscription costs & capping usage on the most expensive models in the meantime. I'm not sure how successful their long-term strategies will be.

## Does AI Equate to More Company Output?

If you give someone a new cleaning tool and cleaning now takes them 5 minutes instead of 15, are they going to use that saved time to do additional cleaning? Maybe. Or maybe the task is complete, so they’re done. It really depends on the individual and their motivations. 

### [Suh and Oh](https://arxiv.org/abs/2602.12695)

There is evidence for workers capturing some of the benefit themselves. A Korean worker survey of 5,512 subjects found almost no correlation between reported time savings and output changes when using AI.

>> We show this disconnect arises because workers capture efficiency gains primarily as on-the-job leisure, rather than increasing their output. 

### [Dillon and colleagues](https://arxiv.org/abs/2504.11436)

A randomized experiment across 66 firms and 7,137 workers offers another example. Workers who used a provided AI tool spent about 2 fewer hours a week on email and worked less outside regular hours. However, researchers did not detect an increase in total work output. 

>>  Apart from these individual time savings, we do not detect shifts in the quantity or composition of workers’ tasks resulting from individual-level AI provision.

### [Humlum and Vestergaard](https://www.andershumlum.com/s/chatbots_260313.pdf)

>> What does not move is the surface—recorded hours and earnings. Using difference-indifferences, we estimate precise null effects at both the worker and workplace levels, ruling out effects larger than 2% two years after ChatGPT’s launch. These null results hold across occupations, across intensities of adoption, and even among workers who report substantial daily time savings. 
>>
>> [..] when earnings and recorded hours remain stable, workers and workplaces absorb technological change through task reallocation and other unrecorded adjustments, reducing pressure on pay or hours. If so, the absence of measurable labor market effects is not evidence that nothing is happening — but rather that transformation is occurring on margins that conventional economic statistics do not capture.

Imagine you have 100 people doing their work and give them a tool that allows them to do their work 2x faster. Why not only employ 50 people instead? That could have a drastic costing savings.

On the other hand, if it's a sort of scalable business with a certain bottleneck, maybe this means they hire 100 more people and ramp up operations. 

Though, if the options for a company are either decreased needed personnel or expansion, that seems like it would lead to stronger and more monopolies.

Regardless, handing people AI doesn’t decide how the gains get used. Incentives, coordination, and addressing next-line bottlenecks can help direct the time-savings gains.

## Digital Low-Hanging Fruit

AI speeding up the production and quality of digital products leads to saturation. You can build faster, but so can your competitors. People are going to spam the hell out of anything cheap to produce.

Amazon is a useful example. In September 2026, *The Bookseller* reported that KDP (Amazon's publishing platform) reduced its weekly user publish limits from 10 to 2 titles per format. [The Bookseller](https://www.thebookseller.com/news/amazon-reduces-weekly-kdp-uploads-from-10-to-two-per-format), [KDP rules](https://kdp.amazon.com/en_US/help/topic/G202172740). 

AI-assisted recreation of existing software adds another pressure. Projects such as [Photocraft](https://github.com/storytold/photocraft) are interesting examples where the (expensive!) Adobe product suite is attempted to be recreated, pretty much. Even if something like this got shut down, in the long run I think AI will have an immense negative impact on companies like Adobe unless they could somehow legally protect themselves.

Since the robotics field is still in its infancy, AI is (currently) not going to have as great of an impact in hardware advancements and manufacturing compared to its impact in the digital world. Hardware could be an interesting area to follow, with all the noise and focus in the digital space going on right now.

## Workflows and Work Tiers

Organizational economics studies how routine problems can be handled at lower levels while unusual ones go to specialists. I think that’s a useful analogy for routing work among scripts, cheaper models, expensive models, and humans. [Garicano](https://www.journals.uchicago.edu/doi/10.1086/317671)

It's possible companies could want a framework for certain workflows where as much work is scripted as possible and models are only used in areas absolutely necessary. Even if a model is really cheap to run, reproducability and future model swapping would encourage one to not use AI unnecessary when designing automation. Why have AI rediscover a process that could become a reliable script?

## I Love Me Some Diagrams Still

As implementation gets automated, more of the remaining human work moves toward understanding the whole system, connecting back to a previous writeup, [*Why Diagrams Are Important*](https://github.com/ashfordhill/writings/tree/main/why-diagrams-are-important). 

Though there is use of AI-generated diagrams via something like Mermaid, I think it's valuable for an overseeing engineer to trace and modify these diagrams as necessary. The brain gets lazy and I don't think there will be an incentive for getting complacent engineers to de-rustify themselves in the near-future. Working through problems that require high levels of mental energy is good for staying sharp, whether you manually code or not. 

In my current team we've used a lot of visually appealing diagramming to communicate. When a diagram isn't detailed enough or is even missing, it's definitely felt in communication with other people. 

---
title:  "Retrospectives"
subtitle: "Food for thought"
author: "Jack Reed"
avatar: "img/author.png"
image: "img/e.jpg"
date:   2018-02-27 12:12:12
---
Like it or not, there is a lot of data that get's generated throughout software development lifecycles. The metrics that an agile team chooses to use should help them shed some light on what might be happening, it can be an interesting way for a team to learn more about their systems and performance, and it forms part of an important aspect of experimentation.

#### Experimenting
As _**Jeff Sutherland**_ may have once said '_Reduced mental capacity caused by multitasking makes us erroneously think that we are crushin' it, when we are actually losing focus and productivity._'- which may well be true. However, being solely focused on one thing, a 'sprint goal' for example, can without question contribute towards the success of that sprint goal. The price that's paid for that specific, focused attention, even when there is flexibility in the implementation of functionality, it can still, at times cause blindness to everything else, as it can be too easy for us to get blinded by our desires which can end up hindering our ability to see things as they truly are.

Experimenting whilst things are going well might not seem all that necessary to most people. Imagine if our focus was solely that 'sprint goal' and nothing else matters, and that goal was being accomplished by the team at the end of each sprint- what would be the problem with that? Well, always getting what we set out to achieve could be blinding us to perhaps an even higher possible accomplishment? Also, if we're getting nothing else but what we have set out to achieve, then what have we learnt? Can growing and learning be just as important as winning (accomplishing a sprint goal)? Isn't there value in knowledge acquisition? It is during retrospectives where the results from experiments and recent performance can be analysed and discussed.

'_If you adopt only one agile practice, let it be retrospectives. Everything else will follow.'_- **Woody Zuill**

For a software company that has teams with the odd certified ScrumMaster, Product Owner or a few Developers that are familiar with Kanban, Scrum, XP, Lean-Software.. a so called 'agile' team is far less valuable than a team of actual agile thinkers- ones that have an understanding of the principles behind agile and lean, that are empowered to question everything, and have the ability to experiment without the fear of failing.

#### Who Wants To Be Measured?
The thought of being watched by someone or measured in some way, I think, it's safe to say that a certain amount fear, or at least the feeling of slight apprehension can be found in all of us. Perhaps this derives from our childhood when our parents or primary care givers first start looking over us, observing us and our behaviour and teaching us right from wrong. As children in school we are measured by our grades, job searching involves us being measured against our competition and keeping a job involves us having our performance measured and reviewed over time, at least in some way or another. Does this help explain why there is rarely anyone on an agile team that ever gets excited about the thought of them or their work being measured? Well, in this post I'll be exploring team level metrics, metrics that should be chosen by the team and analysed by the team based on what they think is relevant and useful.

Metrics can help us make better sense of what has happened or what is actually going on right now, particularly if you're looking at a metric that's a leading indicator like the work in progress (WIP). And a lot can be said about having a sense of understanding. I mean, there is nothing simple and straight forward in software development, it seems it's a complex environment with a default setting of chaos. Therefore, we have to try to make sense of things that we think are important, being stressed at work or because of work can be a serious problem. Failing to come to grips with (someone or something) could cause us to suffer from all sorts of psychological effects overtime by provoking anxiety and depression.

_'The way in which we're constructed neurophysiologically, we don't experience any positive emotion unless, we have an aim, and we can see ourselves progressing towards that aim, and it isn't obtaining the aim that makes us happy, it's pursuing it._'- **Jordan B Peterson**

#### What Are Useful Metrics?
The right choice of metrics to use depends on the team and context, so not all metrics are necessarily going to be useful- in fact, sometimes they can be dangerous. In terms of metrics at a team level, they can be used to measure anything that the team think is relevant in helping them identify improvements, as it can provide them with additional information on; their experiments, results from adjustments made in their behaviour, track their progress towards goals and can even help prepare for the future- it should really come down to what the team find out to be useful.


_'Individuals can make a difference, but it takes a team to really mess things up.'_

#### Typical Agile Metrics
It's safe to say that most of the time, when you mention the words 'Agile Metrics', people tend to think of the following:

- **Team Velocity**
- **Sprint Burndown**
- **Epic and Release Burndown**
- **Cumulative Flow**
- **Control Chart**
- **Lead Time**
- **Cycle time**
- **Work in Progress (WIP)**


The data from an agile team will generally come from multiple different locations depending on the context of the team and how they are working. For example, they may use a project tracking tool such as: '**JIRA**', '**Pivotal Tracker**', '**Rally'**, '**Asana**', or they might just be writing requirements on '**Post-it Notes**', then plastering the notes on a wall. One of the best things about agile practices, I think, is that teams can move quickly within their own context, and utilise what is useful for them. If a team find it beneficial to use **Post-it Notes** on a wall for their product backlog items or requirements, then great, let's get decorating. A team might even find that what they want to measure can't be done with any of their system tools that they're using, so they have to get creative, maybe some sort of mood board is required that they update manually to track their mood during a sprint?


Generally speaking there will be a whole list of different systems that are used by a team. Here are a few examples of systems that a team might use.
- **Project Tracking** (JIRA, Pivotal Tracker, Asana, Trello, Post-it Notes)
- **Source Control** (Github, Bitbucket, Subversion, Microsoft Team Foundation Server, Mercurial)
- **Continuous Integration** (Jenkins, Bamboo, Travis, Github, Circle CI)
- **Deployment Tools** (CodeDeploy, Capistrano, AWS CodeDeploy, Octopus Deploy, Distelli)
- **Business Intelligence/Application Monitoring** (NewRelic, LogicMonitor, Datadog, AppsDynamics, BMC Software)

#### Questions Based On Outputs:
  - How often are we getting working software to our target environment?
 - How many known bugs are there?
 - What is our current velocity?
 - Are we meeting our commitments?

Data from each of these systems, on their own can answer simple questions around specific outputs.

<img src="/img/team-system-data-collection.png" align="middle">

#### Questions Based On Outcomes:
- Are we making our process better?
- Are we delivering the right things?
- Are we making our product/service better?
- How good are our requirements?

As a whole, having all these systems and the data they produce forms the team's system data collection. Having this collection of data allows the team to group together certain data group samples, enabling them to then have conversations around some of the bigger types of questions that are based on outcomes, rather than just outputs.

<img src="/img/team-system-data-collection-questions.png" align="middle">

#### Effective Metrics
Defining effective and useful metrics can be tricky, and what metrics that might be useful for a team might not necessarily always stay useful overtime. Here are a few important aspects that are probably worth considering when it comes to choosing and defining a metric.

#### Contrast
We tend to understand things better when we can compare it to something that we already understand, this helps us form concepts in our mind based on our existing knowledge. An effective metric is one that is comparable to itself overtime, it wouldn't be a good idea for example to compare team velocity from one team with another team.

#### Simplicity
Using too many metrics will quickly over complicate things. Less can often be more when it comes to maximising metrics, the easier it is for the team to understand what behavioural changes they can do to help influence that metric the better.

#### Affordable
What are the associated costs in gathering metrics? It may be difficult to answer this exactly without measuring it, as we could be referring to '_costs_', in terms of the amount work effort spent on gathering metric data, or '_costs_', could also derive from paid software tools, like the software that is actually gathering the data for us. Therefore, as a rule of thumb- would it be sensible to say that, the possible value of improvement that can be gained from a metric shouldn't exceed the costs of collecting it.

#### Team Level
Meaning that the metrics used should be chosen by the team for team, and if additional metrics on a organisation level are required, then there should be a separation, or at least an agreement in what that is exactly. I mean, nothing wrong with showing off your metrics externally, who knows- the team and other people in the organisation might even start mingling, sharing ideas and having deeper conversations around each others metrics?! Just be cautious of any stakeholders wanting to utilise any of the team metrics without fully understanding the context behind them.

_'Managers who don't know how to measure what they want settle for wanting what they can measure.'_- **Russell L. Ackoff**

#### Actionable
An effective metric should be specific enough and not just document the current state of the existing product or service, but offer insights into understanding where the team are, so that they can have conversations around where or what to do next, I mean, why else measure things that you can't do anything about?

#### Truthful
There wouldn't be much point in relying on data output from a system, if the input data wasn't true or accurate. I've found that it can be useful for a team to discuss and agree on how exactly they intend to input data into each of their systems, and then make it part of their team working agreements. That way they can hold each other accountable for any deviation. Sometimes you can't always measure what you want (true metric), so you settle for what you can measure (proxy metric), the important thing is to understand the two. Imagine an organisation that wanted to increase their online presence and be popular across all their social media channels. One metric could be to measure how many followers they get. But it wouldn't be a true metric if a click farm was used to obtain all those followers. The take away from this is to be aware of what is it exactly that you're measuring, and the impact of what might occur as a result of choosing it as a metric.

'_Any observed statistical regularity will tend to collapse once pressure is placed upon it for control purposes._'- **Charles Goodhart**, or in other words and more simply put by **Marilyn Strathern** '_When a measure becomes a target, it ceases to be a good measure._'

#### Conclusion
I think for any agile team, it is essential to spend time in not only establishing the metrics that matter most to the team, but also to always ask questions and not to hold back when it comes to experimenting, particularly if the evaluated effort involved in running the experiment doesn't out way the potential reward. Accept that each team will vary in what metrics are beneficial for them, for example, some teams in a certain situation might just need to focus on a leading indicator metric like their WIP. By limiting their work in progress might free them up enough so that they can start looking at other areas.

As usual I've stumbled across some great material whilst writing this, so if you’re after more information on the subject of agile metrics, how to focus on value, human behaviour from a psychological perspective and chaos in general, then I’d recommend checking these out:

- Chaos: Making a New Science - by ['James Gleick'](https://www.amazon.co.uk/Chaos-Making-Science-James-Gleick/dp/0749386061)
- Practical Kanban: From Team Focus to Creating Value - by ['Klaus Leopold'](https://leanpub.com/practicalkanban)
- Lean Organization: from the Tools of the Toyota Production System
to Lean Office - by ['Andrea Chiarini'](https://www.springer.com/gb/book/9788847025097)
- [jordanbpeterson.com](https://jordanbpeterson.com/)- Dr Jordan B Perterson
- robertsapolskyrocks.com - ‘Robert Morris Sapolsky’

# Measuring Engineering Performance

## Measuring Engineering Performance

> 💡 The purpose of this document is to shed light on different ways of working. The goal being to build a caring high-performance culture.

#### Software Engineering, Sales, and Professional Services are fundamentally different.

> _**execsum:**_ [You get what you measure](https://hbr.org/2010/06/column-you-are-what-you-measure). Working Hours, Lines of Code, salaries, and other metrics have a weak, sometimes negative correlation with an organization’s ability to rapidly ship regret-free, scalable software. For sales experts and consultants, that’s counter-intuitive, goes against core beliefs, and matches neither perceptions nor internalized mental models. But it’s true nonetheless. Bridging that gap and coming to a trusting yet fully informed shared truth is (next to excellent hires, a strong case, and the ability to say NO) the essence of a B2B SaaS business’ success. Read on for what (not) to measure and what (not) to optimize.

#### What type of work is Software Engineering?

> 💡 SW engineering is not more or less challenging, productive, or valuable than any other function in a startup. It simply uses brains differently.

* SW engineering aims to **avoid repetition by constantly adding or rethinking complexity**.
* SW engineering is **continuous, creative decision-making**.
* **Many such decisions are hard to revert** (even a split-second decision by a junior can be prohibitively expensive to revert months later).
* **Negative work** is a thing: Hard-to-revert decisions made exhausted or stressed out can easily kill weeks of planning or work if not caught and reverted soon after. Under pressure, even seasoned seniors sometimes don’t have the hard-to-revert decisions they later learn were mistakes. Instead of decreasing, negative work increases the time remaining.
* After searching for a bug for 6 hours in a complex system of services, databases, queues, clients, and asynchronous, distributed state, any human’s brain would be completely exhausted.
* **Software development is complex, abstract, attentive work, and therefore hypersensitive to a developer’s mental state**. That is, there are hidden inputs at play: anxiety, depression, burnout, toxicity at work, grief, micro-aggressions, insufficient off-hours recovery, and a hundred other things that can reduce or invert individual productivity on any given day.

#### Measuring direct inputs slows us down

* Using working hours as key metric forces engineers to do negative work. They will accomplish less than if they went home earlier. Exacerbated by a reduced sense of self-efficacy, the impacts of a long working day are detrimental to the following days as well (Having to clean up, exhaustion)
* Measuring “Hours worked” is the path of least resistance. But instead, measuring performance is essential to scale a deep tech business.
* The performance of one engineer is easily several times that of another. Even working hours with a net-positive impact are often negligible.
* Using money as an input metric is worse: Paying more rarely boosts productivity, as does paying less.

#### Most output metrics are problematic

* Measuring lines of code or commits is terrible; every line of code that doesn’t solve a problem relevant customers have reduces the value of a software system. And it’s trivial to game.
* Measuring an engineer’s performance by features shipped inevitably results in a brittle system consisting of rapidly-built features that don’t quite fit and make it slower to develop future features, eventually deadlocking the company.
*   Individual performance can rarely be measured beyond a binary state of “this team member contributes” or “this team member does not contribute.” And it cannot be measured at a distance.

    A software development team is not a group of isolated individuals working alone; each team member’s work output is a function of work output from all their teammates, not to mention several meaningful non-measurable interactions throughout the day. The interdependencies and nuances of individual work are [too complex to be measured](https://martinfowler.com/bliki/CannotMeasureProductivity.html) by an outside observer. For example, some team members are force multipliers for the rest of their team—they may not accomplish a lot on their own, but their teammates would be significantly less productive without their help and influence. Individuals like this are a secret weapon of effective engineering organizations, but their productivity cannot be measured on an individual scale. Other team members may not produce a lot of features, but act as “code janitors,” carefully testing, cleaning up, and refactoring code wherever they go so that their teammates can develop features more quickly and painlessly. Their productivity as individuals is also impossible to measure, but their effect on the team’s productivity is exponential. Even for programmers that regularly ship new features, productivity [tends to vary greatly over the short term](https://insights.sei.cmu.edu/sei_blog/2020/01/programmer-moneyball-challenging-the-myth-of-individual-programmer-productivity.html), stifling efforts to track it with any specificity. For reasons like this, individual performance is best left for individual contributors to measure in themselves and each other.
*   Velocity is unreliable

    It’s easily skewed by blockers, absences, insufficient support from team members, supporting team members, bureaucracy, poor estimations, putting out fires, tiny interruptions, time pressure, and many more.
*   Team performance is far more visible

    A great way to track it is to ask, _does this team consistently produce useful software on a timescale of weeks to months?_ This echoes the [third Agile principle](https://agilemanifesto.org/principles.html): “Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.” A team that produces useful software on a regular basis is productive. A team that doesn’t should be asked why not. There are usually legitimate reasons for a lack of productivity; most unproductive teams want to be productive, and most productive teams want to be _more_ productive.

#### Building Blocks for a robust qualitative view of Performance and its improvement

The leading question is “_What limits this team’s ability to consistently produce useful software on a timescale of days to weeks?”_ and steadily deploying the following building blocks also steadily increases transparency and visibility into performance and bottlenecks.

The following list isn’t sorted by relevance, many points overlap.

*   **Excellent Leadership:** 10 Traits of excellent engineering managers

    [**Google Tried to Prove Managers Don't Matter. Instead, It Discovered 10 Traits of the Very Best Ones**](https://www.inc.com/scott-mautz/google-tried-to-prove-managers-dont-matter-instead-they-discovered-10-traits-of-very-best-ones.html)

    1. Is a good coach
    2. Empowers team and does not micromanage
    3. Creates an inclusive team environment, showing concern for success and well-being
    4. Is productive and results-oriented
    5. Is a good communicator — listens and shares information
    6. Supports career development and discusses performance
    7. Has a clear vision/strategy for the team
    8. Has key technical skills to help advise the team
    9. Collaborates across the organization
    10. Is a strong decision maker
* **Excellent hires:** All of this is incredibly complex and requires steady tuning. It doesn’t work without humble, driven, smart, empathetic team members who feel fulfilled working together.
* **Closing instead of starting:** Put effort into good tickets, keep work packages small (hours to days instead of days to months), and don’t start new things before things are done-done (zero further touches required). It drastically increases self-efficacy and a qualitative sense of performance between team members and across teams.
* **Upstream, upstream, upstream:**
  * Take engineers’ demands for roadmap quality, planning, and tickets seriously (not without challenging them of course).
  * Push left: In any funnel, optimizing further up has an outsized impact on overall performance
* **Strong feedback culture** to create virtuous cycles and regular surveys for anonymous feedback to find bottlenecks and issues
* **Healthy work and communication culture:** Build teams that enjoy interacting within and without, hire complementary personalities
* **A lot of pair programming** makes gaps visible quickly (and increases knowledge transfer, software quality, and the bus factor)
*   **Minimize interruptions**, provide continuous maker days to everybody writing code

    > _Batch hard but important intellectual work into long, uninterrupted stretches. -_ Adam Grant (Wharton)
* **Personal development:** Regular, structured 1on1s with qualitative performance assessment. Structured as a [progression framework](https://progression.fyi/).
* **Error culture:** Hire for and positively encourage everybody touching delivery to be eager to own up and talk about their failures.
*   **Minimizing Cycle Time** requires strong up- and downstream processes and reliable, fast automation.

    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bdfebea0-22ec-47c6-8e77-33d78c19da24/Untitled.png)

> 💡 Deploying these building blocks is hard and not straightforward, but that’s precisely why excellent engineering drives impact and value. And moving forward, it’ll be one of Atlas Metrics’ key differentiators to do this at scale.

### Tangentially useful special-purpose Metrics

#### DORA

[DORA](https://cloud.google.com/blog/products/devops-sre/the-2019-accelerate-state-of-devops-elite-performance-productivity-and-scaling) is based on a 7y research project at Google and its metrics help measure the performance of a DevOps team:

* **Deployment Frequency:** The frequency of successful software releases to production.
* **Lead Time for Changes:** The time between a code change commit and its deployable state.
* **Mean Time to Recovery:** The time between an interruption due to deployment or system failure and full recovery.
* **Change Failure Rate: H**ow often do a team’s changes or hotfixes lead to failures?

#### Helpful indicators for individual engineers

> 💡 **Doesn’t work at a distance.** For these to create value, you have to be close day-to-day to a peer/report. Because performance is a team effort, relying on second-hand experience and anecdotal evidence easily leads to adverse results.

* Does their work need lots of feedback and revisions during code review?
* Is their work frequently getting knocked back in QA?
* Do they fly through work or constantly get bogged down?
* Do they tackle a mix of tough and easier work, or always end up cherry-picking easy cards?
* Do they regularly deliver working, robust features into production?
* Are they the person you call when nobody else can figure out a problem?
* Do you like pair programming with them, or loathe it?
* Do you look forward to (or dread) making modifications to their code?
* Do they make everyone else on the team better?
* (And dozens of other signals.)

### Essential Reads and Media

* [Paul Graham: Maker's Schedule, Manager's Schedule](http://www.paulgraham.com/makersschedule.html)
* [StackOverflow blog: Can developer productivity be measured?](https://www.notion.so/atlasmetrics/Measuring-Engineering-Performance-30771167014f41419a2a40e300815b4a?pvs=4#ca25fc9c089a4e72b5486ba9e1e67ea8)
* [Engineering Productivity at Netflix: Outcome vs. Output](https://www.youtube.com/watch?v=I3yqrpiZ580)
* [LinearB: What is Developer Productivity and How to Measure it](https://linearb.io/blog/developer-productivity/)
* [How to objectively measure software developer productivity?](https://arc.dev/employer-blog/measuring-developer-productivity/)
* [Laura Tacho @ LeadDev London 2022 - What Dashboards don't tell you](https://www.youtube.com/watch?v=trO_fiTAZeM)
* [Pragmatic Engineer: Can you really measure individual developer productivity?](https://blog.pragmaticengineer.com/can-you-measure-developer-productivity/)
* [Are you using the right metrics to measure Developer Productivity?](https://www.7pace.com/blog/how-to-measure-developer-productivity)
* [HBR: The research is clear: Long hours backfire for people and for companies](https://hbr.org/2015/08/the-research-is-clear-long-hours-backfire-for-people-and-for-companies)
* [The world's biggest trial of the four-day work week has come to an end](https://www.weforum.org/agenda/2023/03/four-day-work-week-uk-trial/)

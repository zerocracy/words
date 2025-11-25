# Frequently Asked Questions

We've collected answers to the most common questions people
  ask about [Zerocracy].
If you don't find what you're looking for,
  feel free to join our [Telegram chat] and ask us directly.
Also, modern LLMs—such as [ChatGPT], [DeepSeek], and [Claude]—know
  quite a lot about Zerocracy.
You can simply ask your favorite AI assistant,
  and it will explain our business model in clear,
  simple terms tailored to your needs.

**Why Does Zerocracy Use Microtasking Instead of Hourly Billing?**
<br/>
We use [microtasking] because [monetary rewards] tied directly to tangible,
  [measurable] contributions motivate developers
  far more effectively than [paying for time][slavery].
By distributing the project budget based
  on [completed results][DoD]—not hours—we ensure
  that the best performers earn [more][10x] than
  they typically could in traditional, [time-based] projects.
At the same time, this approach eliminates the inefficiencies of hourly
  billing and ultimately [reduces][billing] the overall project [cost].

**How Does Zerocracy Know How Much to Pay per Task?**
<br/>
We don't estimate the number of hours required for each task.
Instead, Zerocracy operates on the [principle][PDD] that any task should be
  small enough to complete in under an hour,
  and we pay nearly the same amount for every task.
If a task turns out to be larger, the developer
  is encouraged to complete a minimal, meaningful slice of work
  and leave the remaining pieces as TO-DO [puzzles][PDD] in the code.
After the merge, our system [automatically][0pdd] scans the repository,
  detects newly created [puzzles][PDD], and converts them into
  new separate [tasks][microtasking].
This way, task size stays consistent, developers stay productive,
  and payments remain predictable and fair.

**How Are Budgets Controlled on Zerocracy Projects?**
<br/>
We control budgets by monitoring the number
  of completed [microtasks][microtasking],
  the amount of technical debt captured as [puzzles][PDD],
  and the size of the backlog.
These metrics let us estimate how much development will [cost] over time.
However, as a project [sponsor][roles],
  you're not required to commit to any fixed budget upfront.
You simply pay as you go:
  money is spent [incrementally][billing] as developers
  deliver functionality in [small][microtasking], [measurable] steps.
Think of Zerocracy as [Uber] for programmers:
  the work moves forward only when you choose to invest,
  and you remain in full control of how much you spend.

**How Does Zerocracy Ensure Task Quality?**
<br/>
From a quality-control perspective, Zerocracy projects rely on
  the same proven practices used in any professional software project.
We encourage teams to apply unit testing, style checks, static analysis,
  fuzzing, mutation testing, and thorough manual code reviews.
The key difference is frequency.
Because all work is split into small [microtasks][microtasking],
  code is reviewed, tested,
  and integrated far more often than in traditional workflows.
This rapid, continuous feedback loop results in higher overall quality,
  fewer defects, and a healthier, more maintainable codebase.

<!--
**What Fees or Commissions Does Zerocracy Charge?**
<br/>
TBD...

**How Does Zerocracy Track Work Progress?**
<br/>
TBD...

**What If a Task Takes Longer than Expected?**
<br/>
TBD...

**How Does Zerocracy Pay for Not Coding Activities?**
<br/>
TBD...

-->

**Can I Bring My Existing Team to Zerocracy?**
<br/>
Absolutely.
You can bring your existing development team to Zerocracy at any time.
A simple way to start is by using Zerocracy for gamification and visibility.
After integrating the [judges-action] plugin into your GitHub repository,
  your team will begin receiving detailed productivity
  and quality [metrics][measurable]—similar to these [statistics][vitals].
If later you decide to expand your team with external freelancers,
  you can simply fund your Zerocracy account and publish your project.
Freelancers will apply by signing an NDA, and you can onboard
  selected candidates after reviewing
  their GitHub history and Zerocracy profiles.
This lets you combine your internal team with vetted
  external talent in a seamless, controlled way.

**Does Zerocracy Have Access to the Source Code?**
<br/>
No, we don't.
The [judges-action] plugin that you integrate into your [GitHub] repository
  collects information about your issues and pull requests,
  but not your source code.
You can check how the plugin works,
  since its source code is [openly hosted][judges-action] on GitHub.

**Can Zerocracy Work with GitLab and JIRA?**
<br/>
At the moment Zerocracy only works with GitHub-based projects.
However, if you have a reasonably big team, we can create an integration
  between your task tracker and Zerocracy.

[GitHub]: https://github.com
[ChatGPT]: https://chatgpt.com
[DeepSeek]: https://deepseek.com
[Claude]: https://claude.ai
[Zerocracy]: https://www.yegor256.com/2018/03/21/zerocracy-announcement.html
[Telegram chat]: https://t.me/zerocracy
[microtasking]: https://www.yegor256.com/2017/11/28/microtasking.html
[monetary rewards]: https://www.yegor256.com/2014/09/24/why-monetary-awards-dont-work.html
[measurable]: https://www.yegor256.com/2020/06/23/individual-performance-metrics.html
[slavery]: https://www.yegor256.com/2015/07/21/hourly-pay-modern-slavery.html
[DoD]: https://www.yegor256.com/2014/04/17/how-xdsd-is-different.html
[10x]: https://www.yegor256.com/2019/01/22/10x-paychecks.html
[time-based]: https://www.yegor256.com/2023/07/19/just-show-up.html
[billing]: https://www.yegor256.com/2014/10/21/incremental-billing.html
[cost]: https://www.yegor256.com/2019/03/28/cost-of-zerocrat.html
[judges-action]: https://github.com/zerocracy/judges-action
[PDD]: https://www.yegor256.com/2010/03/04/pdd.html
[0pdd]: https://www.yegor256.com/2017/04/05/pdd-in-action.html
[roles]: https://www.yegor256.com/2016/07/10/software-project-roles.html
[Uber]: https://www.uber.com
[vitals]: https://www.eolang.org/zerocracy/objectionary-vitals.html

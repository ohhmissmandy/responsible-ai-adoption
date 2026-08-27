# What Should AI Be Allowed to Decide?

A lot of AI conversations start with capability: what a model can do, how well it does it, and how fast it's improving. I think organizations need to ask another question just as early: what should this system actually be allowed to decide on its own, without a person checking first?

Capability and authority aren't the same thing. A tool can be very good at something and still be a bad candidate for full autonomy if the occasional wrong answer has serious consequences. Figuring out what AI should decide on its own, what it should recommend, and where it should only assist is a different question from how capable the system is.

I think about it in three tiers. Real life is never this clean, but this gives me a practical way to sort the decision before something goes wrong:

* **Assist.** The system surfaces information, options, or a first draft. A person still makes the call and is expected to actually engage with it, not rubber-stamp it.
* **Recommend.** The system proposes a specific action, and a person approves or rejects it before anything happens.
* **Decide.** The system can execute the action on its own, without case-by-case human approval, though that doesn't mean no one is watching. Monitoring, audits, exception handling, or after-the-fact review can still be part of how it runs.

There's real pressure to let AI make more decisions because automation can make the work faster, easier to scale, or cheaper. Those benefits show up quickly. The downside can be harder to picture until something actually goes wrong. Accuracy matters, but I also want to know what happens when the system is wrong. A recommendation engine suggesting the wrong document may be a minor annoyance. A system deciding whether to flag, block, or approve something with real consequences for a person or the business is a very different situation.

Reversibility is the other thing I keep coming back to. If a wrong decision is easy to spot and undo, more autonomy may be reasonable. If it's hard or impossible to unwind, I want a person in the loop even when the system is usually right. Being right most of the time isn't enough if the one wrong decision can cause lasting harm.

Then there's accountability. If a decision goes wrong, somebody needs to own the outcome and be able to explain what happened. That doesn't mean a person has to make every decision manually. It does mean someone needs the authority to review it, challenge it, intervene, or escalate when something doesn't look right. If nobody can clearly tell me who owns the outcome and what they can do about it, I'm not comfortable handing that decision over.

We already use a lot of this same thinking in technology work with real operational risk. We test before a full rollout. We pilot before scaling. We monitor what happens once something is live, and we plan for what to do if it fails. AI adds its own governance questions, including how models can change over time and how to explain decisions that weren't explicitly programmed step by step. The basic habit still applies: understand what happens when it fails before you scale it.

For me, the practical version starts with three questions: What happens if it's wrong? Can we undo it? Who owns the outcome if we can't? That's a good starting point, but it isn't enough on its own. Privacy, security, regulatory requirements, fairness, and data quality can all change the answer. If any of those raise concerns, the system should stay in Assist or Recommend until those concerns are addressed.

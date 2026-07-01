## Vibe-Coded PR Shall Not Pass

As you grow as a developer, your responsibility changes. At some point, you become the wizard standing on the bridge.

A pull request should not pass simply because it compiles, passes a handful of tests, or was generated quickly. It should pass because someone understands what it does and has confidence that it improves the codebase. Don't review code based on vibes. Interrogate it.

* Why did this implementation change?
* What problem is it solving?
* Why was this dependency added?
* Why did the value in the dependency array change?
* What assumptions does this code make?
* What happens in edge cases?
* Does this follow the existing architecture?
* Will the next engineer understand it six months from now?

Whether the code was written by a teammate, an AI assistant, or your past self, the standard is the same. Curiosity is one of the most valuable tools in code review. Every merged pull request becomes part of the codebase's history. If you approve code you don't understand, you're also approving the maintenance burden that comes with it. The wizard on the bridge isn't there to stop progress. They're there to make sure the right code crosses.

## Don't Be a Unicorn

Unicorns are flashy. We all love Swiftwind.

But on a production codebase, you need to be Gandalf.

As your career progresses, your value increasingly comes from judgment rather than novelty. You become the person who asks the next question, catches the subtle bug, recognizes an unnecessary dependency, or notices that a seemingly harmless refactor changes behavior in unexpected ways.

That responsibility extends to code review. Unreviewed vibe-coded pull requests must not pass into production simply because they compile or look convincing. Someone has to understand what changed, why it changed, and whether it makes the codebase better.

Every engineering team needs people who protect the bridge.

Don't aspire to be the mythical engineer who knows everything.

Be the wizard others trust to say, "This shall not pass," until the code earns its way across.

I've been on both all sides of this. I've approved code without reading closely enough and learned to be more discerning, but I also pushed code I should've reviewed more and had it rejected. And I've rejected code myself or come to understand why code was rejected. Even if your solution is right, you need to be able to articulate it. 


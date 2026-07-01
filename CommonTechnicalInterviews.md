## Common Technical Interviews

Technical interviews come in many forms. Although they differ in format, most are evaluating some combination of problem-solving, communication, software engineering fundamentals, and technical judgment.

Over the course of my career, I've encountered several different styles.

### Data Structures and Algorithms (DSA)

When people talk about "LeetCode," they're often using it as shorthand for data structures and algorithms interviews rather than referring to the platform itself.

The "LeetCode approach" is frequently characterized by solving a large volume of algorithmic problems. That repetition can build familiarity with common patterns and improve problem-solving speed.

I recommend treating DSA as one part of a broader engineering education rather than as a complete interview strategy.

Study algorithms alongside application development. Build real software. Learn databases, APIs, authentication, testing, deployment, and system design. Practice decomposing product requirements into working features, not just decomposing algorithmic puzzles.

These skills reinforce one another. The strongest engineers I know don't separate algorithmic thinking from software engineering. They apply the same problem decomposition skills at different scales.

I tried many approaches with DSA. I tried Leetcode, direct whiteboarding, various YouTube tutorials. I especially used Neetcode. I tried rote memorization and working through code. I tried copying and then brute forcing copy knowledge.

What finally worked for me was building from problem decomposition in Google Docs as I do with system design. 

I think the real challenge for DSA is that it's hard to be motivated to practice it until you hit absolute blockers in problem decomposition under pressure. I kept saying I was going to practiced it, but what finally forced my hand was more coding tribulations for with interviews.

## Conversational Interviews

At first glance, a conversational technical interview might seem like the easiest format. After all, you're "just talking."

In practice, they can be some of the most demanding interviews you'll encounter.

Rather than writing code, you're asked to think out loud. You explain architectural decisions, justify technical tradeoffs, discuss projects you've built, and answer follow-up questions in real time. There is no compiler to tell you when you've misspoken or overlooked an assumption.

I experienced this firsthand during a technical interview for a consulting role. As the conversation progressed, I realized that my technical fluency under pressure needed work. I understood many of the concepts, but understanding something and explaining them clearly, accurately, and confidently are different skills.

That realization changed how I prepared for interviews.

I stopped thinking of technical knowledge as something I simply possessed. Instead, I began practicing the ability to retrieve that knowledge, organize it, and communicate it under pressure.

Like many interview formats, conversational interviews ultimately reward problem decomposition. The difference is that instead of demonstrating your thinking through code, you're demonstrating it through language. The interviewer is often evaluating not only what you know, but how you reason, how you communicate, and how you respond when a discussion becomes more complex.

In my experience, interviews for consulting, architecture, and technical advisory roles often blend technical fundamentals with business context. I encountered questions about object-oriented programming, SQL, system design, and software architecture alongside discussions about AI, automation, and how those technologies could create value for large organizations.

That combination reflects the nature of the work. You're not only expected to understand technology. You also need to explain why a particular technical decision makes sense in the context of a business problem.

## Time awareness

The challenge wasn't the concepts themselves. It was maintaining technical fluency under pressure in a time-constrained conversation.

Unlike a coding interview, there was no opportunity to quietly reason through the problem by writing code. I had to retrieve knowledge, organize it, and communicate it coherently while responding to follow-up questions in real time.

That made me realize that technical fluency is a skill worth practicing independently. It's one thing to understand object-oriented programming, SQL, or software architecture. It's another to explain those concepts clearly and confidently when someone is evaluating your reasoning.

Like coding, verbal technical communication improves with deliberate practice.

### Feature Implementation

Rather than solving a standalone algorithm, you're asked to build a small feature. This may involve creating an API, implementing a UI component, fixing a bug, or extending an existing codebase. These interviews more closely resemble day-to-day software development.

Developers often get excited when they hear they can use an AI coding assistant during the interview. That flexibility can certainly be helpful, but it also introduces a different set of challenges.

Using an AI tool effectively is a skill in its own right. You still need to understand the problem, evaluate the generated code, recognize when the model has misunderstood the requirements, and integrate its suggestions into an existing codebase. In many cases, reviewing and correcting AI-generated code becomes part of the exercise.

I found that these interviews rewarded engineering judgment more than prompt writing. The bottleneck wasn't getting code generated. It was deciding whether the generated code was correct, maintainable, and appropriate for the task at hand.

I had an interesting experience with this. I recently did a live coding interview with Cursor, an AI tool, and a stack I'm familiar with, Next.js with Prisma and TS. I did touch tRPC, which I hadn't before, but this didn't feel too different. I set up the codebase on localhost. 

It was my stack and a tool I'm familiar with, so pretty easy, right? 

Actually... there were unique challenges with this approach. 

I thought ahead on some aspects of the implementation. I proposed beginning with the codebase's existing patterns, but I don't think I spent enough time building a mental model of what I was about to implement.

I didn't yet have a clear understanding of the schema or the data layer. I had worked with Prisma before, but not with the level of ownership required to confidently explain how the Prisma schema, the generated TypeScript types, and the tRPC procedures fit together.

When Cursor helped, its generated logic became a distraction rather than an accelerator. I recognized much of what it produced, but recognizing code and reasoning about it are different skills. I didn't yet have the backend vocabulary to quickly evaluate the tradeoffs, explain why one approach fit the existing architecture better than another, or confidently reject an implementation that looked plausible but wasn't quite right.

That experience taught me that AI-assisted development raises the bar for engineering judgment. The faster code appears on the screen, the more important it becomes to understand the system well enough to evaluate it.

Do not assume AI-assisted feature implementation is a magic easy route. It can surface technical limitations. 

## One lesson kept recurring across different interview formats: recognition is not the same as reasoning.

I often recognized technologies, algorithms, or generated code because I had seen them before. But interviews rarely reward recognition alone. They reward the ability to explain why something works, identify tradeoffs, connect it to the surrounding system, and adapt when the problem changes.

The gap between recognizing a solution and reasoning through it is where much of technical growth happens.


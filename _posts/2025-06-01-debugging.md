---
title: "Debugging 🐞"
tags: [Debugging, "Problem Solving", Methodology]
excerpt: "We all face broken systems in our careers, but how we fix them separates the amateurs from the masters. Distilling David J. Agans' nine debugging rules into two core questions you can actually apply."
---

We all face broken systems in our careers, but how we fix them separates the amateurs from the masters.
The appeal of the methods presented in David J. Agans' book, *Debugging*, is that they can be adapted to a
wide range of domains. The process is simple and easy to understand. In fact, most of us subconsciously
apply these steps in our daily and professional lives already.

However, we first need to clarify what the author means by "debugging" and how it differs from
"troubleshooting," as the meaning can vary across different domains. To quote:

> "Debugging usually means figuring out why a design doesn't work as planned. Troubleshooting usually means
> figuring out what's broken in a particular copy of a product when the product's design is known to be good."

Examples:

- Car mechanics troubleshoot. Car designers debug.
- Doctors troubleshoot the human body. (Which begs the question: who debugs it?)

In short, debugging is improving a system or process to address foundational flaws, while troubleshooting is
a targeted effort to fix a specific breakage. We can also expand this: debugging is design-level problem
solving, and troubleshooting is operational problem solving.

Hopefully, we are on the same page regarding the definition. Now, what are the basic steps? According to the
author:

1. UNDERSTAND THE SYSTEM
2. MAKE IT FAIL (Observe how it is failing)
3. QUIT THINKING AND LOOK
4. DIVIDE AND CONQUER
5. CHANGE ONE THING AT A TIME
6. KEEP AN AUDIT TRAIL
7. CHECK THE PLUG (Test every assumption)
8. GET A FRESH VIEW (To avoid tunnel vision)
9. IF YOU DIDN'T FIX IT, IT AIN'T FIXED

The author expands on each step with great stories and detailed analysis. I highly recommend reading the
book. But here, I'd like to distill these nine steps into two core questions that make them easier to apply.

## 1. How do we understand the situation?

Before you can solve a problem, you need to understand the context - how the system was designed to work, and
exactly how it is currently failing. The gap between those two is where your answer lives.

This sounds obvious, but we regularly skip it. We overestimate our familiarity with a system and jump
straight to fixing. That overconfidence is expensive. Instead, treat everything as a potential suspect -
especially the things you take for granted. The step "Check the Plug" exists precisely because people
routinely overlook the obvious when they assume they already know the answer.

To avoid tunnel vision, deliberately step back and seek outside perspectives. A fresh pair of eyes doesn't
carry your assumptions, and that alone can cut your debugging time significantly.

## 2. How do we approach the solution?

Once the context is clear, the approach is methodical: break the system down into its basic functions and
inspect them one by one. This is "Divide and Conquer" in practice - you're narrowing the search space until
the failure has nowhere to hide.

Crucially, change only one thing at a time. It's tempting to fix multiple suspected issues simultaneously, but
that destroys your ability to know what actually worked. Document every step as you go. An audit trail isn't
just good practice - it's your evidence when someone asks you later what happened and why.

And finally: the problem is only solved when you understand exactly what you fixed and why. A system that
stopped failing on its own is not a fixed system. It's a ticking clock.

Now you might be wondering - isn't this just common knowledge? Yes. Is it practiced properly? Rarely. We tend
to emphasize the steps that feel natural to us and skip the rest, which is exactly why the same problems keep
coming back.

In large organizations, this gets harder. Aligning everyone's attention becomes a real challenge when only
results seem to matter. Think about the last time you got cut off trying to explain context to senior
management, or received a vague process-change email that raised more questions than it answered. The
debugging mindset is partially about solving problems - but it's also about communicating systematically under
pressure, which is where most people fall apart.

Applying these steps also requires domain-specific tools. A product manager might use empathy mapping to
understand system failures from the user's perspective. An engineer might use logs and stack traces. The
underlying logic is the same; the instruments differ. Part of becoming a strong problem solver is building
your own toolkit of these instruments over time.

## Some takeaways

- If your instincts tell you a situation is about to get ugly, start documenting immediately. In general,
  documentation is always a good habit.
- Develop reusable processes and tools as you progress through your career. The frameworks you build now will
  serve you repeatedly.
- This effort may not always produce visible achievements, but it will sharpen your soft skills - and at
  critical moments, having a clear framework will give you confidence when others are scrambling.
- If you manage a large team, these steps will help you navigate systematically when a crisis makes everything
  blurry.
- The first part of debugging - understanding the system, requires upfront time and effort. That tells you
  exactly what to be doing when everything is running smoothly: learning your system deeply before you need to
  fix it.

My concluding thought: storms will come wherever you work. Invest early in understanding how your role
connects to the larger system, both above and below you. Stars shine brightest in the dark - don't miss your
moment when it arrives.

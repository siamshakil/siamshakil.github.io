---
title: "TRIZ in Practice: Resolving Contradictions in Product Design & Business"
tags: [TRIZ, "Design Methods", Business]
excerpt: "Most design contradictions are not trade-offs - they're unsolved problems. TRIZ gives a vocabulary for separating what you want from what you currently accept, and the same logic applies to business decisions, not just hardware."
---

Most design contradictions are not trade-offs - they are unsolved problems. The difference matters. A
trade-off says *you can have strength or low weight, pick one*. A contradiction says *you want strength
and low weight, and you have not yet found the structure that gives you both*. TRIZ (the Theory of
Inventive Problem Solving) is a vocabulary for telling those two situations apart and for attacking the
second one systematically.

## The core idea: contradictions, not compromises

TRIZ was built by Genrich Altshuller after he studied hundreds of thousands of patents and noticed that
inventive solutions repeat the same patterns. Its central claim is that strong solutions *eliminate* a
contradiction rather than balancing it. Two kinds matter:

- **Technical contradiction** - improving one parameter degrades another (make the wall thicker for
  strength, and it gets heavier).
- **Physical contradiction** - one parameter must take two opposite values (the surface must be hot to
  cure and cold to handle).

Once a problem is framed this way, TRIZ offers a toolbox: the 40 inventive principles, the contradiction
matrix, separation principles (in time, in space, on condition), and the idea of the *ideal final result* -
the function delivered with the mechanism removed.

## Three examples from real design sessions

- **Separation in time.** A fixture had to clamp hard during machining and release instantly after. The
  contradiction - high force and zero force - dissolved once we separated the two states in time with a
  spring-loaded cam rather than a single fixed setting.
- **Local quality.** A bracket needed stiffness in one axis and compliance in another. Instead of one
  uniform material choice, we varied the geometry locally - rib where stiffness mattered, slot where it
  did not.
- **The other way around.** A cooling step was slowing the line. Rather than cooling the part faster, we
  inverted it: pre-chill the tool so the part left the station already within tolerance.

None of these were compromises. In each case the apparent trade-off was a sign we had not yet found the
right structure.

## TRIZ is not only for hardware

The part most engineers miss is that the contradiction framing is domain-independent. Business decisions
are full of the same structure dressed in different language:

- *We want low price and high margin.* (Separate on condition: tiered products, where the entry tier
  defends share and the premium tier carries margin.)
- *We want fast delivery and low inventory.* (Separate in space: regional buffer stock for fast movers,
  central stock for the long tail.)
- *We want a standard product and a customised one.* (Separation by system level: a common platform with
  configurable modules - the same logic as TRIZ principle 1, segmentation.)

Altshuller's later work and a body of practitioners extended this explicitly into **Business TRIZ** -
applying the inventive principles and separation logic to management, marketing, and process problems. The
moves are identical; only the parameters change.

## How it sits next to existing methods

TRIZ is not the only structured problem-solving system, and it is worth being honest about where it
overlaps and where it is distinct:

- **Six Sigma / DMAIC** is superb at reducing variation in a known process, but it optimises within the
  current design. It tells you *how well* you are hitting a target, not how to remove the target's
  constraint. TRIZ is for the inventive step that Six Sigma assumes already happened.
- **Design Thinking** is strong on framing the right human problem and diverging on ideas, but its ideation
  is largely unstructured brainstorming. TRIZ replaces "think of something clever" with a directed search.
- **Lean** removes waste; TRIZ removes contradictions. They are complementary - Lean asks *should this step
  exist*, TRIZ asks *how do we get its benefit without its cost*.
- **QFD (Quality Function Deployment)** translates customer needs into engineering targets and surfaces
  *where* contradictions live. It pairs naturally with TRIZ, which then *resolves* them. I use them together:
  QFD to find the conflict, TRIZ to break it, a Pugh matrix to choose between the survivors.
- **Blue Ocean Strategy** is, in effect, business contradiction-breaking at the market level - eliminate,
  reduce, raise, create - and reads like Business TRIZ applied to value curves.

The honest summary: TRIZ is the specialist tool for the *inventive* part of problem solving. It does not
replace these methods; it slots into the one place most of them quietly skip - the moment you are told to
accept a trade-off and you refuse to.

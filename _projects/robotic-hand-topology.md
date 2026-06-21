---
title: "Topology-Optimized Robotic Arm"
order: 3
year: 2019
status: "Topology Opt."
tags: ["Topology Optimization", "SIMP", "Robotics", "FEA"]
excerpt: "Weight reduction of an industrial robot arm using SIMP-based topology optimization - 40% lighter than the baseline while retaining strength. The manipulator both drills soil and extracts a sample without changing attachments."
---

![Topology-optimized robotic arm](/assets/images/projects/robotic-hand-arm.png)

The objective was to **reduce weight from the arm of an industrial robot** to increase efficiency while
retaining the strength. The manipulator was designed to handle two tasks - **drilling soil and extracting
a sample** - without changing the attachments.

The result was a **40% weight reduction** from the base design, achieved with the **SIMP** topology
optimization method.

![Baseline arm vs topology-optimized arm](/assets/images/projects/robotic-hand-topology.png)

## What topology optimization is

Topology optimization is a mathematical method that decides *where to put material* inside a given design
space, for a defined set of loads, supports, and constraints, so that performance is maximised and mass is
minimised. Unlike sizing or shape optimization - which tweak the dimensions of an existing form -
topology optimization can change the fundamental layout, producing the organic, load-path-following
geometry typical of optimised parts.

## The SIMP method

The approach used here is **SIMP - Solid Isotropic Material with Penalization**, the most widely used
topology-optimization scheme:

- The design space is divided into finite elements, and each element is given a **density variable between
  0 (void) and 1 (solid)**.
- A **penalization exponent** (typically *p* = 3) makes intermediate "grey" densities inefficient, pushing
  the solution toward a clean solid-or-void layout that is actually manufacturable.
- The optimiser iterates using **sensitivity analysis**, minimising compliance (i.e. maximising stiffness)
  subject to a **volume-fraction constraint** - the target amount of material allowed.

The outcome is a structure that carries the load along the most efficient paths, which is exactly why the
optimised arm keeps its strength after shedding 40% of its weight.

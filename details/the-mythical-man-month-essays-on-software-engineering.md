## Overview

Published in 1975 and based on Brooks's experience managing IBM's OS/360 project, The Mythical Man-Month is the most influential book ever written on software project management. Its insights remain devastatingly relevant 50 years later.

## Brooks's Law

**"Adding manpower to a late software project makes it later."**

Why?
- New people need to get up to speed (training cost)
- Communication overhead increases exponentially with team size
- Tasks must be repartitioned (coordination cost)
- The mythical "man-month" assumes tasks are perfectly partitionable and people perfectly interchangeable

They're not.

## Key Essays

### The Tar Pit

Programming is fun. Programming systems products is hard. The difference:
- A program that works for you
- vs. A system product: generalized, tested, documented, maintainable

The latter takes 9x more effort.

### The Mythical Man-Month

Men and months are interchangeable only when:
- Tasks can be partitioned with no communication between workers
- Example: picking cotton, not software development

For software:
- Communication dominates
- Training is essential
- Adding people increases communication overhead

**Key insight**: If a task takes one woman 9 months, nine women cannot do it in one month.

### The Surgical Team

Instead of democratically organized teams, Brooks advocates for "surgical teams":

**The Surgeon** (Chief programmer):
- Defines specifications
- Writes code
- Tests it
- Writes documentation

**Supporting cast**:
- Copilot: Thinks about problems, can code
- Administrator: Handles non-technical matters  
- Editor: Polishes documentation
- Secretaries: Support roles
- Program clerk: Maintains code and documentation
- Toolsmith: Builds specialized tools
- Tester: Writes test cases
- Language lawyer: Expert in technical details

Ratio: 1 surgeon to 9 support → 10x productivity of a 10-person democratic team.

**Modern interpretation**: Have a small number of senior engineers supported by specialists, rather than many mid-level generalists.

### Conceptual Integrity

**Most important consideration in system design.**

Ensure:
- Single architect or small team defines system
- Consistent design philosophy
- No "design by committee"
- Clear separation: architecture (what) vs. implementation (how)

**Key quote**: "I will contend that Conceptual Integrity is the most important consideration in system design. It is better to have a system omit certain anomalous features and improvements, but to reflect one set of design ideas, than to have one that contains many good but independent and uncoordinated ideas."

### The Second-System Effect

**The second system an architect designs will be the most dangerous.**

Why?
- First system: Constrained, conservative
- Second system: Overconfident, kitchen sink everything
- Includes all ideas withheld from first system
- Result: Baroque, overdesigned disaster

**Defense**: Self-discipline and tough-minded review.

### Plan to Throw One Away

**You will throw it away anyway, whether you plan to or not.**

- First system teaches you what you really need
- Pilot systems fail for: wrong functions, performance, or poor design
- Build the pilot system with the plan to discard it
- The real system is the second iteration

**Modern interpretation**: This is the MVP / iteration philosophy decades before Lean Startup.

### No Silver Bullet

(Added in Anniversary Edition, 1995)

**There is no single development that will give order-of-magnitude improvements.**

Why? Because complexity is essential to software:
- **Essential complexity**: Intrinsic to the problem
- **Accidental complexity**: From tools and implementation

Most improvements address accidental complexity. Essential complexity remains.

**Key insight**: Better tools won't save bad projects. Understanding the problem will.

## Communication

**The critical problem in large teams:**

- For n people, there are n(n-1)/2 communication paths
- 10 people = 45 communication paths
- 50 people = 1,225 communication paths

**Brooks's solution**:
- Reduce n (smaller teams)
- Reduce need for communication (better architecture, clear interfaces)
- Formal communication through documentation

## Estimating

**1/3 planning, 1/6 coding, 1/4 component test, 1/4 system test**

Most developers:
- Assume coding is 1/2 of the project
- Ignore testing time
- Result: Projects are late

**Brooks**: Testing takes as much time as coding. Plan for it.

## What Founders Will Learn

- Why throwing more engineers at a problem doesn't work
- The importance of conceptual integrity (product vision)
- Team structure matters enormously
- Communication overhead dominates at scale
- Why second versions are dangerous (avoid feature creep)
- Planning for iteration, not perfection
- Realistic project estimation
- The difference between essential and accidental complexity

## Relevance for Startups

**Still true:**
- Small teams with clear ownership outperform large teams
- Architectural consistency matters more than features
- Adding people to solve speed problems often backfires
- Plan to iterate, not to get it right first time
- Communication overhead is your enemy

**Less relevant:**
- The specific organizational structure ("surgical teams")
- Documentation practices (evolved since 1975)
- Development tools (obviously)

**Core principles endure.**

## Key Quotes

- "How does a project get to be a year late? One day at a time."
- "The bearing of a child takes nine months, no matter how many women are assigned."
- "Good cooking takes time. If you are made to wait, it is to serve you better, and to please you."
- "Question: How does a large software project get to be one year late? Answer: One day at a time!"

## For Technical Founders

This book matters because:
- You'll hire engineers
- You'll be tempted to hire too many
- You'll want to add people to late projects
- You'll need to understand why that fails

Reading Brooks first saves painful lessons.

## About the Author

Frederick P. Brooks Jr. managed the OS/360 project at IBM (1964-65), one of the most complex software projects of its time. The project was late, over budget, and taught him lessons he distilled in this book.

Brooks won the Turing Award (1999) and the National Medal of Technology (1985).

## Pricing

Originally published 1975. Anniversary Edition (1995) by Addison-Wesley includes "No Silver Bullet" and other reflections. ISBN: 978-0-201-83595-3. Available in paperback and ebook.

Part of the O'Reilly catalog. One of the most assigned books in computer science programs worldwide.
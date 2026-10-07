# RedsScheduler

Buffer-aware scheduling for game development.

- Prefilled from the current **The Storefront** TickTick roadmap.
- New work records effort, priority, deadline, dependency, and whether the date is hard.
- Capacity is calculated after a configurable uncertainty buffer.
- Rebalancing moves lower-priority work before critical work and protects milestones.
- Low-value work can be pushed to backlog rather than silently consuming deadline buffer.
- Imported tasks with no effort estimate are explicitly marked as assumed until calibrated.
- Browser changes persist locally.

Default model: 8 hours/day, 30% protected buffer, 5.6 schedulable hours/day.

GitHub Actions deploys the repository root to GitHub Pages on pushes to `main`.

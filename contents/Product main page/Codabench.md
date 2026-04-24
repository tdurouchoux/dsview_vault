---
already_read: true
link: https://www.codabench.org/
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-04-24'
---

https://www.codabench.org/
## Summary

Codabench is an open-source platform for organizing AI benchmarks and competitions, evolved from CodaLab (launched 2013 by Microsoft/Stanford). Key features:
- **Flexible benchmarking**: Define tasks (datasets/metrics), customize submission interfaces, scoring programs, and leaderboards.
- **Code/result submissions**: Supports both (code submissions allow fairer benchmarks via uniform execution environments).
- **Inverted benchmarks**: Swap datasets/algorithms (participants submit datasets against reference algorithms).
- **Custom compute**: Organizers can integrate their own workers for scalable computing.
- **Active research use**: Hosted high-profile challenges (e.g., COVID-19 prediction, ECCV face recognition) and supports reproducible research via "executable papers" (worksheets).

**Key stats**: 62,260+ users, 1,172 public competitions, 514,621+ submissions.
**Technical notes**:
- Default CPU queue for small jobs (20-min cap); organizers must provide queues for code submissions.
- Upcoming system upgrade (April 28, 2pm CET) may cause downtime.
- Open-source (GitHub); contributors welcome.

**Partners**: Includes Chasuite, Chahub, and Chagrade.
**Citation**: Xu et al. (2022) in *Patterns* (DOI: 10.1016/j.patter.2022.100543).
## Links

- [CodaLab Competitions Public Competitions](https://www.codabench.org/competitions/public/?page=1) : Access to public competitions hosted on Codabench for exploring and participating in AI and machine learning challenges.
- [Codabench Documentation for Organizers](https://docs.codabench.org/latest/Organizers/Benchmark_Creation/Getting-started-with-Codabench/) : Official documentation guiding organizers on creating and managing benchmarks on Codabench.
- [Codabench GitHub Repository](https://github.com/codalab/codabench) : GitHub repository for Codabench, providing access to the source code, contribution opportunities, and release details.
- [Codabench Newsletter Archive (2025)](https://docs.codabench.org/dev/Newsletters_Archive/CodaLab-in-2025/) : Access to the Codabench newsletter for 2025, summarizing key updates, competitions, and platform developments.
- [Codabench Paper on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2666389922001465) : Academic paper published in *Patterns* journal, detailing the features, architecture, and purpose of the Codabench platform.

## Topics

![[topics/Platform/Codabench]]

![[topics/Platform/CodaLab Competitions]]

![[topics/Concept/Inverted Benchmarks]]

![[topics/Concept/Compute Workers]]

![[topics/Concept/Reproducibility]]
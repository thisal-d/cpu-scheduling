# CPU Scheduling Practice Repository 📚

This workspace contains a set of practice questions and solutions covering common CPU scheduling algorithms used in operating systems courses. The content is organised by scheduling type to make navigation easy.

## Structure

```
questions/      - all question files, grouped by algorithm
answers/        - corresponding solutions in the same folder layout
README.md       - this file
```

Each algorithm directory contains at least **3 practice questions**; the preemptive SJF directory has **5 questions** as requested.

## Algorithms Covered

| Directory | Description |
|-----------|-------------|
| `fcfs` | First-Come, First-Served (FCFS) |
| `sjf_nonpreemptive` | Shortest Job First – non‑preemptive |
| `priority` | Priority scheduling (non‑preemptive) |
| `roundrobin` | Round Robin (RR) with various time quanta |
| `sjf_preemptive` | Shortest Remaining Time First (preemptive SJF) |

Each folder contains `q1.md`, `q2.md`, etc. for questions and corresponding `a1.md`, `a2.md`, etc. for answers.

## How to use

1. Open a question MD file under `questions/<algorithm>` to try solving it.
2. When ready, open the matching answer file under `answers/<algorithm>` to check your work.
3. Use the table of contents or your editor's file explorer to jump between algorithms.

> Feel free to add more questions or expand the repository as you want!

## Question Navigation

Click any link below to jump straight to that practice problem.

### FCFS
- [q1](questions/fcfs/q1.md)
- [q2](questions/fcfs/q2.md)
- [q3](questions/fcfs/q3.md)

### Non-preemptive SJF
- [q1](questions/sjf_nonpreemptive/q1.md)
- [q2](questions/sjf_nonpreemptive/q2.md)
- [q3](questions/sjf_nonpreemptive/q3.md)

### Priority Scheduling
- [q1](questions/priority/q1.md)
- [q2](questions/priority/q2.md)
- [q3](questions/priority/q3.md)

### Round Robin
- [q1](questions/roundrobin/q1.md)
- [q2](questions/roundrobin/q2.md)
- [q3](questions/roundrobin/q3.md)

### Preemptive SJF
- [q1](questions/sjf_preemptive/q1.md)
- [q2](questions/sjf_preemptive/q2.md)
- [q3](questions/sjf_preemptive/q3.md)
- [q4](questions/sjf_preemptive/q4.md)
- [q5](questions/sjf_preemptive/q5.md)

---

## 📝 Practice Papers
Ready for a challenge? Try these mixed-algorithm papers with missing data!

| Paper | Description | Solutions |
|-------|-------------|-----------|
| [Paper 1](papers/paper1.md) | All 5 types, missing burst/WT | [Sol 1](answers/papers/paper1_sol.md) |
| [Paper 2](papers/paper2.md) | Advanced reverse-engineering | [Sol 2](answers/papers/paper2_sol.md) |
| [Paper 3](papers/paper3.md) | SRTF Masterclass + Gantt Charts | [Sol 3](answers/papers/paper3_sol.md) |


---

Happy studying! ✅
---

Happy studying! ✅
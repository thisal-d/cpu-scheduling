
## First- Come, First-Served (FCFS) Scheduling

Suppose that the processes arrive at the same time in the order: $ P_{1}, P_{2}, P_{3} $

<table><thead><tr><th>Process</th><th>Burst Time (ms)</th></tr></thead><tbody><tr><td>P1</td><td>24</td></tr><tr><td>P2</td><td>3</td></tr><tr><td>P3</td><td>3</td></tr></tbody></table>

The Gantt Chart for the schedule is:

<table border="1"><tr><td>$P_{1}$</td><td>$P_{2}$</td><td>$P_{3}$</td></tr><tr><td>0</td><td>24</td><td>27</td><td>30</td></tr></table>

Waiting time for processes;

- P1 = 0 ms

P2 = 24 ms

P3 = 27 ms

Average waiting time: $ ( 0+2 4+2 7 ) / 3 $ =17ms

Turnaround time for processes;

P1 = 24 ms

P2=27ms

- P3 = 30 ms

Average Turnaround time: (24+ 27+30)/3=27ms

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347195.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=4pCRaQfdyW0BSxCn4xEkySajrZ4%3D&Expires=1773717147' alt='OCR图片'/></div>

## First- Come, First-Served (FCFS) Scheduling

Suppose that the processes arrive at the same time in the order: $ P_{2}, P_{3}, P_{1} $

<table border="1"><tr><td>Process</td><td>Burst Time(ms)</td></tr><tr><td>P1</td><td>24</td></tr><tr><td>P2</td><td>3</td></tr><tr><td>P3</td><td>3</td></tr></table>

The Gantt Chart for the schedule is:

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347203.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=YP6S4FZ2y7w0yOMtFmtLFza1I1I%3D&Expires=1773717147' alt='OCR图片'/></div>

Waiting time for processes;

- P1 = 6 ms

- P2 = 0 ms

Turnaround time for processes;

- P3 = 3 ms

P1 = 30 ms

- P2 = 3 ms

- P3 = 6 ms

Average waiting time: $ ( 6+0+3 ) / 3= $ Average Turnaround time: $ ( 30+ 3+6 ) / 3=1 3 \mathrm{m s} $

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347211.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=cbjqZlwjZX0mGcfLXvYO%2F%2BIjzfc%3D&Expires=1773717147' alt='OCR图片'/></div>

## First- Come, First-Served (FCFS) Scheduling

- First- Come, First-Served scheduling is one of the simplest types of Non- preemtive CPU scheduling algorithms.

- The processes are attended to in the order in which they arrive in the ready queue.

- FCFS can result in long waiting times, if a long process arrives before a shorter one.

- This is known as the Convoy effect, where shorter processes are forced to wait behind longer processes, leading to inefficient execution.

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347218.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=T8T20NYDWiqFUW3OR8diSUA5W4o%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347225.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=px%2BvejfqyTpt94VGPgQ2A2Re%2Bbc%3D&Expires=1773717147' alt='OCR图片'/></div>

## Shortest-Job-First (SJF) Scheduling

- Shortest-Job-First is a scheduling process that selects the waiting process with the smallest execution time to execute next.

- This may or may not be preemptive.

- This is the optimal scheduling algorithm which gives minimum average waiting time for a given set of processes.

- However, this is not practically feasible, as it is difficult to know the length of the next/ future CPU request.

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347231.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=VV6%2Bv7acm9z8UubxQZ4XatqkPus%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347236.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=olYTCovxw58Mo080M8aYl7ubbBg%3D&Expires=1773717147' alt='OCR图片'/></div>

## Shortest-Job-First (Non- Preemptive) Scheduling

<table border="1"><tr><td>Process</td><td>Burst Time(ms)</td></tr><tr><td>P1</td><td>6</td></tr><tr><td>P2</td><td>8</td></tr><tr><td>P3</td><td>7</td></tr><tr><td>P4</td><td>3</td></tr></table>

Waiting time for processes;

- P1 = 3ms

- P2 = 16ms

- P3=9ms

- P4 = 0 ms

Average waiting time = (3+16+ 9+0) / 4=7ms

Suppose that the processes arrive at the same time.

The Gantt Chart for the schedule is:

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347241.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=LIUbHCwZ8jguXiaTLVTYUlO0V2I%3D&Expires=1773717147' alt='OCR图片'/></div>

Turnaround time for processes;

- P1=9ms

- P2=24ms

- P3 = 16ms

- P4 = 3 ms

Average Turnaround time = (9+24+16 +3) / 4=13ms

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347248.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=kMIn3oZZUgW0hAMTyLY6TebZI8Q%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_3_1773112347255.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=W4xE9NrmkpGZEVEKqF6kPrAw6Nc%3D&Expires=1773717147' alt='OCR图片'/></div>

## Shortest-Job-First (Preemptive) Scheduling

<table border="1"><tr><td>Process</td><td>Arrival Time(ms)</td><td>Burst Time(ms)</td></tr><tr><td>P1</td><td>0</td><td>8</td></tr><tr><td>P2</td><td>1</td><td>4</td></tr><tr><td>P3</td><td>2</td><td>9</td></tr><tr><td>P4</td><td>3</td><td>5</td></tr></table>

Waiting time for processes;

- P1 = (0-0) + (10-1) = 9ms

- P2 = (1-1) = 0ms

- P3 = (17-2) = 15ms

- P4 = (5-3) = 2ms

Average waiting time = (9+0+15+ 2) / 4=6.5ms

This is known as Shortest-remaining-time-first scheduling. Suppose that the processes arrive at different timeslots.

The Gantt Chart for the schedule is:

<table border="1"><tr><td>$P_{1}$</td><td>$P_{2}$</td><td>$P_{4}$</td><td>$P_{1}$</td><td>$P_{3}$</td></tr><tr><td>0</td><td>1</td><td>5</td><td>10</td><td>17</td><td>26</td></tr></table>

Turnaround time for processes;

- P1 = 17ms

- P2 = (5-1) = 4ms

- P3 = (26-2) = 24ms

- P4 = (10-3) = 7 ms

Average Turnaround time =

$$
(1 7 + 4 + 2 4 + 7) / 4 = 1 3 \mathrm {m s}
$$

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347262.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=onVWJaoE94vMoek6yIXjd1P3Mh0%3D&Expires=1773717147' alt='OCR图片'/></div>

## Priority Scheduling

- A priority number (integer) is associated with each process

- The CPU is allocated to the process with the highest priority (smallest integer $ \equiv $ highest priority)

- This may be preemptive or non- preemptive.

- The low priority processes may never execute. This is known as Starvation

- As a solution to this problem, the priority increases with the time. It is known as Aging.

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347272.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=rCoLRdZBcOG8V6g6Ayf8L6LTdwo%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347280.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=xo66YRxmoKU%2F9ONGNrdfpiLHOMY%3D&Expires=1773717147' alt='OCR图片'/></div>

## Priority Scheduling

<table border="1"><tr><td>Process</td><td>Burst Time(ms)</td><td>Priority</td></tr><tr><td>P1</td><td>10</td><td>3</td></tr><tr><td>P2</td><td>1</td><td>1</td></tr><tr><td>P3</td><td>2</td><td>4</td></tr><tr><td>P4</td><td>1</td><td>5</td></tr><tr><td>P5</td><td>5</td><td>2</td></tr></table>

- Priority scheduling Gantt Chart

<table border="1"><tr><td>$P_{2}$</td><td>$P_{5}$</td><td>$P_{1}$</td><td>$P_{3}$</td><td>$P_{4}$</td></tr><tr><td>0</td><td>1</td><td>6</td><td>16</td><td>1819</td></tr></table>

Waiting time for processes;

- P1=6ms

- P2=0ms

- P3=16ms

- P4 = 18ms

- P5=1ms

Average waiting time: (6+0+16+18+1) / 5=8.2ms

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347285.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=85oFH%2F%2Fym6%2FwyP%2FDVzPVtDfARQY%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347294.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=u%2BpW1pr6sbMUA4rSiUTcdpqBSEM%3D&Expires=1773717147' alt='OCR图片'/></div>

## Round Robin (RR)

- Each process gets a small unit of CPU time (time quantum q), usually 10-100 ms. After this time has elapsed, the process is preempted and added to the end of the ready queue.

- The Timer interrupts every quantum to schedule next process

- If there are n processes in the ready queue and the time quantum is q, then each process gets 1/n of the CPU time in chunks of at most q time units at once. No process waits more than (n-1)q time units.

- Assume there are 4 processes and the time quantum is 10 ms, then each process gets 1/4 of the CPU and runs at most 10 ms per turn. The maximum waiting time before a process gets the CPU again $ ( 41)\times1 0 \mathrm{~ms}=3 0 \mathrm{~ms} $

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347303.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=YKDYTWAawas9MDEhUEM7Otvzt%2BA%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347328.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=cXYUjBjEFK6Iu%2FnMDcnFOdu5vRI%3D&Expires=1773717147' alt='OCR图片'/></div>

## Round Robin (RR) with quantum (q) = 4

<table border="1"><tr><td>Process</td><td>Burst Time(ms)</td></tr><tr><td>P1</td><td>24</td></tr><tr><td>P2</td><td>3</td></tr><tr><td>P3</td><td>3</td></tr></table>

- The Gantt chart is:

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347333.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=Fho7hXyw5V5DV1koxLslwxuLjNg%3D&Expires=1773717147' alt='OCR图片'/></div>

Waiting time of processes;

- P1 = (10-4) = 6ms

- P2=0ms

- P3=0ms

Average waiting time: (6+0+0) /3=2ms

Turnaround time of processes

- P1=30ms

- P2=7ms

- P3 = 10ms

Average turnaround time = (30+7+10)/3=15.67ms

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347339.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=B0186Q5gwK%2BAQnaKxEAjHq8oYD8%3D&Expires=1773717147' alt='OCR图片'/></div>

## Time Quantum and Context Switch Time

- q should be large compared to context switch time

- Performance

- q large $ \Rightarrow $ FIFO

- q small $ \Rightarrow $ q must be large with respect to context switch, otherwise overhead is too high

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347352.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=LdPFrT%2FgxBSef1Y%2Fj6SVhazq%2B28%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347382.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=mkLjex6aq4IefniZ%2FaiWCFdl3mo%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_3_1773112347391.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=9QRNsFOxx8VCs9fSnyqDcnjAmr4%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_4_1773112347408.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=sYZWHLN0%2F5CR8wSfswrY%2BH9YrvM%3D&Expires=1773717147' alt='OCR图片'/></div>

## Multilevel Queue

- Ready queue is partitioned into separate queues

- foreground

- background

- Each queue has its own scheduling algorithm:

- foreground - RR

- background - FCFS

- Processes are permanently in a given queue and

- Scheduling must be done between the queues:

- Fixed priority scheduling; (i.e., serve all from foreground then from background). Possibility of starvation.

- Time slice - each queue gets a certain amount of CPU time which it can schedule amongst its processes; i.e., 80% to foreground in RR, 20% to background in FCFS

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347417.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=5n7p%2BZnEGib%2FyXVKxAeJxXd%2BfqE%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347488.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=e9wEWNRfj06jQSKc5%2BfNoLDadAU%3D&Expires=1773717147' alt='OCR图片'/></div>

## Multilevel Feedback Queue

- A process can move between the various queues; aging can be implemented this way

- Multilevel-feedback-queue scheduler defined by the following parameters:

- number of queues

- scheduling algorithms for each queue

- method used to determine when to upgrade a process

- method used to determine when to demote a process

- method used to determine which queue a process will enter when that process needs service

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347494.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=0dvkL0M0Wbxa9S1eRABpMySzZNU%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347500.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=ChsYni%2BCBTlhEA%2B%2B8ZLwiiq9YBI%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_3_1773112347508.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=PrwPVsHQSqeV3cz53k5Nh5QKF3c%3D&Expires=1773717147' alt='OCR图片'/></div>

## CPU Scheduling Algorithm Evaluation

There are four evaluation methods.

- Deterministic evaluation

- Queueing Models

- Simulations

- Implementation

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347517.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=m6UoI93AXe5yHqwfIVnUCSmo4eA%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347522.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=xohGPRtGsxdHSbEgE5AhuyJ0XxY%3D&Expires=1773717147' alt='OCR图片'/></div>

## Deterministic Evaluation

- This is a type of analytic evaluation. It takes a particular predetermined workload and defines the performance of each algorithm for that workload.

- This is the simplest and fastest, but requires exact numbers for input, applies only to those inputs

- Consider 5 processes arriving at time 0: For each algorithm, calculate minimum average waiting time

- FCS is 28ms:

- Non-preemptive SFJ is 13ms:

<table border="1"><tr><td colspan="2">P1</td><td colspan="4">P2</td><td>P3</td><td>P4</td><td>P5</td></tr><tr><td colspan="2">0</td><td colspan="4">10</td><td>39</td><td>42</td><td>49</td><td>61</td></tr><tr><td>P3</td><td>P4</td><td colspan="2">P1</td><td colspan="2">P5</td><td colspan="4">P2</td></tr><tr><td colspan="2">0</td><td>3</td><td colspan="2">10</td><td colspan="2">20</td><td colspan="4">32</td><td>61</td></tr><tr><td colspan="2">P1</td><td colspan="2">P2</td><td colspan="2">P3</td><td colspan="2">P4</td><td colspan="2">P5</td><td>P2</td><td>P5</td><td>P2</td></tr><tr><td colspan="2">0</td><td colspan="2">10</td><td colspan="2">20</td><td colspan="2">23</td><td colspan="2">30</td><td>40</td><td>50</td><td>52</td><td>61</td></tr></table>

- RR is 23ms:

<table border="1"><tr><td>Process</td><td>Burst Time</td></tr><tr><td>$P_{1}$</td><td>10</td></tr><tr><td>$P_{2}$</td><td>29</td></tr><tr><td>$P_{3}$</td><td>3</td></tr><tr><td>$P_{4}$</td><td>7</td></tr><tr><td>$P_{5}$</td><td>12</td></tr></table>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_1_1773112347530.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=9zjyFqgKXcw9AIfhB7aFpm6qbA8%3D&Expires=1773717147' alt='OCR图片'/></div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F202603101112105690120b69934023%2Fcrop_2_1773112347537.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=9t%2F%2FHkJxAMom9vOhky4xTKGJKVA%3D&Expires=1773717147' alt='OCR图片'/></div>

## Queueing Models

- This computation is doing by little's law. Little's law - in steady state, processes leaving queue must equal processes arriving.

n = $ \lambda $ x W(n = average queue length, W = average waiting time in queue, $ \lambda $ = average arrival rate into queue)

- If on average 7 processes arrive per second, and normally 14 processes in queue, then average wait time per process = 2 seconds
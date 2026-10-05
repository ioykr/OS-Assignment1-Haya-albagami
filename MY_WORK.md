# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Haya ayed albagami |
| **Student ID** | 446051371 |
| **University Email** | 446051371@std.psau.edu.sa |
| **GitHub Username** | ioykr|
| **Repository Link** | https://github.com/ioykr/OS-Assignment1-Haya-albagami.git |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/12bZd7VnnZyh4FDRhfRvoDf5wPbKLzI7D/view?usp=drivesdk

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [october,3,2026,10:30pm]
**What I did**:
I began by reading the assignment instructions and checking the original Java code
**Details**:
I studied the `Process` and `SchedulerSimulation` classes to understand how the application works. I also reviewed Round-Robin scheduling and how the ready queue stores threads. After setting my student ID,
I ran the original simulation and checked the output.
**Challenges**:
When a process returns to the ready queue the application generates a new thread, which initially baffled me
**Solution**:
I went from addProcessToQueue() to currentThread.start() and currentThread.join(). This helped me grasp how each round execution works
**Time spent**:
2 hours
---

### Entry 2 - [4 october,2026,12:40am]
**What I did**:
I worked on adding the process priority feature.
**Details**:
I added a priority field to the `Process` class and used the seeded random generator to assign values from 1 to 10. I also added methods to read and set the priority and updated the ready queue message to display it. 
**Challenges**:
I wasn't sure if adding priority required me to alter the sequence of the schedule
**Solution**:
I realized that priority was only required for display after reviewing the instructions once more. I kept the FIFO order unchanged
**Time spent**:
2 hours
---

### Entry 3 - [4 october,2026,6:00am]
**What I did**:
I added the context switch counter
**Details**:
I declared a static counter in the `SchedulerSimulation` class. I incremented it before `currentThread.start()` and added a message to display the final total.
**Challenges**:
When I first put the static variable within the main() method, Java compilation failed
**Solution**:
I maintained the variable inside the SchedulerSimulation class and relocated it outside of main()
**Time spent**:
5 hours
---

### Entry 4 - [4 october,2026,2:00pm]
**What I did**:
I started tracking wait times and turnaround times
**Details**:
In order to monitor process creation time, ready queue entrance time, and overall waiting time, I created variables. I used System.currentTimeMillis() to calculate how long each process waited in the ready queue.
I also saved references to each process so I could print the final statistics table.
**Challenges**:
Understanding how to compute waiting time while a process repeatedly enters the ready queue proved challenging
**Solution**:
Every time a process was added, I noted the queue entrance time, and when the scheduler chose it, I updated the process's overall waiting time.
**Time spent**:
5 hours
---

### Entry 5 - [4 october,2026,7:30pm]
**What I did**:
I examined the finished code and verified the results of the simulation
**Details**:
I looked at the final waiting table, the FIFO order, the context switch counter, and the priority values. I also looked over the comments for each feature

**Challenges**:
In the VS Code terminal a few characters and symbols were displayed incorrectly
**Solution**:
I looked into the display issue by testing the UTF-8 encoding settings in PowerShell and Java. Additionally, I verified that the problem was with character display rather than scheduling computations.
**Time spent**:
2 hours
---

### Entry 6 - [Optional - Date and Time]
Not used. 

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [16 hours]

**Most challenging part**:
Implementing waiting time tracking proved to be the most difficult task because processes can repeatedly return to the ready queue. I had to know when to begin and end the waiting time measurement

**Most interesting learning**:
I thought it was fascinating to see how Java threads can be utilized to mimic CPU execution and how Round-Robin scheduling provides each process a turn
**What I would do differently next time**:
Next time, I would test every small change before adding another feature. I would also review the original code carefully before deciding where to add new variables and methods.
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

Before this assignment, I knew what a thread was, but I did not fully understand how Java uses it. I learned that the `Process` class implements `Runnable` and defines the work inside `run()`.
The scheduler creates a Java thread to execute a simulated process. Calling `start()` begins execution, while `join()` makes the main thread wait for that turn to finish. 
I saw how `Thread.sleep()` simulates CPU time during a quantum. This assignment helped me understand how threads and scheduling work together.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

Tracking waiting time was the hardest part for me. At first, I thought I only needed to record each process's creation and completion times.
Then I realized that unfinished processes can return to the ready queue several times. Each return creates another waiting period for the same process. 
I had to add these periods together without including execution time. This took more effort to understand than the priority feature or the context-switch counter.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I reread the original code and followed each process through the ready queue. I checked when a process entered the queue and when the scheduler selected it. 
I used `System.currentTimeMillis()` to measure the waiting time between these two points. I also fixed a compilation error after realizing that a static field should be declared outside `main()`.
When some terminal symbols appeared incorrectly, I tested the encoding settings. Running the simulation and checking its results helped me confirm my changes.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful when an application needs to handle different tasks without becoming unresponsive.
For example, a web browser can load a page while the user interacts with other parts of it. Games also use threads for tasks such as audio, input, and background work. 
Operating systems schedule runnable threads to share CPU time. Round-Robin is one scheduling approach that gives each ready task a limited turn. 
This assignment helped me understand why scheduling and coordination between threads matter.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]
I'm interested in learning how operating systems schedule threads on multicore processors. I also want to understand race conditions and how threads safely share data.
### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]
Creating threads and comprehending the ready queue are two basic concepts that I feel more comfortable with. I still need to learn synchronization and more sophisticated scheduling techniques

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]
The assignment was useful because it connected Java code with CPU scheduling. Although tracking waiting time was challenging, it helped me understand Round-Robin scheduling better.
---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A thread is a unit of execution within a process, while a process is a running program with its own resources. Separate processes usually have separate address spaces, but threads in one process can share memory. Creating threads and communicating between them is generally less expensive than doing the same with separate processes. In this assignment, the `Process` class represents a simulated process, not a separate operating-system process. The `addProcessToQueue()` method uses `new Thread(process)` to execute that simulation inside the same Java application.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, a process that does not finish within its time quantum returns to the end of the ready queue. In my simulation, P4 had a burst time of 10504ms and the time quantum was 5000ms. 
After its first turn, P4 had 5504ms left, and after its second turn, it had 504ms left. P4 was re-queued two times and finished on its third turn. 
Re-queueing is important for fairness because other ready processes get CPU time instead of waiting for P4 to finish all at once.

Example from my output:
```
  ➕ P4 added to ready queue │ Priority: 1 │ Burst time: 10504ms

...

  ▶ P4 executing quantum [5000ms]
     Remaining time: 5504ms
  ↻ P4 yields CPU for context switch

  ➕ P4 added to ready queue │ Priority: 1 │ Burst time: 10504ms

...

  ▶ P4 executing quantum [5000ms]
     Remaining time: 504ms
  ↻ P4 yields CPU for context switch

  ➕ P4 added to ready queue │ Priority: 1 │ Burst time: 10504ms

...

  ▶ P4 executing quantum [504ms]
     Remaining time: 0ms
  ✓ P4 finished execution!
```

**Explanation of example:**
P4 entered the ready queue three times in total, including its first entry. The two extra entries happened after the first and second CPU turns because P4 still had remaining burst time.
It finished on its third turn without being re-queued again.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New:** P1 enters the New state when `new Thread(process)` creates its thread inside `addProcessToQueue()`.
2. **Runnable:** P1 becomes Runnable when the scheduler calls `currentThread.start()`.
3. **Running:** The JVM begins executing P1's `run()` method during its CPU turn, although Java includes running threads in the `RUNNABLE` state.
4. **Waiting:** P1's thread enters `TIMED_WAITING` during `Thread.sleep(stepTime)`, while the main thread enters `WAITING` when it calls `currentThread.join()`.
5. **Terminated:** P1's current thread terminates when `run()` finishes, and the scheduler creates a new thread if the simulated process still needs another quantum.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduling]

**Description**:
An operating system scheduler handles runnable threads from multiple programs, such as a browser and a text editor. Each runnable thread receives a limited time quantum when Round-Robin scheduling is used.

**Why Round-Robin works well here**:
When a quantum ends, the scheduler can perform a context switch to another ready thread. Unfinished threads return to the ready queue for another turn. This supports fairness and responsiveness because one busy thread cannot keep the CPU indefinitely.

### Example 2: [background Task Processing]

**Description**:
A background task manager may process files and prepare reports for several users. These tasks can be divided into smaller pieces of work.

**Why Round-Robin works well here**:
A Round-Robin worker scheduler could give each task a short turn before switching to the next one. This resembles my simulation because unfinished tasks return to the ready queue while context switches allow other tasks to proceed. It helps prevent long tasks from delaying all the shorter ones.

## Summary

**Key concepts I understood through these questions:**
1. I gained knowledge about the distinction between a simulated process and an actual Java thread, as well as the creation and management of threads.
2. I comprehended how Round-Robin scheduling distributes CPU time equitably using a time quantum and FIFO ready queue.
3. I discovered that scheduling allows for the tracking of waiting times, turnaround times, and context switches.


**Concepts I need to study more:**
1. Race conditions and thread synchronization.
2. How threads are scheduled across several CPU cores in actual operating systems

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

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
| **Full Name** | Shatha ali saqr |
| **Student ID** | 445052012 |
| **University Email** | 445052012@std.psau.edu.sa |
| **GitHub Username** | shathathv |
| **Repository Link** | https://github.com/shathathv/OS-Assignment1-Shatha-Ali-Saqr |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1GRRXE6DD6qWUJAulcFwQ_0nwdber_Dmo/view?usp=sharing
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

### Entry 1 - [September 22, 2026,5:00 PM]
**What I did:** Set up the assignment repository and prepared the Java project.

**Details:**
- Forked the starter repository and worked on my own assignment repository.
- Updated the student ID in `SchedulerSimulation.java`.
- Opened the project in VS Code and read the starter code to understand the main classes and scheduling flow.
- Ran the program to check that the original simulation worked before making the required changes.

**Challenges:**
Understanding the existing scheduler code and how the processes and threads were connected.

**Solution:**
I read the code step by step and ran the program so I could compare the code with the output.

**Time spent:** 20 minutes

---

### Entry 2 - [September 25, 2026,6:10 PM]
**What I did:** Added the process priority feature.

**Details:**
- Added a priority value for each process.
- The priority is randomly generated from 1 to 10, where 10 is the highest priority.
- Displayed the priority when the process enters the ready queue.
- Kept the ready queue behavior FIFO because the priority is only displayed and does not change the scheduling order.
- Ran the program and checked that the processes were displayed with priority values.

**Challenges:**
I needed to make sure that adding priority did not change the Round-Robin scheduling behavior.

**Solution:**
I kept the priority as a display-only property and tested the program after making the change.

**Time spent:** 30 minutes

---

### Entry 3 - [September 26, 2026, 2:00 PM]
**What I did:** Added the context switch counter.

**Details:**
- Added a static counter to track context switches.
- Incremented the counter when a new process starts running.
- Added the total number of context switches to the final output.
- Ran the simulation and checked the final result.
- The program showed a total of 29 context switches in my test run.

**Challenges:**
I needed to place the counter update in the correct part of the scheduling process so that it counted each new process execution.

**Solution:**
I followed the point where the scheduler starts a process thread and then tested the final counter using the program output.

**Time spent:** 46 minutes

---

### Entry 4 - [September 27, 2026, 4:00 PM]
**What I did:** Added waiting time tracking and turnaround time calculation.

**Details:**
- Used `System.currentTimeMillis()` to track how long a process waited in the ready queue.
- Updated the process waiting time when it was selected to run again.
- Added the final process table with Process Name, Burst Time, Waiting Time, and Turnaround Time.
- Calculated turnaround time using waiting time plus burst time.
- Ran the program and checked the waiting and turnaround time values.

**Challenges:**
The waiting time had to be measured from the time the process entered the queue until it was selected to run.

**Solution:**
I used the process queue entry time together with `System.currentTimeMillis()` and added the elapsed time to the process waiting time.

**Time spent:** 20 minutes

---

### Entry 5 - [September 28, 2026, 6:30 PM]
**What I did:** Tested the complete program and reviewed the assignment files.

**Details:**
- Ran the complete scheduler after implementing the required features.
- Checked that all processes completed successfully.
- Verified the final process table and context switch count.
- Reviewed `MY_WORK.md` and filled in my student information and repository link.
- Checked the Git history and pushed my latest changes to GitHub.

**Challenges:**
I had to check that the new features worked together without breaking the original scheduling simulation.

**Solution:**
I ran the complete program several times and reviewed the output, including the final process table and context switch count.

**Time spent:** 30 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: Approximately 5 hours

**Most challenging part**: Understanding the existing scheduler code and adding the new features without changing the Round-Robin behavior.

**Most interesting learning**: I learned how threads can be used to simulate processes and how the ready queue controls the order in which processes get CPU time.

**What I would do differently next time**: I would read and organize the existing code earlier and test each feature separately immediately after adding it.

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

I learned that multithreading allows different tasks to run as separate threads in a program. In this assignment, each process uses a thread to simulate its execution on the CPU. I learned that Thread.start() starts the thread, while Thread.join() makes the main scheduler wait for the thread to finish its current execution. I also understood how Thread.sleep() can be used to simulate the time spent by a process running. The Round-Robin scheduler gives each process a time quantum and then allows another process to run. I also learned that the ready queue and thread execution must work together to simulate the scheduling process.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part was understanding the existing scheduler code before adding the new features. The code already had several methods for creating processes, adding them to the ready queue, and running their threads. I found it difficult at first to know exactly where to add the context switch counter and waiting time calculation. I also had to make sure that adding the new features did not change the original Round-Robin behavior. Running the program several times helped me understand the relationship between the queue and the threads. After testing the changes, I was able to see the expected final process table and context switch count.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame the challenges by reading the SchedulerSimulation.java code carefully and testing the program after making small changes. I also used the README instructions to understand what each required feature should do. When I added the waiting time feature, I used System.currentTimeMillis() to calculate the time a process spent waiting in the queue. I checked the output after each change to make sure the values were being calculated. I also reviewed the code when I noticed anything that did not look correct and fixed it before continuing. This step-by-step testing helped me understand the code instead of only copying the required changes.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading can be used in many real-world applications where several tasks need to be handled at the same time. For example, a web browser can use different threads for loading pages, handling user input, and downloading files. A music application can use one thread to play audio while another handles user actions. The same idea is shown in this assignment because each process is represented by a thread and receives CPU time through the scheduler. Round-Robin scheduling can help give different tasks a fair opportunity to use CPU resources. Understanding these concepts can help me when developing applications that need to perform several operations without making the whole application wait.
### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

In this assignment, a process is simulated by the `Process` class, while a thread is the real Java thread that runs that process. A process has its own information such as burst time, remaining time, and priority, while threads are used to execute the simulated processes. Threads are lighter to create than separate processes and can share memory within the same program, which makes communication easier. In the code, the simulated process is passed to `new Thread(process)` inside `addProcessToQueue()`, and then the thread is started to run the process.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

When P2 does not finish within its 4000ms time quantum, it yields the CPU and is added back to the ready queue. P2 has a burst time of 9445ms, so it was re-queued two times before it finished. After the first two 4000ms quanta, P2 had 1445ms remaining and then completed its final quantum. Re-queuing allows other processes to use the CPU instead of allowing P2 to keep running until completion, which makes the Round-Robin scheduling fair.

Example from my output:
```
P2 executing quantum [4000ms]
P2 completed quantum 4000ms
Remaining time: 1445ms
P2 yields CPU for context switch

P2 added to ready queue
Burst time: 9445 | Priority: 4

P2 executing quantum [1445ms]
P2 completed quantum 1445ms
Remaining time: 0ms
P2 finished execution!
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. 1. New: P1 is in the New state when its thread is created in addProcessToQueue() using new Thread(process), but it has not started yet.
2. Runnable: P1 becomes Runnable when Thread.start() is called by the scheduler, which makes the thread ready to be executed.
3. Running: P1 is Running when its thread is executing the run() method and using its assigned CPU time quantum.
4. Waiting: During Thread.sleep() inside run(), P1's thread temporarily waits while simulating its execution, while the main scheduler thread can wait on Thread.join() for the thread to finish its quantum.
5. Terminated: P1 becomes Terminated after its run() method finishes and the thread completes its execution.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling in an Operating System

**Description**:
An operating system can use Round-Robin scheduling to share CPU time between multiple running programs. Each process receives a fixed time quantum and then the CPU can be given to another process. This is similar to my simulation, where each process is represented by a thread and the scheduler controls how long it runs.

**Why Round-Robin works well here**:
Round-Robin is useful because it gives each process a fair opportunity to use the CPU. Context switches allow the scheduler to move from one process to another when its time quantum ends. This improves responsiveness because one process cannot keep the CPU for an unlimited amount of time.

### Example 2: Web Browser

**Description**:
A web browser can perform several tasks at the same time, such as loading a web page, handling user input, and downloading files. These tasks can be handled by different threads so that one task does not block the whole application. This is related to my simulation because different threads receive CPU time to perform their work.

**Why Round-Robin works well here**:
Round-Robin can help keep different tasks responsive by giving each task a limited amount of CPU time. The time quantum is similar to the fixed execution time given to a process in my simulation. A context switch allows another task to run after the current task gives up the CPU.

## Summary

**Key concepts I understood through these questions:**
1. The difference between a thread and a process.
2. How Round-Robin scheduling uses a time quantum and ready queue.
3. How thread lifecycle states and context switches work.

**Concepts I need to study more:**
1. Thread synchronization and communication between threads.
2. More advanced CPU scheduling algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [x] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [x] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [x] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

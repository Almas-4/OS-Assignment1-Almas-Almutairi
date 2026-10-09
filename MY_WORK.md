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
| **Full Name** | [Almas Abdullah AlMutairi] |
| **Student ID** | [446051602] |
| **University Email** | [446051602]@std.psau.edu.sa |
| **GitHub Username** | [Almas-4] |
| **Repository Link** | [https://github.com/Almas-4/OS-Assignment1-Almas-Almutairi] |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1hDLnQ7w2UvSnMhAYC2ziyPVQoJj_P0lr/view?usp=drivesdk

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

### Entry 1 - [September 22, 2026, 2:30 PM
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

### Entry 1 - September 26, 2026 — 6:00 PM
**What I did**:Added my Student ID to the project and log in github.

**Details**:I updated the required student information and checked that it was saved correctly.

**Challenges**:Making sure the information was entered in the correct place.

**Solution**:I checked the README requirements and verified the changes.

**Time spent**: 2 hours

---

### Entry 2 -September 28, 2026 — 6:00 PM
**What I did**:Understood the existing code and project structure.

**Details**:To comprehend how the processes, threads, scheduler, and ready queue operate, I read the README and went over the primary Java classes.

**Challenges**:recognising the connections between the various classes.

**Solution**:I followed the code step by step and ran the program to understand its output.

**Time spent**: 2 hours

---

### Entry 3 - October 4, 2026 — 5:00 PM
**What I did**:Worked on Feature 1.

**Details**:I added the required priority information to the Process class and checked that it worked with the existing code.

**Challenges**:knowing where the priority should be added without interfering with other program components.

**Solution**:I tried the application after making the modifications while adhering to the current class structure.

**Time spent**: 3 hours

---

### Entry 4 - October 5, 2026 — 4:00 PM
**What I did**:Worked on Feature 2.

**Details**:I implemented the context switch counter and checked how context switches happen during scheduling.

**Challenges**:determining the appropriate time to count a context switch.

**Solution**: I monitored the scheduler's operation and used the program output to test the counter.

**Time spent**: 2 hours

---

### Entry 5 - October 5, 2026 — 6:30 PM
**What I did**:Worked on Feature 3.

**Details**:I implemented the waiting time tracking and checked the final scheduler summary.

**Challenges**:Understanding how the waiting time of a process varies upon its return to the ready queue. 

**Solution**: I used the scheduler to test the waiting time calculation and tracked the process execution.

**Time spent**:2.5 hours

---

### Entry 6 -October 6, 2026 — 5:30 PM
**What I did**:Tested the completed features and worked on the documentation.

**Details**:I verified the three features' output after running the application once again. I also began finishing the technical responses, reflection, and development log.

**Challenges**:ensuring that the documentation and final product met the requirements of the assignment.

**Solution**:I verified the code and output, went over the README, and filled in any blanks.

**Time spent**: 2 hours

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 14 hours

**Most challenging part**: Feature 3 was the most challenging because I had to understand how waiting time changes when processes return to the ready queue

**Most interesting learning**:I found it interesting to see how Java threads can be used to simulate processes and how Round-Robin scheduling manages them.

**What I would do differently next time**:I would begin testing every feature sooner and continue to

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

[Write your answer hereI discovered that a program can have several threads operating separately. I discovered how to define a job using Runnable and how to start a thread using Thread.start(). Additionally, I discovered that Thread.sleep() can temporarily mimic a process that uses the CPU. One thread can wait for another to finish by using Thread.join(). By seeing multithreading in action in real code, this assignment improved my understanding of it.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Feature 3 and figuring out the waiting time were the hardest parts. Because processes can use their time quantum and then return to the ready queue, it proved challenging. I had to comprehend the transition between waiting and running. I also have to comprehend the relationship between the process and its thread. I was able to comprehend the issue by carefully testing the scheduler.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[In order to comprehend the requirements, I first looked over the README and the current code. I tracked each process's progress by following the scheduler step-by-step. After making a few minor adjustments, I tried the application. When I discovered an issue, I looked at the program's output and code to determine what was causing it. I was able to resolve the problems and gain a better understanding of the implementation thanks to this.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[When an application must manage several tasks concurrently, multithreading is helpful. A web browser, for instance, can employ threads to load pages while still interacting with the user. A thread can be used by a music player to play music while the user utilises other functions. Threads can also be used in games for things like user input and game logic. These illustrations made it easier for me to understand how the threading ideas covered in this assignment can be applied in practical settings.]

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

[While threads are tiny execution units that share a process's memory, processes are separate programs with their own memory. While threads are quicker and easier to communicate with, processes often have more creation and communication overhead. This assignment uses a real Java thread to run the Process class, which is only a simulated process. The Java thread that executes the simulated process is created by the line new Thread(process) in addProcessToQueue().]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process does not finish within its time quantum, it is placed back into the ready queue to wait for another turn. In my output, P6 has a burst time of 11850ms and the time quantum is 5000ms, so P6 was re-queued 2 times before it finished. The first 5000ms left 6850ms, and the second 5000ms left 1850ms. P6 then used its final 1850ms and finished execution. This behavior is important because re-queuing gives other processes a chance to use the CPU and makes the Round-Robin scheduler fair.]

Example from my output:
```

Example from my actual output:

P6 completed quantum 5000ms
Remaining time: 6850ms
P6 yields CPU for context switch

P6 added to ready queue
Burst time: 11850ms

P6 completed quantum 5000ms
Remaining time: 1850ms
P6 yields CPU for context switch

P6 added to ready queue
Burst time: 11850ms

P6 executing quantum [1850ms]
P6 finished execution!

This shows that P6 returned to the ready queue twice before using its remaining 1850ms to finish.
```

**Explanation of example:**
[P6 uses its 5000 ms time quantum first, but it doesn't finish because there are still 6850 ms left. After that, it is put back in the ready queue so that the CPU can be used by other programs. P6 gets re-queued after using an additional 5000 ms on its second turn and having 1850 ms left. P6 completes execution after running for the final 1850 milliseconds. This demonstrates how each process is given an equal chance by the Round-Robin scheduler.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when the thread is created with new Thread(process) inside addProcessToQueue() but before start() is called.]

2. **Runnable**: [P1 is running when its run() method executes and Thread.sleep() is used to simulate its CPU time.]

3. **Running**: [P1 is Running when its run() method is executing and the output shows P1 executing quantum [5000ms].]

4. **Waiting**: [Thread in P1 goes into TIMED_WAITING.While the main thread can enter WAITING when it calls Thread, sleep() is called to mimic CPU execution.join() to await P1's completion]

5. **Terminated**: [When P1's run() method completes, it enters the Terminated state, as indicated by P1 ended execution!.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling in an Operating System]

**Description**:
[Round-Robin scheduling allows an operating system to distribute CPU time among several active programs. In the simulation, every running application functions as a process, and the time quantum allots a finite amount of CPU time to each process. The OS switches context and transfers the CPU to the next process that is ready when the quantum expires]

**Why Round-Robin works well here**:
[Rather of having one process use the CPU continually, Round-Robin ensures fairness by giving each ready process a turn. Because programs don't have to wait as long to receive CPU time, it also enhances responsiveness. Processes like P6 are re-added to the ready queue after utilising their 5000ms quantum in my simulation, which is comparable to this.]

### Example 2: [Web Server Handling Multiple Requests]

**Description**:
[Several threads can be used by a web server to simultaneously process requests from several users. A time quantum restricts how long a task can utilise the CPU before another task has a turn, and each request can be regarded as a task. The server can transition between jobs thanks to a context switch.]

**Why Round-Robin works well here**:
[Round-Robin can avoid all other requests from being delayed by a single, lengthy task and offer equitable CPU access. Because every request is given the opportunity to be processed on a regular basis, it also increases responsiveness. Because incomplete tasks are put back in the ready queue and given another turn later, this is comparable to the simulation.]

## Summary

**Key concepts I understood through these questions:**
1.How Round-Robin scheduling equitably distributes CPU time among tasks.
2.Java threads' progression through various lifetime stages.
3.How the ready queue and context switching operate.

**Concepts I need to study more:**
1.communication and synchronisation of threads.
2.the distinctions between threads and processes in actual operating systems.

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

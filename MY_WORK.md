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
| **Full Name** | [Deem Omar Alroies] |
| **Student ID** | [446051752] |
| **University Email** | [446051752]@std.psau.edu.sa |
| **GitHub Username** | [Deem277] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [6/10 ]
**What I did**: Set up my GitHub repository and personalized the project.

**Details**: I forked the starter repository, renamed it, cloned it into VS Code, and changed the student ID

**Challenges**: I had difficulty getting the Java program to show output in VS Code.

**Solution**: I checked the Java configuration, tried different JDK settings, and reviewed the project setup.

**Time spent**: 30 minutes

---

### Entry 2 - [7/10]
**What I did**: Added process priority.

**Details**: I added a priority variable to the Process class and generated a random priority between 1 and 10. I also displayed the priority when a process entered the ready queue.

**Challenges**: No major issues

**Solution**:

**Time spent**: 30 minutes

---

### Entry 3 - [9/10]
**What I did**: Added the context switch counter.

**Details**:  I added a static counter and increased it whenever a process started running. I displayed the total at the end of the simulation.


**Challenges**: I needed to find the correct place to increase the counter without changing how the scheduler works.

**Solution**: I added contextSwitchCount++ before currentThread.start(). Then I ran the program and checked that the total appeared at the end.

**Time spent**: 1 hour

---

### Entry 4 - [10/10]
**What I did**: Added the Waiting Time Tracking feature.


**Details**: I used System.currentTimeMillis() to calculate waiting time. I added methods to start and stop waiting time tracking and displayed a final summary with burst time, waiting time, and turnaround time

**Challenges**:  This feature was harder because I needed to add code in different parts of the program. I was also not sure where to add the processes to the allProcesses list.

**Solution**: I added each process to the list after creating it in the for loop. I also used startWaiting() and stopWaiting() to track waiting time. Then I used a simple for loop to display the final results.

**Time spent**: 2 hour

---

### Entry 5 - [10/10]
**What I did**: Reviewed the program and completed the documentation.

**Details**: I tested the three features and reviewed the output. I worked on the reflection and technical questions in MY_WORK.md.

**Challenges**: I needed to make sure the answers were related to my code and that I understood the changes I made.

**Solution**: I reviewed the code and the program output while writing the answers. I also checked the README instructions to make sure I included the required information.

**Time spent**: 30 minutes

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

**Total time spent on assignment**: [120 hours]

**Most challenging part**: Adding the waiting time feature. The waiting time feature needed more changes than the other two features.

**Most interesting learning**: I learned how Java threads work and how Round-Robin scheduling gives each process a turn to use the CPU. I also learned how to track waiting time and count context switches.

**What I would do differently next time**: Next time, I would test each change separately to find errors more easily.

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

I learned how to do multithreading in Java. In this assignment each simulated process is a Java thread. I found that Thread.start() starts a thread to execute. I also understood that Thread.join() makes the main thread wait until another thread is done. The Thread.sleep() method is used to simulate the time it takes for a process to run. The assignment helped me understand the working of threads and Round-Robin scheduling.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was running the Java program in VS Code. At first, I clicked Run, but the expected output did not appear. I was not sure if the problem was caused by the code or the Java configuration. I tried changing the JDK version and setting up the repository again. This took more time than I expected because I needed to check different settings. It was challenging, but it helped me learn more about configuring Java projects.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I started by checking the project setup and reviewing the README instructions. I checked the Java version and the configuration in VS Code. I also reviewed the code to make sure I was running the correct file. After working on each feature, I ran the program to check the output. I tested the priority values, context switch counter, and waiting time summary separately. Testing the code step by step helped me find problems more easily and understand my changes.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*
Multithreading is useful in applications that need to perform different tasks. For example, a web browser can load pages in threads, while keeping the interface responsive. Music application can play audio when user searches for another song. Operating systems use scheduling to allow different tasks to share CPU time. Round-Robin scheduling is a scheduling algorithm that assigns a fixed time quantum to each process and then switches to another process. This is similar to the simulation I have run where processes run one after another until they are done.[Write your answer here.]

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

A process is an independent running program . A thread is an execution unit within a process . Processes have their own memory space and threads within the same process share memory. Threads are also typically faster to create and communicate with than separate processes. SchedulerSimulation.java The Process class represents a simulated process. new Thread(process) creates a real Java thread to run the process. We used threads as a way to be able to simulate CPU scheduling without having to create separate processes inside the operating system.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

When a process does not finish within its time quantum, it goes back to the end of the ready queue. In my simulation, the time quantum is 5000 ms, and P2 has a burst time of 10757 ms. After the first execution, P2 has 5757 ms remaining, and after the second execution, it has 757 ms remaining. P2 is re-queued 2 times before it finishes on its third turn. This makes Round-Robin fair because other processes also get a chance to use the CPU.

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 starts in the New state when a thread is created using new Thread(process) inside addProcessToQueue().

2. **Runnable**: P1 enters the Runnable state when currentThread.start() is called, and it becomes ready to run.

3. **Running**:  P1 starts running when the CPU executes its run() method. It runs for a maximum of 5000 ms in one turn.

4. **Waiting**: When Thread.sleep(stepTime) is called, P1 enters the Timed Waiting state for a short time. The main thread also waits for P1 to finish using currentThread.join().

5. **Terminated**:  P1 enters the Terminated state when its run() method finishes. If P1 still has remaining time, the program creates a new thread for its next turn.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
An operating system needs to manage multiple running programs that share the CPU. For example, a user may open a browser, a text editor, and a music player at the same time. Each program needs CPU time to perform its tasks.

**Why Round-Robin works well here**:
Round-Robin gives each runnable task a fixed time quantum before moving to the next task. A context switch allows the CPU to work on another task. This helps provide fairness and responsiveness, similar to how processes take turns in my simulation.

### Example 2: [Name of application/scenario]

**Description**:
A server may receive requests from many users at the same time. It can use multiple threads to handle different requests. Some requests may need more processing time than others.

**Why Round-Robin works well here**:
A Round-Robin approach can give each ready task a turn instead of allowing one long task to use all the processing time. This can improve fairness between tasks. It is similar to my simulation, where unfinished processes return to the ready queue and wait for another turn.

## Summary

**Key concepts I understood through these questions:**
1.The difference between threads and processes.
2.How Round-Robin scheduling uses the ready queue and time quantum.
3.How Java threads are created, executed, and terminated.

**Concepts I need to study more:**
1.Thread synchronization.
2.Different CPU scheduling algorithms

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

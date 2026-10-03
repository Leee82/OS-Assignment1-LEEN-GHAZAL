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
| **Full Name** | Leen Ahmad Ghazal |
| **Student ID** | 445052798 |
| **University Email** | 445052798@std.psau.edu.sa |
| **GitHub Username** | Leee82 |
| **Repository Link** | https://github.com/Leee82/OS-Assignment1-LEEN-GHAZAL |
 
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

### Entry 1 - [September 24, 2026, 7:00pm]
**What I did**:
- had an overview of the assignment and started with the basics
**Details**:
- set up a github account with my uni email
- forked the repository and renamed it with my name
- changed my id in the schedular simulation
- made my first commit
**Challenges**:
- i didnt have a jdk installed
**Solution**:
- installed jdk
**Time spent**: 60 minutes
---

### Entry 2 - [September 26,2026, 2:30pm]
**What I did**:
- finished adding feauture 1
**Details**:
- added a priority label to the proccess class
- modifid the main class to generate a priorit number 1 through 10
- modified the output to include the priority number and added to queue
**Challenges**:
- the output wouldnt show first
**Solution**:
- i had to scroll down in the terminal to see it...
**Time spent**:
- 60 minutes
---

### Entry 3 - [September 27, 2026, 2:00pm]
**What I did**:
- added feature 2: context switching count
**Details**:
- added the static int to the schedularsmiualtion class.
- incremented it after every switch
- printed the output at the end
**Challenges**:
- an error kept coming up when intitalizing the counter
**Solution**:
- since it is static it should be put outside the main method
**Time spent**:
- 30 minutes
---

### Entry 4 - [september 27, 2026, 2:30pm]
**What I did**:
- changed the author of the commits to the correct user(IMPORTANT PLEASE READ)
**Details**:
- I did 7 commits and pushed them to the repository over the course of 3 days before noticing that the author of the commits is my username of my personal account.
- i had to change it to my university account resesting the past 7 commits to the same time. so please understand.
- the repository account is my university email from the start, the issue was with vs code author only.
**Challenges**:
- author not matching
**Solution**:
- reseting the commits with the corrrect author
**Time spent**:
- 30 minutes
---

### Entry 5 - [September 28, 2026, 10:15pm]
**What I did**:
- added feature 3
**Details**:
- intiallized the variables
- recorded each time the proccess is finished
- created an array and stored the proccess in
- designed a table summary for output
**Challenges**:
- waiting time was outputed as 0 in all processes
**Solution**:
-  called setCompletionTime() inside process method immediately when remaining time reaches 0
**Time spent**:
- 2 hours
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

**Total time spent on assignment**: [5 hours]

**Most challenging part**: implementing feature 3

**Most interesting learning**: learning how to use github correctly

**What I would do differently next time**: check the correct author for my commits way before

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

using threads is much more convenient because thread creation is more lightweight than process creation. It starts with implementing the interface runnable in my class. Then, calling the start() method in my main method to trigger the run() method. the thread.sleep method sets a specified period of time for a certain thread to move into the waiting queue. Threads take turns according to their burst times on the cpu to organize their running by different algorithms. What surprised me is how organized the thread execution is when demonstrating their exact work in the output. 



## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

the most challeging part was implementing feature 3 and it took me about 2 hours. i can say i understood what needed to be done and what to add excatly but "where" was hard. it was tough because searching for the right place in a code you didnt write yourself can be confusing. this exact method: setCompletionTime(System.currentTimeMillis()) i tried putting in 3 different places before getting the right output. Also, shaping the table to portray the outputs was kind of hard and alligning the right data in the right column with the /t.    

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

 i needed to reread the schedular simulation class again too see where i want to record the time of the thread completed firstly. i was constantly rerunning the program after each change to find what was wrong. i added a couple of print statements to see where exactly i want the table in the output is placed. i also asked for help from my father since he has a little bit of background in java. he suggested making an array to traverse through the threads nstead of writing everything manually.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is really important in real world apps like PUBG to keep the game running without lagging or freezing. just like how we created separate threads in our code, PUBG uses threads to handle player movement, sounds, and graphics all at the same time. the game gives small time slices to each task, similar to how our time quantum worked. It uses a ready queue concept to organize which task gets CPU time next so graphics don't stop the network updates. Fast context switching between processing other players and rendering the map makes everything happen in real time. lastly using multithreading lets the game run background stuff smoothly so we get a good playing experience.

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

A thread is more lightweight than a process so in this project, we used java threads because creating separate processes takes way more overhead and memory. First, threads can share memory easily, allowing us to access shared data like contextSwitchCounter and processQueue directly. Second, creating threads with new Thread(process) in addProcessToQueue() is much faster and lighter than creating whole new processes.the class named Process in our code is just a custom class we built to store process data, while the actual execution is handled by real java thread objects. Calling currentThread.start() in our loop triggers the run() method to execute each process step by step.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, when a process doesn't finish within its time quantum, it yields the CPU, gets paused, and is placed back at the end of the ready queue so other processes can get their turn.

Example from my output:
//note: this is the second time it entered the excution:

? P3 executing quantum [4000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P3 completed quantum 4000ms │ Overall progress: [███████████████████░] 97%
     Remaining time: 165ms
  ? P3 yields CPU for context switch

  ? P3 (Priority: 9 enters the ready queue...) │ Burst time: 8165ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P5 ? P6 ? P7 ? P8 ? P10 ? P11 ? P12 ? P13 ? P15 ? P16 ? P1 ? P3]
└───────────────────────────────────────────────────────────────────────────────

**Explanation of example:**

In my simulation run, P3 had a burst time of 8165ms, so it could not complete in its first 4000ms slice and was re-queued 2 times before it finally finished execution. Re-queueing is really important for fairness because it prevents a long process from taking over the CPU and guarantees that every process gets equal opportunities to run.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P3 enters the new state when we create its thread object using new Thread(process) inside the addProcessToQueue() method.

2. **Runnable**: P3 moves to the runnable state when processQueue.add(thread) puts it in line, and ready to be selected by the CPU scheduler.

3. **Running**: P3 transittions to the running state when the main scheduler loop calls currentThread.start(), which triggers P3 run() method to execute its time quantum on the CPU.

4. **Waiting**: P3 enters the waiting state when Thread.sleep(stepTime) is called inside its run(). it waits because it needs to pause its execution for a set duration to represent CPU processing time.

5. **Terminated**: P3 reaches the terminated state after its run() method completes execution and finished running.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): OS CPU Scheduling for Desktop Applications

**Description**:
An operating system uses roundrobin scheduling to run multiple applications like a web browser, a code editor, and a music player on a single CPU core. Each open app acts like a Process in our code, getting a small time slice to run before the OS performs a context switch to move to the next app.

**Why Round-Robin works well here**:
It provides fairness and high responsiveness because every application gets continuous access to the CPU. This prevents a heavy program from locking up the computer and keeps the user interface smooth and interactive.

### Example 2: Google Handling User Requests

**Description**:
A web server like google handling incoming web requests from multiple users at the same time uses roundrobin thread scheduling to process incoming traffic. each user request acts as a process, the server processing turn is the time quantum, and switching between serving different users is the context switch.

**Why Round-Robin works well here**:
it ensures fairness and predictability by preventing a huge file download from one user from blocking other users requests. Every visitor gets their request processed in order, keeping response times low and balanced across all users.

## Summary

**Key concepts I understood through these questions:**
1. How roundrobin scheduling gives every process a fair time quantum to execute on the CPU.
2. The difference between threads and processes.
3. How context switching and re-queueing keep execution fair when a process needs more CPU time.

**Concepts I need to study more:**
1. how priority values change the order of execution
2. how other scheduling techniqes work

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

# meowmeowmeowcute

<!-- Public fork: use only your GitHub username. Do not add a student ID,
Discord name, legal name, email address, or other private identifier. -->

## Environment

OS:windows 11

Editor / IDE:VSC

Shell:bash

Languages I have used:cpp,python,js,html,css,scratch(?),

## Things I have done before

- [V] SSH into another machine
- [ ] Resolve a Git merge conflict
- [V] Build a Docker image
- [ ] Read a stack trace
- [ ] Compile software from source
- [V] Use a debugger
- [ ] Use Linux as a primary development environment
- [ ] `sudo rm -rf /` a server ???!
- [ ] <others ...>

## Something I built

a so fxxking useful check list;include make a PWA for the goal that i can visit the application any where i have net.
a Moewney app;just a money keep and checking app.
always by codex lol

## Something I want to understand better

how to build a drone wareness that i can make it fly.

## Mission 01 — Linux

### Task A — find the file

Path:missions\01-linux\files\.config\nested\.deep\.treasure

Command I used:grep -R THE_PENGUIN_WAS_HERE

### Task B — count the errors

Count:8

Command I used:grep -oi "error" server.log | wc -l

(or vsc reader lol)

## Mission 03 — SSH

SSH token:FLAG{fe322c8dc745}

Command I used:ssh -i "missions\03-ssh\knock knock" flag@217.142.229.247

## Mission 04 — Debug

What was wrong:
The `the-answer` function added 1 to the base value 40, so it returned 41 instead of the expected 42.

What I changed:
I changed the addition in `the-answer` from 1 to 2, so the function now returns 42.

## Mission 05 — Docker

What was wrong:
The Dockerfile copied main.janet to /app/main.janet, but the working directory was /quest and CMD tried to run main.janet from there.

What I changed:
I changed the COPY destination to /quest/main.janet so it matches the WORKDIR and CMD path.

## Mission 06 — Improve something

What I changed:

Why:

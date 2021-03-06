# The Practice Floor

Welcome to The Practice Floor. Here we practice computer programming
using Code Katas. A [Code Kata](http://codekata.com/) is a small practice
programming problem. They may be solved multiple times using the same
or different technologies and approaches.

The Practice Floor is where you store all your practice sessions, ready to
be the seeds of your next practice session or the base for a real project.

## Structure and Usage

The main Git repository of the Practice Floor will not contain solutions,
aside from a few samples. Each person or group should create their
own version.

Each practice session should be short and goal directed.  Take a small
step forward. Since these are so small, you can repeat the same goal over
and over, honing your craft and making better code. Put every attempt
in a separate directory.

The directories are divided first into "goal". This is the code kata or
general concept you're creating. The simplest is `hello-world`. Others
could include `poker`, `chat`, or `pet-shop`

Under that directory, a new directory is created for every attempt to
complete a kata or work towards a goal. Directories are named with the
goal and technology or approach used. A numeric counter goes next, so you
can easily work on the same goal/kata with the same approach/technology.
Examples include `hello-world-java-cli-1`, `poker-react-4`, or
`chat-scala-akka-35`

## Setting Up Your Own

The Practice Floor is a directory structure and philosophy. To get the
directory structure, checkout your Practice Floor repo and add the
main Practice Floor Git repository:

```bash
git init
git remote add origin <your-git-URL>
git remote add template git@bitbucket.org:ziroby/practice-floor-template.git
git pull template master
```

If you want updated copies of the README's in the master template:

```bash
git pull template master
```

## Doing a Kata

1. Set a timer for twenty-five minutes. (Use the
[Pomodoro Technique](https://francescocirillo.com/pages/pomodoro-technique))

2. Pick a goal and technology. Goals are small steps on Katas, such as
   "Implement Poker Hello in Rust", or "combine micronaut-hello-2 and
   fizzbuzz-java-5 to make a micronaut Fizzbuzz"

2. If it's a new goal, make a directory and add a `README.md` to
   present the problem.  (The README can be pushed back to the master
   template Practice Floor repository with a pull request). Also copy
   Progress-sample.md to the directory, nanming it PROGRESS.md

4. Create a subdirectory under the goal directory. The file name format is
   goal-technology-iteration, like `hello-world-spring-boot-1`

4. Add a line to PROGRESS.md to specify the directory name and the
   goal you've set.

4. You may copy code from any other directory in the practice floor.

5. Try to get your goal complete in the time you have. Don't stress
   too much if you don't. This is practice, after all, and everything
   is a learning experience.

5. If you finish or get stuck, start over another attempt, or end this
   attempt early. Do not add time to the timer.

6. When you're done, add to PROGRESS.md how far you got and any lessons learned.

7. Commit and push to your personal Practice Floor.

## Disclaimer

All thoughts and opinions are my own. I do not represent my employer,
or any other party, in any way.

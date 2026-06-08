### Git and Workflow

**Goal:** Get your environment ready, understand the basic Git workflow, and successfully submit your first Pull Request.

This assignment is about learning how you’ll submit every future assignment.

**TIMELINE: 24 HOURS.**
- this assignment was published at **6/8/26 - 13:00**
- you should open your pull request till **7/8/26 - 13:00**

---
#### 1. Tools you need to install

Before anything else, install these:

- Git
- VS Code
- Obsidian (for notes)
	- write what you learn
	- save small explanations
	- keep confusion in one place

#### 2. GitHub setup

- login to github (set password and everything else. you'll use github everyday)
- create a personal access token
- store this token (you'll need it later)

#### 3. Fork the repository

Go here:

```
https://github.com/zareisajad/learning-path
```

- Click **Fork** (top right)
- This creates your own copy of the project.
- You will work inside your fork, not the original repo.

#### 4. Clone your fork

##### tip:
first enter below command once so git can store your credential you'll enter later.
so you don't have to enter username and password (access token) everytime.

```
git config --global credential.helper store
```

keep reading 

Open terminal:

```
git clone https://github.com/<your-username>/learning-path.git
cd learning-path
```

Now you have the project on your computer.

#### 5. Create a branch

Before starting any assignment, create a branch for it.

For this assignment:

```bash
git checkout -b assignment-00
```

You are now working on a separate branch.

Every future assignment should be completed on its own branch:

```text
assignment-01
assignment-02
assignment-03
...
```

This keeps your work organized and makes Pull Requests much cleaner.

You can verify your current branch with:

```bash
git branch
```

The active branch will have a `*` next to it.

(don't overthink these for now. it's ok if it looks confusing! just do the steps, you'll learn eventually)


#### 6. Keeping your repo updated (Sync Fork)

Before starting any new assignment, always sync your fork.

Go to your GitHub fork in browser and click:
**"Sync fork"**
Then on your machine inside local repository:

```
git pull
```

#### 7. Create your assignment folder

Inside your local repo create a file like this:

```
submissions/<your-github-username>/frontend/level-01/assignment-00/
```

Create a file inside it:

```
README.md
```

### 8. Your Assignment 00 content

Put this inside `README.md`:

```
## Assignment 00

By submitting this assignment, you agree to:

- You are responsible for completing assignments on your own
- You will not use AI unless the assignment allows you
- You will submit work via GitHub Pull Requests and this workflow
- You accept feedback and will make improvements when needed
- You respect the effort I am putting into this program by respecting to the timelines

#### Deadline & Responsibility

Each assignment has a timeline for a reason.
Not because I want to rush you, but because consistency is the main skill you're actually training here.

If you don’t follow the timeline:

- You fall out of rhythm
- You lose momentum
- You start overthinking instead of building

#### What happens if you miss a deadline

If you don’t submit an assignment within the expected timeframe:

- You can still submit it later
- I will still review it

But:

- It will be marked as **late**.
- If you submit an assignment **N days late**, then the next assignment will also be released **N days later than planned**.
- You’ll be expected to catch up on your own time.
- **if you miss 3 assignments in a row, the program will be STOPPED**.

This is not school.
No one is forcing you to do this.
But the trade-off is simple:

- If you treat this casually, you’ll get casual results.
- If you treat this like real work, you’ll build real skill.

The only thing you actually “lose” by not taking it seriously is time.
And in this field, time is the only real cost.

#### Important

When you hit a bug or something doesn’t work your first job is to try and solve it yourself.

That means:
- Read the error message carefully if theres any (or understand what you want)
- Google it
- Check documentation or examples
- Try small changes and observe what breaks or fixes it
- Break the problem into smaller parts

If the deadline passes and you are not finished, you should still submit your work.

- Even if it’s incomplete.
- Even if it doesn’t work.

I need to see:
- how you think
- where you got stuck
- what you managed to do before hitting the limit

So if you’re not done by the deadline, you still:
- commit your latest progress
- open the PR anyway
- explain what is missing in the a README file.

In real development, unfinished work is still part of the process.

---
I HAVE READ THIS AND AGREE.
Name:
GitHub Username:

- GOOD LUCK.
```

**YOU MUST READ THE CONTENT OF THIS FILE - DON'T SKIP IT**

#### 9. Commit your work

After creating the file:

```
git add -A
git commit -m "Complete assignment 00"
```

#### 10. Push to GitHub

```
git push
```

#### 11. Open Pull Request

Go to your GitHub fork.

You should see a button like:

> “Compare & Pull Request”

Click it.
Create the PR.
That’s your submission.

#### 12. What I’m checking for

- Correct folder structure
- You successfully opened a PR
- You understand basic Git workflow
- You can modify files and push changes


#### summary of workflow (important)

Every assignment will follow this cycle:

- Pull latest changes (sync)
- Create branch for that assigment 
- Add your files
- Commit changes
- Push to GitHub
- Open Pull Request
- Wait for my review and next assignment

That’s it. You’ll repeat this for every assignment.

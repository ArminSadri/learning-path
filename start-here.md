### Git and Workflow

> **Goal:** Get your environment ready, understand the basic Git workflow, and successfully submit your first Pull Request.

This assignment is not about frontend yet. It’s about learning how you’ll submit every future assignment.

**TIMELINE: 24 HOURS.**
- this assignment was published at **6/8/26 - 12:00**
- you should open your pull request till **7/8/26 - 12:00**

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

#### 5. Basic idea of Git workflow (important)

Every assignment will follow this cycle:

- Pull latest changes (sync)
- Create or edit files
- Commit changes
- Push to GitHub
- Open Pull Request

That’s it. You’ll repeat this for every assignment. (how? keep reading)

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

## 8. Your Assignment 00 content

Put this inside `README.md`:

```
## Assignment 00


#### How many hours are you willing to assign for learning per day? and how many days per week?
(Real number. Don’t guess “ideal”. Write what you can actually do consistently.)

---

By submitting this assignment, you agree to:

- You are responsible for completing assignments on your own
- You will not use AI-generated unless the assignment allows you
- You will submit work via GitHub Pull Requests and this workflow
- You accept feedback and will make improvements when needed
- You understand that progress comes from consistency, not speed
- You respect the effort I am putting into this program by respecting to the timelines

#### Deadline & Responsibility

Each assignment has a timeline for a reason.

Not because I want to rush you, but because consistency is the main skill you're actually training here.

If you don’t follow the timeline:

- You fall out of rhythm
- You lose momentum
- You start overthinking instead of building
- You slowly stop treating this like real practice

#### What happens if you miss a deadline

If you don’t submit an assignment within the expected timeframe:

- You can still submit it later
- I will still review it

But:

- It will be marked as **late**
- If you submit an assignment **N days late**, then the next assignment will also be released **N days later for you**.
- You’ll be expected to catch up on your own time
- **if you miss 3 assignment in a row the program will be STOP**

This is not school.
No one is forcing you to do this.
But the trade-off is simple:

- If you treat this casually, you’ll get casual results.
- If you treat this like real work, you’ll build real skill.

The only thing you actually “lose” by not taking it seriously is time.
And in this field, time is the only real cost.

---
I HAVE READ THIS AND AGREE.
Name:
GitHub Username:

- GOOD LUCK.
```

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




# FT-Potluck-Planner-5

<div align="center">



![snooplion](https://thumbs.gfycat.com/AdmiredAdventurousCaiman-size_restricted.gif)

| Resource | Link | Note |
|-|-|-|
| Trello | [trello-board](https://trello.com/b/JN4HNaJX/kanban-template) |  |
| Gitbook Notes | [git-book](https://app.gitbook.com/@bryan-guner/s/potluck-planner/~/settings/integrations) | Where I keep personal notes... feel free to use it too |
| Github Orginization | [potluck github org](https://github.com/FT-Potluck-Planner-5) |  |
| Experiment/documentation Repo | [experimental](https://github.com/FT-Potluck-Planner-5/Resources-Orginization-Experiment-Sandbox) |  |
| Slack Channel | [slack](https://lambda-students.slack.com/archives/C022PB42GKU) |  |
| Build Week Instructions | [notion build week](https://www.notion.so/Git-for-Build-Sprint-20ce2d09dc0e47b1af5d51821b54b810) |  |
|  |  |  |
|  |  |  |
|  |  |  |

  
  
  
  
  </div>


# Potluck Planner

## ☝️ **Pitch**

If you have ever tried to organize a potluck through text messages, online to-do lists or spreadsheets, you'll understand why this app is essential. 

In the world of social gatherings and potlucks the "Potluck Planner" is king. This is your place for all things pot luck.

## ✅  **MVP**

1. As an `organizer` I can create an upcoming `potluck` and invite my friends to attend

2. As an `organizer` I can adjust `date`s, `time`s and `location`s of the potluck

3. As an `organizer` I can use the list feature in my app to add food `items` that we'd like to see at the potluck

4. As a `guest` to a potluck I want to be able to confirm that I'm going to the upcoming `event`

5. As a `guest` I'd like to be able to select which `item`s I'd like to be responsible for bringing

**NOTE: All of the user stories above should only require a single user type. Users can create "potlucks" and add other users to them.**

## 🏃‍♀️ **Stretch**

1. Add a reminders functionality that allows users to link up their upcoming `date`s to their Google calendar.

2. Ability to upload multiple `photos` from the potluck gathering, like a photo gallery for a past event.

# Git for Build Sprint

# Git MVP

Git MVP includes 4 main requirements:

## 1. Use `main` as your primary branch

You must use `main` as your primary branch, which is the default when creating a new repository. 

**Why?**

- Branching from the branches other than the `main` branch can create opportunities for merge conflicts.

## 2. Feature Branch Naming

Feature branches must be named: `feature/<descriptive name>`

For example, if you're working on a feature that allows users to change the email address in their profile, the branch should be named `feature/change-email`

More info on branches and how to create a branch can be found [here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).

**Why**?

- Without a good naming convention, it is very easy to lose track of the purpose of a branch.

## 3. Delete Merged Branches

After a branch has been merged to the `main` branch, it must be immediately deleted.

**Why?**

- Short-lived branches are a best-practice for minimizing merge conflicts. Leaving many branches active in a repository makes it difficult for team members to navigate the on-going work. Once a branch has been reviewed, approved, and merged into the `main` branch, it should be immediately deleted.
- A healthy Git repository has a minimum of active branches.
- This is [easy to comply with using GitHub](https://help.github.com/en/github/administering-a-repository/managing-the-automatic-deletion-of-branches).

## 4. Build Sprint Git Workflow

*Following this workflow make it easier to collaborate with your teammates. It will also help prepare you for Labs, since it is very similar to the Git workflow you will use in Labs!* 

**The idea is that each Trello card should be on its own pull request as a feature!**

The Build Sprint Git Workflow is designed to prepare you for your Labs experience. You can learn more about Git & GitHub in Labs, check out the [Engineering Standards](https://labs.lambdaschool.com/) and [Labs Git Workflow.](https://docs.labs.lambdaschool.com/guides/coding/git-workflow)

## Getting Started

You're ready to work on a new Trello card - let's get started!

**WITHOUT FORKING,** clone your team's repository. 
After that always make sure you start with a recent copy of the repo.

### `> git checkout main`

### `> git pull origin main`

- To get started on your first task let’s make a branch. Making sure you are on the `main` branch, start a new branch with a name that matches or correlates to the task you are about to begin.
- The trick here is to think beyond yourself when naming the branch, stay aligned with your Trello board so you ***and*** others can easily make sense of it.

```jsx
git checkout -b [*feature/<descriptive name>*]
```

## Sharing Is Good

Now you have a branch to make all your awesome commits to! 

- Copying the description from the Trello card, which should summarize the actual work in the PR, create a **Draft Pull Request** using the `main`branch as the **base** after you have made your first commit.

Github created pull request drafts so that notifications will be turned off by default until you decide you are ready for review.  

![Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/draftPR.gif](Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/draftPR.gif)

## We have lift off!   🚀

Now we’re ready to make some awesome software. Committing and pushing our code regularly are habits worth having. Before we know it, we’ll be ready to take the PR out of draft mode.

Tip: do your best to be a great team member by making commit messages as clear as possible. They don’t have to be elaborate- keep it to the point.

### One small step  👨🏾‍🚀

When you feel you’ve completed the task you’ve been working on, it's time to: 

- Update the description
- Take the PR out of Draft Mode
- Make it "**ready for review**".

Ask someone in your team's channel to review your work. 

 

![Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/github-ready-pr.png](Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/github-ready-pr.png)

The team will then be notified of the PR and they can begin a review before merging it to the `main` branch.

Tip: Follow the team policy regarding the number of reviewers required before merging. It’s great practice to take the time and make comments in the code, even if just positive notes on good work your teammate did.

## Merging to `main`

If there are no conflicts to be resolved in the code choose `Rebase and merge` or `Squash and merge` from the `Merge` button.

![Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/github-merge.png](Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/github-merge.png)

If you find yourself with a merge conflict, there are a number of ways to solve it. The Github tools are very handy. You can also do it locally. When going down the local path, there is a good set of instructions [here](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-merges).

Your code changes are now on the `main` branch, ready to *wow!* users with your updates. 

Deploy your code (if not otherwise handled by Github Events) and be ready to support and address any issues that arise.

![Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/git_comic.png](Git%20for%20Build%20Sprint%201709b932890047dbbfdfef39267cf81b/git_comic.png)

Humor Break! 


# Web Development Lab — Student Profile Repository

This repository is for the **Build a Student Profile Repository Using Git and GitHub** activity (Team 4).

The aim is to practise the basic team GitHub workflow: each developer works on an assigned HTML page in a separate feature branch, opens a pull request, and the Team Lead reviews approved changes before they are merged into `main`.

## Team

| Student | GitHub username | Responsibility | Branch | File |
|---|---|---|---|---|
| Student 1 | `@instinct-coder1` | Team Lead and Reviewer | `main` | `README.md` |
| Student 2 | `@Nit-2520` | Profile Developer | `feature/profile` | `profile.html` |
| Student 3 | Username needs confirmation | Skills Developer | `feature/skills` | `skills.html` |
| Student 4 | To be added | Contact Developer | `feature/contact` | `contact.html` |

The Student 3 username supplied for the team was `MOHDFAIZ03!`. GitHub usernames cannot contain an exclamation mark, so please confirm the correct username before adding it. Add Student 4's name and username when available.

For a three-person team, assign the Team Lead responsibility to one of the developers as instructed in the worksheet.

## Expected repository structure

After all three developer pull requests have been reviewed and merged, the `main` branch should contain:

```text
Web-Dev-Lab_Exercise/
├── README.md
├── profile.html
├── skills.html
└── contact.html
```

The three HTML pages are assigned to the developers. Each developer must create and push their own page from their assigned feature branch.

## Team workflow

1. The Team Lead maintains this public repository and invites the team members as collaborators.
2. Every team member clones the repository to their own computer.
3. Each developer creates only their assigned feature branch and HTML file.
4. Each developer stages and commits their own work, then pushes the branch to GitHub.
5. Each developer opens a pull request from their feature branch into `main`.
6. The Team Lead checks the target branch, changed file and page content before approving a pull request.
7. Approved pull requests are merged into `main`.
8. The team checks that all three HTML files are present on `main` and prepares the repository, branch, commit and pull-request links for the instructor demonstration.

## Developer command reference

Run these commands in the cloned repository. Use only the branch and file assigned to you.

```bash
git clone https://github.com/instinct-coder1/Web-Dev-Lab_Exercise.git
cd Web-Dev-Lab_Exercise

# Example for the Profile Developer
git switch -c feature/profile

# Create or edit profile.html, then:
git add profile.html
git commit -m "Add student profile page"
git push -u origin feature/profile
```

For the other assignments, use `feature/skills` with `skills.html`, or `feature/contact` with `contact.html`. Each developer should run their own Git commands and open their own pull request.

## Team Lead review checklist

Before merging each pull request, check that:

- [ ] The pull request targets `main`.
- [ ] The source branch matches the developer's assigned branch.
- [ ] The pull request contains the correct assigned HTML file.
- [ ] The page content has been reviewed.
- [ ] The change is suitable to merge.

After all approved pull requests are merged, verify that `profile.html`, `skills.html` and `contact.html` are present on `main`.

## Submission details

- Team number: 4
- Repository: https://github.com/instinct-coder1/Web-Dev-Lab_Exercise
- Profile pull request: to be added after it is opened
- Skills pull request: to be added after it is opened
- Contact pull request: to be added after it is opened
- Merge confirmation: update after all three pull requests have been reviewed and merged

## Activity completion tracker

Update the [Activity Completion Tracker](https://docs.google.com/spreadsheets/d/1OPzZquflN6P_tYSYN6-3rBU5b8HkgwKk3lerEyo-JCo/edit?usp=sharing) only after the repository and pull requests have been checked.

---

**Repository naming note:** The worksheet specifies `student-profile-team-4`. This repository is currently named `Web-Dev-Lab_Exercise`, as selected for this work. Confirm with your instructor whether this name is acceptable before final submission.

# Hey Manny -- Here's What You Need To Do

## Step 1: Accept the Collaborator Invite
- Go to https://github.com/ismaelcaraballo-afk/git-practice
- You should see a yellow banner at the top asking you to accept the invite
- Click "Accept invitation"
- If you don't see it, check your email or go to https://github.com/notifications

## Step 2: Clone the Repo
Open your terminal and type:
```bash
git clone https://github.com/ismaelcaraballo-afk/git-practice.git
```
Then go into the folder:
```bash
cd git-practice
```

## Step 3: Create Your Branch
```bash
git checkout -b what-i-build
```
This creates a new branch called "what-i-build" and switches you to it.

## Step 4: Create Your File
Create a file called `building.md`. You can do this in your editor or in terminal:
```bash
echo "# What I Want to Build" > building.md
```
Then open `building.md` and write 1-2 sentences about what you want to build as a developer.

## Step 5: Add, Commit, Push (all in one line)
```bash
git add . && git commit -m "Add building.md" && git push -u origin what-i-build
```

What this does:
- `git add .` = stages all your changes
- `git commit -m "message"` = saves them with a message
- `git push -u origin what-i-build` = uploads your branch to GitHub
- `&&` = runs the next command only if the previous one worked

## Step 6: Open a Pull Request
- Go to https://github.com/ismaelcaraballo-afk/git-practice
- You should see a yellow banner saying "what-i-build had recent pushes"
- Click "Compare & pull request"
- Add a title like "Add building.md"
- Click "Create pull request"

## Done!
After that, we review each other's PRs and merge them.

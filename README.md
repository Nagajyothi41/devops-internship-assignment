
# DevOps Internship Assignment

## Phase 1 - Git & SSH

### git fetch vs git pull

git fetch:
- Downloads changes from remote repository.
- Does not merge changes into current branch.

git pull:
- Performs git fetch.
- Automatically merges fetched changes.

### SSH Setup

Generate SSH key:

ssh-keygen -t ed25519 -C "email@example.com"

View key:

cat ~/.ssh/id_ed25519.pub

Add key to GitHub Settings -> SSH and GPG Keys.

### Merge Conflict Example

1. Create feature-A
2. Create feature-B
3. Modify same line
4. Merge both branches
5. Resolve conflict
6. Commit changes

## Phase 2 - Flask Application

Features:
- Modern UI
- Health endpoint
- Ready for Dockerization
- Ready for Kubernetes

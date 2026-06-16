
# Merge Conflict Demo

git checkout -b feature-A
echo "Version A" > demo.txt

git checkout main
git checkout -b feature-B
echo "Version B" > demo.txt

git checkout main
git merge feature-A
git merge feature-B

Resolve conflict manually:

<<<<<<< HEAD
Version A
=======
Version B
>>>>>>> feature-B

Commit resolved version.

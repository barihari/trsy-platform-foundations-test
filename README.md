# Ensure you are in the main branch
git checkout main 

# Create a new branch for your PR
git checkout -b chore/initial-publish

# Make a tiny edit to the README
echo "Initial commit to trigger publish." >> README.md

# Stage, commit, and push the new branch
git add .
git commit -m "chore: initial commit of package files"
git push origin chore/initial-publish
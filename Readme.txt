# IT120 Activity 1 - Git Commands

# Initialize repository
git init

# Create initial files and first commit
git add .
git commit -m "Initial commit with Profile, Education, Background, Readme, and Test.py"

# Rename master to main
git branch -M main

# Create B1 branch and update Profile.txt
git checkout -b BAYANGF_B1
git add Profile.txt
git commit -m "Added Birth Place, Religion, etc. in Profile.txt for B1"

# Create B2 branch and update Education.txt
git checkout -b BAYANGF_B2
git add Education.txt
git commit -m "Added College and Program in Education.txt for B2"

# Create B3 branch and update Background.txt
git checkout -b BAYANGF_B3
git add Background.txt
git commit -m "Added contact person and address in Background.txt for B3"

# Create B4 branch, add Git commands to Readme.txt, and remove Test.py
git checkout -b BAYANGF_B4
git add Readme.txt
git rm Test.py
git commit -m "Saved Git commands in Readme.txt and removed Test.py for B4"

# Connect to GitHub remote repository
git remote add origin https://github.com/francinekaye/BAYANGF_IT120_Act1.git

# Push all branches to GitHub
git push -u origin main
git push -u origin BAYANGF_B1
git push -u origin BAYANGF_B2
git push -u origin BAYANGF_B3
git push -u origin BAYANGF_B4

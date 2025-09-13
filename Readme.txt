# Git Commands for Activity

## Main Branch
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/francinekaye/BAYANGF_IT120_Act1.git
git push -u origin main

## Branch B1
git checkout -b BAYANGF_B1
notepad Profile.txt
git add Profile.txt
git commit -m "Added Birth Place, Religion, etc. in Profile.txt for B1"
git push -u origin BAYANGF_B1

## Branch B2
git checkout -b BAYANGF_B2
notepad Education.txt
git add Education.txt
git commit -m "Added College, Program, etc. in Education.txt for B2"
git push -u origin BAYANGF_B2

## Branch B3
git checkout -b BAYANGF_B3
notepad Background.txt
git add Background.txt
git commit -m "Added Person to Contact, Address in Background.txt for B3"
git rm Test.py
git commit -m "Removed Test.py in B3"
git push -u origin BAYANGF_B3

## Branch B4
git checkout -b BAYANGF_B4
notepad Readme.txt
git add Readme.txt
git commit -m "Added Git commands in Readme.txt for B4"
git rm Test.py
git commit -m "Removed Test.py in B4"
git push -u origin BAYANGF_B4

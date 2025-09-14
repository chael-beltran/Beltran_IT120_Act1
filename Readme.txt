git config --global user.name "Chael Beltran"
git config --list
git config --global user.email "michaeljames.beltran@csucc.edu.ph"
git config --list
clear
cd
mkdir Beltran_IT120_Act1
cd Beltran_IT120_Act1
touch Profile.txt Education.txt Background.txt Readme.txt Test.py
pwd
cd ~/Desktop/Beltran_IT120_Act1
mv "/c/Users/ACER VERO/Beltran_IT120_Act1" "/c/Users/ACER VERO/Desktop/"
cd ~/Desktop/Beltran_IT120_Act1
code .
git init
git add .
git commit -m "Initial commit with base files"
git remote add origin https://github.com/chael-beltran/Beltran_IT120_Act1.git
git branch -M main
git push -u origin main
git checkout -b Beltran_B1
git add Profile.txt
code Profile.txt
git add Profile.txt
git commit -m "Added personal details to Profile.txt"
git log
git status
git log --oneline
git show ebee0fb
git push -u origin Beltran_B1
git checkout main
gt checkout -b Beltran_B2
git checkout -b Beltran_B2
code Education.txt
git add Education.txt
git commit -m "Added college info to Education.txt"
git log --oneline
git show b73efaa
git push -u origin Beltran_B2
git checkout main
git checkout -b Beltran_B3
code Background.txt
git checkout main
code Background.txt
git add Background.txt
git commint -m "Remove Person to contact info from main cause this should be in B3"
git commit -m "Remove Person to contact info from main cause this (should be in B3)"
git push origin main
git checkout Beltran_B3
code Background.txt
code Background.txt
rm Test.py
git add Background.txt
git commit -m "Added Person to contact address cause i forgot to add it in Background.txt B3 and remove Text.py"
git rm Test.py
git commit -m "Actually remove Test.py"
git push -u origin Beltran_B3
git checkout main
git checkout -b Beltran_B4
code Readme.txt
history
rm Test.py
history 
git add Readme.txt
git rm Test.py
git commit -m "Added all the git commands i use in this activity on Readme.txt and remove Test.py"
git push -u origin Beltran_B4
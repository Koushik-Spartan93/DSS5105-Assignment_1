## Steps follow to create a repositry in git hub and push the local code to github repositry using git. 


(base) koushik@Koushiks-MacBook-Pro ~ % cd /users/koushik/Desktop/DSS5105
(base) koushik@Koushiks-MacBook-Pro DSS5105 % git add checkerboard.py
(base) koushik@Koushiks-MacBook-Pro DSS5105 % git commit -m "Initial commit with checkerboard script"
[main (root-commit) b9c2ea8] Initial commit with checkerboard script
 Committer: Koushik K.S <koushik@Koushiks-MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 24 insertions(+)
 create mode 100644 Desktop/DSS5105/checkerboard.py
(base) koushik@Koushiks-MacBook-Pro DSS5105 % git remote add origin https://github.com/Koushik-Spartan93/DSS5105-Assignment_1.git
(base) koushik@Koushiks-MacBook-Pro DSS5105 % git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 673 bytes | 673.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Koushik-Spartan93/DSS5105-Assignment_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
(base) koushik@Koushiks-MacBook-Pro DSS5105 % 


Creating another branch 
(base) koushik@192 ~ % git branch
* dev
  main
(base) koushik@192 ~ %
(base) koushik@192 ~ % git add Desktop/DSS5105/checkerboard.py    
(base) koushik@192 ~ % git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   Desktop/DSS5105/checkerboard.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)

(base) koushik@192 ~ % git commit -m "change the color map"                   
[dev 1006c73] change the color map
 Committer: Koushik K.S <koushik@192.168.1.10>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 1 deletion(-)
(base) koushik@192 ~ % git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
(base) koushik@192 ~ % git push -u origin dev
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 378 bytes | 378.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Koushik-Spartan93/DSS5105-Assignment_1.git
   b9c2ea8..1006c73  dev -> dev
branch 'dev' set up to track 'origin/dev'.



Pull Request: 
 <img width="468" alt="image" src="https://github.com/user-attachments/assets/cf9d18b0-93f9-47e2-9a67-9b1d503bb2d5" />

 Merge request :
 <img width="468" alt="image" src="https://github.com/user-attachments/assets/64bdbfcf-3853-4da1-bd64-af2f78b88222" />





 


![image](https://github.com/user-attachments/assets/6804dc57-7c15-4995-a0d6-fcdfc446b45e)

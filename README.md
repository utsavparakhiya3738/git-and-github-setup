# git-and-github-setup For All Laptop and Desktop
1. Install git --> https://git-scm.com/install/windows<br>
2. Add Your Config into Git <br>
3. Open Git Bash Into Computer <br>
4. Paste Below CMD: <br>
git config --global --unset user.name <br>
git config -global --unset user.email <br>
git config --global user.name "utsavparakhiya3738" <br>
git config --global user.email "utsavparakhiya3738@gmail.com" <br>
5.check your git config (paste below cmd into gitbash) <br>
git config --list <br>
6. Check your email and username in given output <br>
7. create a project folder into computer (ex. News-Website)<br>
8. join your folder with github <br>
9. go to github website (login first)<br>
10. create a new repo (check for new btn into dashboard - green color btn)<br>
11. give a name to repo (ex. news-website)<br>
12. Click botton --> create a Repo (green botton)<br>
13. find the link that start with --> git remote add origin --> Copy that whole line<br>
14. open your vs code --> open terminal (check the menu click the option terminal --> new terminal) --> first check last words (ex. /News-Website>)<br>
15. paste the copy link(repo link) --> close the terminal<br>
16. create files, edit files, delete files into your folder<br>
17. open terminal and give below cmd one by one:
git add .
git commit -m "give a msg"
git push origin main (main --> branch name {check your working brach first and after tha t write the branch name})<br>
18. repeat the cycle
edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files<br>

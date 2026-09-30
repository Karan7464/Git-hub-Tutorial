<h2><b>Github Tutorial</b><br></h2>
<h3>Git</h3>
Version Control System is a tool that helps track changes in code>> Git is one of those.<br>
-popular, free, open source, fast, scalable etc.<br>
-track the history, collaborate.<br>
<h3>Github</h3>
-website that allows developers to store and manage their code using Git. In form of repo.<br><br>
Two steps:<br>
1.ADD (skip this step when we are on github already like now.)<br>
2.COMMIT
<h3>Configuring Git</h3>
GLOBAL>> when we want to work with only one account(easy way of expalning)<br>
so we have to remove credentials of previous used different github account.<br>
windows button >> search credentials manager >> windows credentials >> github related link tap on remove >> than run this commands.<br><br>
git config --global user.name "My name"<br>
git config --global user.email "someone@email.com"<br>
git config --list<br>
<h3>
  Clone & Status
</h3>
<h4>Clone:</h4>When we want to copy a repository on local(latop/pc) from remote(github).<br>
git clone <b>link</b><br>
entre in the main folder by cd <name>>tab changes directory.<br>
<h4>Status:</h4>
displays the state of the code<br>
git status<br>
<h5>Types:</h5>
<b>untracked</b><br>
new files taht git dosen't yet track<br>
<b>modified</b><br>
changed<br>
<b>staged</b><br>
file ready to commit<br>
<b>unmodified</b><br>
unchanged<br>
<h3>Add & commit</h3>
<h4>add-</h4>
adds new or changed files in your working directory to the Git staging area.<br>
git add <b>file name or . for all</b><br>
<h4>commit-</h4>
it stores the record of changes<br>
git commit -m "some msg"<br>
<h3>Push Command</h3>
push- upload local repo content to remote repo<br>
git push origin main<br>
  
<h2>Working with local folder.</h2>

note:cd..>> exit from current directory.<br>
mkdir NAME>> create a new directory. <br>
cd NAME(TAB)>> entre in that directory.<br>
ls>> all list in that directory <br>
ls-a(dir -Force)>> shows hidden files too.<br><br>
<h3>already existing project to upload on github.</h3>
<h4>Init Command</h4>
init- used to create a new git repo.<br> >> when we starts our project in local file only.<br>
Step1- git init(after open that project)<br>
Step2- Commit.<br>
Step3- New repo on github.dont add readme.<br>
Step4- git remote add origin <b>LINK</b><br>
Step5- git remote -v (to verify remote(git repo))<br>
Step6- git branch (to check branch)<br>
Step7- git branch -M main (to rename branch)<br>
Step8- git push (-u) origin main>> if we want to work on this project for now we can directly use git push.<br> 
Step9- Adding readme:<br>
  1.by git hub directly>> add file>> run in terminal >git pull origin main<br>
  2.add file name README.md >>push
  

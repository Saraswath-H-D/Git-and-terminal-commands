#linux commands
<br>
echo "hello" echo for print that word
<br>
whoami   get username
<br>
id   get all ids(gid,uid,groups)
<br>
id -un   also give username
<br>
pwd is for showing current working directory
<br>
rmdir   is to delete empty dirctories
<br>
cat f_nme  print elements in the file
<br>
cp src_file dest_file   is used for copy elemrnts from src file to destination
<br>
mv old_name new_name  used to rename 
<br>
rm f_name is used to remove file permanently
<br>
uname for os details
<br>
locate f_name   for get to path of db
<br>
touch f_name create empty files and timestamp
<br>
ln -s s_file link-file   to link file
<br>
clear
<br>
ps display process activitiy
<br>
man cmd_nme
<br>
grep UNIX  it will give text that have UNIX
<br>
wget url  used to download files frm intrnet usng url
<br>
sort f_name to sort contents
<br>
cal disp 
<br>
whereis path
<br.
wc f_name  count words and lines
<br>
cat>>f_name  u can write input


# git and terminal commands

this is my first.
<br>
author-saraswath
<br>
bye
<br>
git config --global user.name" "
<br>
git config --global user.email" "  in git dash
<br>
git config --list <br>
vs code down click and go to terminal
<br>
cloning means copy repository from github to local(computer) copy https from github in code
<br>
git clone link
readme file is for description
<br>
git status
<br>
cd folder name to change directory
<br>
git status <br>
new files with no commit are not able to track by git if we change something<br>
|_|->add(engage)->commit<br>
git add filename<br>
add used for teacking the untracking file
git add.(for all file)
git commit -m"any para"<br>
git push origin main (push local to github)<br>
cd.. for remove from ownership<br>
mkdir name for creating directory <br>
git init (to make it has git file)<br>
init command is used for making repo in local or vscode
become git repository<br>
git remote add origin <url> for push where we create repository using git init<br>
git remote -v to verify remote
git branch which branch<br>
git branch -M main to rename main branch name<br>
git push origin main<br>
git push -u origin main<br> if we want to repeatedly push -u is used that is after that if we write git push is enough
git commit -am "wdfd" for both add and commit if there is no taq
branch used for different work and merge
git checkout<branch name> for navigate our fav branch
git checkout -b<new brnch nme> for create new branch
git checkout -d<branch> for delelte
git push --set-upstream origin <branch name> 
git diff <branch name> compare 
git merge <branch name>
or by pulling request we can merge
pr also type of commit
git pull origin main from git to local to run updated code
to resolve conflict when we change differnt in same file with main and in subbranch it will not merge if we backspace we can resolve
git reset <filenmae> is we can remove last add at that file
git reset  remove last add of all file
git reset HEAD~1 we can remove last one committed line
git log for history
git reset <hash> we get from git log to reset multiple commits
git reset hard <hash> automatically will clear
fork new repository is used for copy from other or ours code 
node js open terminal or git bash 
type node
and type js commands
like console.log("hello")
type global to get to know wt in node js
.help to know wt commands
.exit to exit
touch script.js //to create file under file
type node in bash 
type process it gives all informatoin about current node
we can have process.cwd(),process.version,process.release
in bash if we want to search path type explorer.
in bash we type node script js hello bye to run hello bye are arguments also print when console.log(process.argv)typed and also for loop
type npm in git bash for seeing packages 
npmjs website can be seen   we can create our own packages send to developers
now create directory under backend call figlet using mkdir
and type npm i figlet to install 
in that we have node_modules where it stores dependencies of package that if we remove it it not run
package-lock.json will records all versions of installed dependencies
package.json contains descriptive metadata about project,such as name ,version and dependencies
if node_module is delelte then if we type npm install in bash it will install node_modules based on package.json
if we create directory and want to create package.json simply write npm init in bash it will ask author licensce everything if we install extra like npm i figlet it will add to package.json
we can install package globally by npm install -g figlet   and npm link figlet  but not recommend
npm install express
nodemon to automatically restart server with code changes
type npm install -g nodemon
npm init -y (-y)automatically fill related details package-lock.json
mongod --version
type mongosh in bash for typing mongodb cmds
type help after mongosh it will show list
show dbs
quit to exit 
it also can used for js
<test> in mongosh means temp default db
mdb works in bson format means convert json to binary format or also called documents
collection is many documents stores


#mongodb commands
type mongosh in gitbash
<br>
help command
<br>
show dbs
mongosh also java script part
when we open mongosh temp db create cld test
switched to db clge
we write in json but mdb store in bson
db.student.insertOne({name:"harry",dob:14,}) here if we directly type db.collectionme it will automatically create clction
db.student.find()
 db.student.insertMany([{name:"hat",age:17},{name:"shoe",age:21}])
 db.student.findOne({age:17}) give only one having age:17 and return og document
 db.student.find({age:17}) it is only cursor to original doc not return og doc so it show with []
 db.student.find({marks:{$gt:75}})
 db.student.find({city:{$in:["dehli","mumbai"]
 db.student.find({$or:[{marks:{$gt:75},{city:["dehli","mumbai"}])
 db.student.updateOne({name:"adam"},{$set:{city:"dehli"}})
 db.student.updateMany({name:"adma"},{$set:{city:"dehli"}})
 db.student.replaceOne({name:"admi"},{name:"adhi",city:dehli})




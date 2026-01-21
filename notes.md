command
git -v
git config --global user.name "Ahmad Abuzar"
git config --global user.email "ahmadabuzar0786@gmail.com"
 
to check config at global level

git config --global --list

making vs code default editor  
git config --global core.editor "code --wait";

cross platform compatibility -->
git config --global core.autocrlf true

initialiaze git into folder 
git init 
git add f1.txt   move to staging area
git add f1.txt f2.txt index.html  move to staging area(space de de kr file name)
git add .  (. mtlb sari file add kro staging area me)

git rm --cached f1.txt      move from staging to working area for the first file onlyyyyyy
git restore --staged filename.extension for rest of the time

git commit -m "First Commit"   to commit all files must be in staging area


git commit --amend -m "New Commit Message"  already bane commit me hi jodo no extra commit aur agr new commit msg jodna hai to ye lgao otherwise niche wala
git commit --amend --no-edit


rename a branch-->
git branch -m main  (main new name hai aur hmesha small letters me dena, isme respectfully hora)
git branch -M main  (main new name hai aur hmesha small letters me dena -M se forcefully change ho jaega)

.gitignore name ki file bnao usme fir jo bi file ka name lkhoge usko git p upload ni krega usually hm node_modules ko ni upload krte wrna code heavy ho jaega

src/*.html agr lkhe ,gitignore me to src ke and kisi bi html file ko ignore kr dega  (* means all file html wali *.js means allm js file )


commit ke baad hi chalana sirf ek baar
git remote add origin https://github.com/ahmadabuzar/GENAI.git --> to connect local(GENAI folder in pc ) repo to remote(GENAI github folder) repo 

             origin is aliasing for https://github.com/ahmadabuzar/GENAI.git 

git push -u origin main here main is teh branch name mtlb hamre case me master hai ---->to upload our code to github

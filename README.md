# GITHUB - homework (TXT)   
## 1. Create a remote repository called TXT
In the header on the main page on the right, click "+" ->   
In the dropdown, select "New repository"->   
In the required "Repository name" field, enter "TXT" ->   
Click the "Create repository" button at the bottom of the page   
## 2. Clone the TXT repository to the local computer
vvsen@Vadim MINGW64 /c/vadim/qa/github/TXT  
`git clone https://github.com/VSenakosau/TXT.git`   
Cloning into 'TXT'...   
remote: Enumerating objects: 3, done.   
remote: Counting objects: 100% (3/3), done.   
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0   
Receiving objects: 100% (3/3), done.   
## 3. Create a new.txt file inside the local TXT
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`touch new.txt`
## 4. Add the file to Git
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git add new.txt` or `git add .`   
## 5. Commit the file
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git commit -am "Add new.txt in git repo"`   
[main e36dff3] Add new.txt in git repo   
 1 file changed, 0 insertions(+), 0 deletions(-)   
 create mode 100644 new.txt   
## 6. Commit the file 


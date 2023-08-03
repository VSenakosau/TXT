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
## 6. vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git push`
## 7. Edit the content of the file new.txtx - write information about yourself (full name, age, number of pets, future desired salary). Write everything in TXT format
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`nano new.txt`   
```
Full Name: Vadzim Senakosau
Age: 36
Number of pets: 1
Future desired salary: $4900
```
## 8. Send the changes to a remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git commit -am "Send changes to new.txt to an external repository"`   
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git push`   
Enumerating objects: 5, done.   
Counting objects: 100% (5/5), done.   
Delta compression using up to 12 threads   
Compressing objects: 100% (3/3), done.   
Writing objects: 100% (3/3), 391 bytes | 391.00 KiB/s, done.   
## 9. Create a preferences.txt file
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`touch preferences.txt`   
## 10. In the preferences.xml file, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in TXT format
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`nano preferences.txt`
```
Favorite movie: 1+1
Favorite TV series: Braking bad
Favorite food: Shaverma
Favorite time of year: Summer
Party you would like to visit: Party on Bali
```
## 11. Create a skills.txt file, add information about skills that are going to be learned at the course in TXT format.
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`touch skills.txt`
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`nano skills.txt`   
```
  skill1: Basic theory
  skill2: Client-server architecture
  skill3: HTTP methods
  skill4: JSON, XML
  skill5: API testing via Postman
  skill6: Charles and Fiddler
  skill7: Dev Tools
  skill8: VPN
  skill19: Mobile testing
  skill110: Feature of iOS, Android
  skill8: Build iOS apps on XCode
  skill19: Android Studio
  skill110: ADB
```
## 12. Send two files at once to the remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git add . && git commit -m " add preferences.txt and skills.txt"`      
## 13. Send 2 files to an external repository at once
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git push`
## 14. On the web interface, create a bug_report.txt file   
Click "Add file", select "Create new file" -> Enter the file name bug_report.txt   
## 15. Make Commit changes (save) the changes on the web interface
Click the "Commit changes" button ->     
if necessary, enter the data in the Commit message and Extended description fields description ->   
Click the "Commit changes" button   
# 16. At the web interface, modify the bug_report.txt file and add the bug report in TXT format
Click on the file name ->      
Click on the "Edit this file" icon ->      
Enter data      
```
  id: 128
  severity: trivial
  priority: low
  title: The message in the tooltip begins with a lowercase letter when hovering over the image of the link "Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes on the https://capital.com/argentine-peso-forecast-ars" page
  environment: Windows 11 Pro , Chrome 112
  stepsToReproduce:
    step1: 1. Navigate to capita.com
    step2: 2. Scroll down to the "Financial News" block
    step3: 3. Click tab "Forex"
    step4: 4. Select section "USD latest: GBP/USD, EUR/USD, USD/JPY trading setups"
    step5: 5. Hover the cursor over the image of the links in the "USD latest: GBP/USD, EUR/USD, USD/JPY trading setups" section
  expectedResult: The text of the tooltips on each image starts with a capital letter
  actualResult: The text of the tooltips for the link image "Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes" begins with a lowercase letter
  attachment: URL to the video
  License: All
  author: SVadim
```
# 17. Make Commit changes (save) the changes on the web interface
Click the "Commit changes" button ->        
if necessary, enter the data in the Commit message and Extended description fields description ->      
Click the "Commit changes" button   
# 18. Synchronize remote and local TXT repository   
vvsen@Vadim MINGW64 /c/vadim/qa/github/txt (main)   
`git pull origin main` 
```
remote: Enumerating objects: 7, done.   
remote: Counting objects: 100% (7/7), done.   
remote: Compressing objects: 100% (5/5), done.   
remote: Total 6 (delta 2), reused 0 (delta 0), pack-reused 0   
Unpacking objects: 100% (6/6), 1.73 KiB | 74.00 KiB/s, done.   
From https://github.com/VSenakosau/TXT   
 * branch            main       -> FETCH_HEAD
   2a2106d..4b0422d  main       -> origin/main
Updating 2a2106d..4b0422d
Fast-forward
 bug_report.txt | 16 ++++++++++++++++
 1 file changed, 16 insertions(+)
 create mode 100644 bug_report.txt
```

 bug_report.xml | 19 +++++++++++++++++++
 1 file changed, 19 insertions(+)
 create mode 100644 bug_report.xml

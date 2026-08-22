# Git_Report.md
## cloning repo
Command: 
git clone https://github.com/deanlouisdejesus03312006-code/Software-Versioning-Lab.git

Response: 
Cloning into 'Software-Versioning-Lab'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (7/7), done.

## Making a new branch
Command: 
git checkout -b feature-update

Response: 
Switched to a new branch 'feature-update'

## Opened Readme.md in terminal
Command: 
.\README.md

No text response, opened Readme.md

## Staging entire local clone
Command: 
git add .

No Response

Command: 
git commit -m "Updated README with laboratory information"

Response: 
[feature-update 3ff926e] Updated README with laboratory information
1 file changed, 4 insertions(+), 1 deletion(-)

## Pushing to github
Command: 
git push origin feature-update

Response: 
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 378 bytes | 378.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature-update' on GitHub by visiting:
remote:      https://github.com/deanlouisdejesus03312006-code/Software-Versioning-Lab/pull/new/feature-update
remote:
To https://github.com/deanlouisdejesus03312006-code/Software-Versioning-Lab.git
 * [new branch]      feature-update -> feature-update
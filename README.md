# webhtml - simple html application
git checkout -b <name_version> - create new repo
git checkout -b v0.1.0 

Merge version
git checkout  v0.1.0
git rebase main
after that
git checkout main
git merge v0.1.0


docker build -f Dockerfiles/nginx/Dockerfile -t app_html_ng:0.1.0 .



Version 0.1.0
 bgcolor=purple, OS=ubuntu16, Version: 0.1.0
 
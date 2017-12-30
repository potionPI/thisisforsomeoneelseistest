Tried to get this up for someone else. (All the code is by Celina -W)

Anyway, it worked for them before I did this so it's moot point. But it's easier to use terminal.



## Instructions for whoever is super new like me:

1. Have your site files ready
2. jekyll new nameOfFile —blank
3. Stuff all the files into the nameOfFile
4. jekyll serve
5. bundle init
6. open Gemfile and replace # gem "ruby" with gem "jekyll" (yes, replace the #)
7. bundle install
8. showFiles (well, I mean just find a way to show hidden files)
9. touch .gitignore
10. edit .gitignore and add _site to it.
11. git init
12. git add .
13. git commit -m 'First commit'
14. remote add origin https://github.com/yourUser/repoName.git (or git remote set-url origin https://github.com/yourUser/repoName.git)
15. git remote -v
16. git push -u origin master
17. Now use netlify to stuff everything onto your GitHub 
18. When you update your site's folder on your computer...
19. git add .
20. git push -u origin master
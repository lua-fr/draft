
* https://www.lua.org/ftp/#manuals
* https://github.com/lua/manual/blob/master/manual.of

# html -> github
pandoc -s -t markdown_github manual.html -o manual.md

# html -> normal
pandoc -s -t markdown manual.html -o manual.md



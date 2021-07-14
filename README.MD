#demo
This is 2nd try to understand some error like =" error: src refspec main does not match any
error: failed to push some refs to 'github.com:dakiketan/demo.git'"

example: ketan@Ketan MINGW64 ~ (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'github.com:dakiketan/demo.git'

sol/out:

ketan@Ketan MINGW64 ~ (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 215 bytes | 107.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:dakiketan/demo.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

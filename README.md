two git repository: solegym  and solegym/public
the website is showed by directory solegym/public
soleym dir is the source code.

1. update website:
(1) cd xxx/solegym/
(2) hugo -d public
(3) hugo server

2. push to github:
(1) cd solegym/public && git add . && git commit && git push.  ---- push the website update
(2) cd solegym/ && git add . && git commit && git push.    ---- push the src update

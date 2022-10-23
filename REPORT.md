<h1> Report of Li Eugene, 311449, M33031</h1>
<h3> First task </h3>

<h3> Second task </h3>
<image src="./docs/2.1.png" />
<image src="./docs/2.2.png" />
Commands:

1. ```
   git rebase -i HEAD~2 
   ```
   <b> For squashing commits </b>
2. ```
   git checkout master 
   ```
   <b> No comments </b>
3. ```
   git merge ci
   ```
   <b> ... </b>
4. ```
   git branch -d ci
   ```
   <b> Delete branch </b>

<h3> Third task </h3>
<image src="./docs/3.png" />
Commands:

1. ```
   git reflog
   ```
   <b> For history </b>
2. ```
   git reset --hard <hash>
   ```
   <b> To move HEAD on lost commit </b>
3. ```
   git branch old-master
   ```
   <b> Make new branch </b>

<h3> Fourth task </h3>
<image src="./docs/4.png" />
Commands:

1. ```
   git log -L 32,32:prisma/seed.ts
   ```
   <b> For seeing history of line </b>

<h3> Fifth task </h3>
<image src="./docs/5.png" />
Commands:

1. ```
   git bisect start
   ```
   <b> To start bisecting </b>
2. ```
   git bisect good 8673a612
   ```
   <b> Point commit, where code works </b>
3. ```
   git bisect bad 086864e4
   ```
   <b> Point commit, where code doesn't work </b>
4. ```
   git bisect good/bad
   ```
   <b> If code works/doesn't work at this commit </b>
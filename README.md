# Git useful commands


## Discard unstaged changes

<code>
git clean -df

git checkout -- .

</code>

git clean removes all untracked files 
(warning: while it won't delete ignored files mentioned directly in .gitignore, 
it may delete ignored files residing in folders) and git checkout clears all unstaged changes.

-d: Remove untracked directories in addition to untracked files
-f: Force (might be not necessary depending on clean.requireForce setting)

<code>
git checkout .
</code>

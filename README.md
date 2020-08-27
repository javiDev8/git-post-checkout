# git-post-checkout

if you want to ignore some paths but only in some branchs, this script is for that.

this script edit the .gitignore file each time you checkout a branch, in this case ignores the "some/path" and "another/path" in any branch less master.
you can use it, for example, to ignore a build in the development branch but commit it in the master.

for use it just put the script in your/repo's/root/.git/hooks/ and edit it to your needs.

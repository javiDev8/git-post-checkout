# git-post-checkout

If you want to ignore some paths but only in some branchs, this script is for that.

This script edits the .gitignore file each time you checkout a branch, in this case ignores "some/path" and "another/path" in any branch less master.
You can use it, for example, to ignore a build in the development branch but commit it in the master.

For use it just put the script in your/repo's/root/.git/hooks/ and edit it to your needs.

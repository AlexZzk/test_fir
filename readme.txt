Git is a distributed version control system.
Git is free software.
Git has different branches and you can rollback anytimes you want.

These changes just for the test if I haven't commit the file.
Let's see what will happened.

I haven't commit following words.

If the file doesn't add to the cash area, the checkout function will 
delete all your modifications to the latest version on the branch.

Let's see if the file has add to the cash area.

Note:
if you add the file to the cash area,the checkout function doesn't wwork.
But if you add to the cash area and do other changes,and didn't add,
the checkout function will delete those changes.


Let's see what will happened.

Here I add this file to the cash.

I add some numbers here, but did not 'add';after that I use the checkout, The numbers are gone.

Different between checkout and reset HEAD:
the 'reset HEAD' will move the file from cash area to the local area, it will keep your modification on the local version.
the 'checkout' will undo your modify.

<!-- new edit begin 0723-->
I add those things in a new branch.


Git command:
查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

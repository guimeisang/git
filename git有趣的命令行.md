## git stash 命令行(储藏)
比如更改了代码，此时你需要切换分支，但是你不想提交你现在正在进行的工作；所以你想储存这些变更。为了往堆栈推送一个新的储存，只能进行git stash;
- git stash 暂存
- git stash list 罗列出所有保存在栈上的变更
- git stash apply [stash@{0}] 使用stash[0]上的储存
- git stash branch testchanges :  
如果你储藏了一些工作，暂时不去理会，然后继续在你储藏工作的分支上工作，你在重新应用工作时可能会碰到一些问题。如果尝试应用的变更是针对一个你那之后修改过的文件，你会碰到一个归并冲突并且必须去化解它。
如果你想用更方便的方法来重新检验你储藏的变更，你可以运行 git stash branch，这会创建一个新的分支，检出你储藏工作时的所处的提交，重新应用你的工作，如果成功，将会丢弃储藏。

## emoj
[请看这](http://www.webpagefx.com/tools/emoji-cheat-sheet/)

# ballball

### 跟着yxc的commit记录在搞一遍
Day1. 初始化工作和创建第一个网站
Day2. 创建文件结构,从url到urls.py到index.py到index.html  

这儿补充一下git, 我从当前a结点, git reset --hard HEAD~到了上一个结点b, 然后commit了一个新结点c, 此时新结点在HEAD上面, main上面, 然后我将结点c `git branch test_branch c的哈希值`.
但是此时main分支的HEAD和新分支的HEAD都是c, 所以我回到main分支, HEAD是c, 此时再git reset --hard a的哈希值, 这才回到了a结点. 自始至终a与c的结点的上一个结点都是b结点.


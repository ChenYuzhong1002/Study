[toc]

# Git

## Git基本用法

|                   method                   |               function               |
| :----------------------------------------: | :----------------------------------: |
|                `git add .`                 |           添加文件到暂存区           |
|                `git commit`                |         提交暂存区到本地仓库         |
|           `git commit -m '注释'`           |   提交暂存区到本地仓库，并添加注释   |
|                 `git pull`                 |          下载远程代码并合并          |
|    `git push <远程主机名> <本地分支名>`    |          上传远程代码并合并          |
|                `git status`                | 查看仓库当前的状态，显示有变更的文件 |
|             `git branch [-r]`              |    查看本地分支，`-r`表示远程分支    |
|        `git checkout [-b] <分支名>`        |    切换分支，`-b`表示创建新的分支    |
|   `git config --global user.name "xxx"`    |              设置用户名              |
| `git config --global user.email "x@x.com"` |             设置用户邮箱             |

## Git创建密钥

1. `git init`
2. `ssh-keygen -t rsa`
3. 在`.ssh`文件夹中查找密钥。Linux系统使用 `cat ~/.ssh/id_rsa.pub`查找





# 变量命名

**进位**   `carry`



# 函数用法

## `unordered_map<key,T>`

|    method    |                           function                           |
| :----------: | :----------------------------------------------------------: |
| `count(key)` |                   查找key为键的键值对个数                    |
| `find(key)`  | 查找key为键的键值对，并返回迭代器；如果未找到，<br />返回`end()`返回的迭代器 |
|  `begin()`   |                   返回第一个键值对的迭代器                   |
|   `end()`    |         返回一个指向最后一个键值对之后的位置的迭代器         |
|  `empty()`   |                 空，返回`true`；否则`false`                  |
|   `size()`   |                       返回键值对的个数                       |






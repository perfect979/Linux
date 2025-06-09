# Git指令

| 命令                                                         | 解释                                                |
| ------------------------------------------------------------ | --------------------------------------------------- |
| `git init`                                                   | 创建本地git仓库                                     |
| `git config --list`                                          | 查看当前配置列表                                    |
| `git config --global 要改项 内容`                            | 修改当前配置                                        |
| `git remote add origin "git@github.com:perfect979/Linux.git"` | 创建ssh仓库地址，并起origin名字                     |
| `git remote remove origin`                                   | 删除origin别名                                      |
| `git add file`                                               | 此命令可以将本地文件添加到git缓冲区                 |
| `git commit -m "提交说明"`                                   | 将本地git缓冲区数据提交到本地仓库，并记录一条提交项 |

## 创建ssh-key

| 指令                                          | 解释                   |
| --------------------------------------------- | ---------------------- |
| `ssh-keygen -t rsa -C "perfecr979@gmail.com"` | 创建安全链接           |
| `ssh -T git@github.com`                       | 测试本机是否与账户关联 |




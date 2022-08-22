# Hello,github!Git!

第一次使用，随便写写吧！

1. 练习1：在本地仓库修改readme文件，然后通过git提交到github;
- git add .
- git commit -m "RRR" # 提交并备注信息
- git push origin main
2. 练习2：在github上修改readme文件，然后通过git更新到本地仓库
- git fetch origin
- git merge origin/main   
3. 练习3：使用pull,等价于fetch+merge
- $ git pull origin/main 
```
# 报错如下：
  fatal: 'origin/main' does not appear to be a git repository
  fatal: Could not read from remote repository.

  Please make sure you have the correct access rights
  and the repository exists.
```
- $ git pull origin  # 成功



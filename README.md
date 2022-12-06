# Git Instruction


## 基本版本控制操作

```bash
  git status
```

>確認目錄狀況
<br>

```bash
  git add .
```

>新增所有新的檔案
<br>

```bash
  git add <filename>
```

>新增一個檔案
<br>

```bash
  git remote add origin <url> 
```

>連結網址的儲藏庫(repository)
<br>

```bash
git config --global user.name "ID"
```
>確認姓名
<br>

```bash
git config --global user.email <email>
```
>確認email
<br>


```bash
  git commit -m <message>
```

>將新增內容提交並留言
<br>

```bash
  git log
```

>查看本地提交狀況
<br>

```bash
  git push -u origin <branch-name>
```

>將提交內容推到github
<br>


## 分支合併

```bash
  git branch -M <branch-name>
```

> 新增一個分支
<br>

```bash
  git checkout <branch-name>
```

> 切換到另一個分支
<br>

```bash
  git merge <branch-name>
```

> 把<branch-name>的分支合併到當前分支
<br>

# merge 方法
## 所有檔案資料夾 merge
  1. 把要 merge 的分支都 push上github
  
  2. 輸入 git merge <branch-name>
  
  3. 再 push 上去一次完成了之後

## 單一檔案 merge
  1. 把要 merge 的分支的檔案都 commit
  
  2. 輸入 git merge <branch-name>
  
  3. 如果有錯誤則 fix it 否則 abort
  
  4. 再 push 上去一次完成了之後

<br>
<br>
  
## 其他參考資料
  
  1. 懶人包:
  <https://ithelp.ithome.com.tw/articles/10271811/>
  
  2. 完整語法:
  <https://backlog.com/git-tutorial/tw/stepup/stepup2_3.html/>

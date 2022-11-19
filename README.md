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

# merge方法

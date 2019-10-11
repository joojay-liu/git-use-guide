#### 1. 已有本地库，如何上传到github中?

```
git init
git add . -A
git commit
git remote add origin https://xxx
git push -u origin master
```

#### 2. 如何修改单个项目的用户名和邮箱?

```
git config user.name 'joojay'
git config user.email 'joojay@126.com'
```

#### 3. 如何修改全局的用户名和邮箱

```
git config --global user.name 'joojay'
git config --global user.email 'joojay@126.com'
```